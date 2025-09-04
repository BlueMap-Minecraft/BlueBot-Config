---
description: How to convert PebbleHost's SQL Link to a proper JDBC link for BlueMap
everyone: true
---

# How to use SQL on Pebblehost:

This is the link Pebblehost gives:
`mysql://customer_123456_bluemap:abcdefghijklmnop@eu01-sql.pebblehost.com/customer_123456_bluemap`
To make it work with BlueMap, we will need to modify it a bit, though.

1. Open the config file `storages/sql.conf`, and paste this <:this:796819248580132884> link into the `connection-url:` setting.

2. Take out the **username** and **password**:
`mysql://eu01-sql.pebblehost.com/customer_123456_bluemap`

3. Move them to the `connection-properties:` section in the config:
```yaml
connection-properties: {
    user: "customer_123456_bluemap",
    password: "abcdefghijklmnop"
}
```
4. Put `jdbc:` in front of the link:
`jdbc:mysql://eu01-sql.pebblehost.com/customer_123456_bluemap`

5. Reload BlueMap with the command `/bluemap reload`
