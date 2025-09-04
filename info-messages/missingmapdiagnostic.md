---
description: A step-by-step diagnostic guide on checking missing map area
everyone: true
---

To diagnose chunks not appearing on the map, let's try these diagnostic steps:
1. Join your server
2. Go to an area that's not rendered, to make the server load the chunks in that area
3. Stand there for a solid 30 seconds
4. Restart the server fully
5. Wait a couple minutes
6. Do `/bluemap` and verify that the render threads are idle (if not, wait longer until they are)
7. Open the map, and click the `Update Map` button
8. Is the unrendered area now rendered?

Please also send the output of
`/bluemap debug map <map> x z`
