---
description: How to disable free flight
everyone: true
---

Disabling free flight is not a good method to prevent people from seeing things they shouldn't see.
BlueMap always sends the full 3D models it generated to people viewing your map. Limiting the camera doesn't prevent people from receiving that data.
A better way to do this would be to tweak what gets put into the 3D models in the first place.
By default, BlueMap *already* tries its best not to render caves, and other underground structures.
There is a guide here that explains how to further tweak the cave detection systems, in case the default values don't quite do what you want yet:
<https://bluemap.bluecolored.de/community/CaveRendering.html>
And you can hide ores with this:
<https://www.spigotmc.org/resources/bluemap-no-ore-texture-pack.90535/>

If you still want to disable free flight, you can do that per map (in each map config), with the `enable-free-flight-view` setting. But keep in mind that people can still enable it on their browsers by running a JavaScript command. There's nothing you (or we!) can do about that.
