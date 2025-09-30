---
description: Explains why some chunks in the distance look weird
everyone: true
---

BlueMap uses a concept known as Level of Detail (LOD, for short)
This means that there are different quality levels, *detail* levels, of the 3D models of your world.

Close-by to the camera, it will use the perfect replica 1:1 level.
We call this the "hires layer".
However, for the chunks further away in the distance, it will use lower quality 3D models.
We call this the "lowres layer".
There are in fact multiple different lowres layers, for varying levels of distance.
This allows BlueMap to show chunks much further away than in Minecraft itself.
However, those chunks do look a bit less good than the ones close by.

You can increase the distance at which the hires chunks show, by going into the BlueMap settings menu on the website, and bumping up the render distance slider labelled "hires layer".
You can also increase the "lowres layer" slider, to see even further into the distance, but with the lower quality 3D models instead.
Please keep in mind that this will be very intense on the device that you are viewing the map on, as it really is quite heavy to render so many high quality chunks.
