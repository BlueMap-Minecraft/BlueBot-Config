---
description: How do I make BlueMap take up less space?
everyone: true
---

### Here are some things you can do to make your maps smaller on your storage:
- You can limit the size of your map, by setting maximum X and Z coordinates. To learn more about this, do </minmax:1413273815454322710> in <#803532169955508234>
- By default, BlueMap removes caves already, but you can set it to remove caves a bit more rigorously by setting the `remove-caves-below-y` value higher. To learn more about this and to get more tips on how to save a bit of storage space by removing caves, do </caves:1413273815223369913> in <#803532169955508234>
- If you have a ton of leaves, installing [this](<https://modrinth.com/resourcepack/bluemap-nttl>) resourcepack on your BlueMap may save a small bit of storage. It removes the geometry between the leaf blocks. This is like setting Minecraft in-game to fast graphics.
- If you're fine with having a high quality 2D-only map, instead of a fully 3D map, you can disable `enable-perspective-view` and `enable-free-flight-view` ([example](<https://bluecolored.de/bluemap/#overworld_2d:-822:49:411:132:0:0:0:1:flat>))
- If you want to be extremely rigorous and if you only need the zoom-out map, then you can disable saving the hires-tiles, by setting the `enable-hires` option to `false`. Keep in mind that you won't have the full 3D-Model when you zoom in... But the map will be MUCH smaller ([example](<https://bluecolored.de/bluemap/#overworld_lowres:-808:38:422:214:-0.02:0:0:0:perspective>))

All of these options are in each map config.
You can use more than one of these at the same time.
