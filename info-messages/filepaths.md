---
description: A quick tldr about all BlueMap's different filepath configs
everyone: true
---

BlueMap's different filepath configs, tldr explanation:
`core.conf`  →  `data`:  run-time state
`webapp.conf`  →  `webroot`:  webapp files
`webserver.conf`  →  `webroot`:  webroot to host the webapp from (usually the same as <:this:796819248580132884>)
`storages/file.conf`  →  `root`: the actual 3D models (if you're using an external webserver, it should be at `<webroot>/maps` for the webapp to work correctly)
