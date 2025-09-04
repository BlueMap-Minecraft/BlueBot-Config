---
description: The `map-update-interval is only a fallback`
everyone: true
---

The `full-update-interval` option is only a fallback
BlueMap works by looking at your world files
If they are updated, BlueMap starts rendering all the changes from there
On some systems (=almost none) those file watchers that BlueMap uses to check if the world files got updated don't work well
That config option is there for those systems, to make them forcefully check for updates
