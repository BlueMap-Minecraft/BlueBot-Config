---
description: How to do a clean BlueMap install
everyone: true
---

To do a clean BlueMap install:
1. Shut down your server
2. Make a backup
3. Delete your current `BlueMap-X-YZ-platform.jar`
4. Delete the BlueMap config directory (`plugins/BlueMap` or `config/BlueMap`, depending on your platform)
5. Delete the bluemap data directory (the `bluemap` folder in your server root, the one with the `web` folder in it)
6. Put the new jar on your server
7. Reconfigure BlueMap again, from these newly generated, fresh, configs
  You can keep the configs from your backup aside, to help you with the porting.
