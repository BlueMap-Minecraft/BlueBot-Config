---
description: A step-by-step diagnostic guide on checking missing map area
everyone: true
---

To diagnose chunks not appearing on the map, let's try these diagnostic steps:
1. Pick a location in the world that isn't rendered but _should_ be rendered.
2. Send the outputs of `/bluemap debug world [map] [x y z]` and `/bluemap debug map [map] [x z]`, where the coordinates are of the spot you picked in step 1.
  -# If you are using the mod/plugin. If you're using the CLI, you cannot do this sadly...
3. Join your server.
4. Go to the spot you picked in step 1, to make the server load the chunks in that area.
5. Stand there for a solid 30 seconds.
6. Restart the server fully (no reloads!).
7. Wait a couple minutes.
8. Do `/bluemap` and verify that the render threads are idle (if not, wait longer until they are).
  If you are using the CLI, read the logs, verify that the render threads are idle (if not, wait longer until they are).
9. Open the map, and click the `Update Map` button.
10. Tell us, is the unrendered area now rendered?
11. Send the outputs from the same exact commands from step 2 again, so we can see how they changed.
