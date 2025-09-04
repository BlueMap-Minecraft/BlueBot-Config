---
description: How can i change the ip?
everyone: true
---

By default, the webserver binds to **all network-interfaces** that are available. That's what the placeholder `0.0.0.0` (or `::0`) means :)
This works perfectly on almost all servers and in **almost all cases you don't need to set/change the ip-setting!**

Just connect using your public server-IP and the port, like this: `http://<public-ip>:<port>/` :)

If you still want to manually set the IP that the webserver binds to, you can just add a line to your `webserver.conf` with something like this:
```yaml
ip: "127.0.0.1"
```
