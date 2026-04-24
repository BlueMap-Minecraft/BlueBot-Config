---
description: How to do a clean BlueMap install
everyone: true
---

To do a clean BlueMap install:
1. Shut down your server
1. Make a backup
1. Delete your current `BlueMap-X-YZ-platform.jar`
1. Delete the BlueMap config directory (`plugins/BlueMap` or `config/BlueMap`, depending on your platform)
1. Delete the bluemap data directory (the `bluemap` folder in your server root, the one with the `web` folder in it)
1. Put the new jar on your server
1. Start the server
1. Reconfigure BlueMap again, from the newly generated, fresh, configs  
  You can keep the configs from your backup aside, to help you with the porting.
