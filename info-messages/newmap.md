---
description: How to add new maps to BlueMap
everyone: true
---

**Manually add new maps:**
Here is an explanation on how to manually add a new map to BlueMap: https://bluemap.bluecolored.de/wiki/getting-started/Configuration.html#configuring-your-maps-adding--removing-maps

**Automatically generate map configs for all loaded worlds (again):**
If you don't want to manually create a map config for your new map(s), you can also let BlueMap create them automatically, by following these steps:

1. Shut down your server.
2. Rename the `bluemap/maps/` folder (the one with the .conf files in it) to `maps.bak`.
3. Start your server.
4. Stop your server.
5. The maps folder should be regenerated now, with new, fresh config files in it, so go into it.
6. Edit the new configs to your liking, using the backup you made previously in `maps.bak` as reference.
