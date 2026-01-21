---
description: How to use the min and max options to crop your map
everyone: true
---

In your map's `.conf` file, there are options for cropping your map:
```php
render-mask: [
    {
        min-x: 4317
        max-x: 6304
        min-z: 3478
        max-z: 4702
        #min-y: 50
        #max-y: 100
    }
]
```
You can set those to any amount you want to limit how far your world will be rendered on each axis.

**Don't forget to remove the `#` in front of them when you modify it, otherwise it will be ignored!**  
You can leave the `#` in front of the `min-y` and `max-y`, though, as you probably don't want to limit the height of your world.

Make sure to run `/bluemap reload` to reload the config that you just changed!  
In some cases you might need to use `/bluemap fix-edges <map-id>` to tell bluemap to rerender the map along the new and old borders.

(If you changed the `min-y` or `max-y`, you must also run `/bluemap purge <map-id>` to _delete and rerender_ your map.)

For more advanced usage of render masks, see the wiki: <https://bluemap.bluecolored.de/wiki/customization/Masks.html>

https://cdn.discordapp.com/attachments/1241798015266717717/1402648718385090611/minmax.jpg?ex=6894adea&is=68935c6a&hm=80155e37dd8b542660af0ecbfdfca847d0f4dfde5e42ac3312f40cf7be52df63&
