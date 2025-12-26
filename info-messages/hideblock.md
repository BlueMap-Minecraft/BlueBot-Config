---
description: How to hide specific blocks on the map
everyone: true
---

To hide specific blocks, you can create a resource-pack.
With a resource-pack, you can make BlueMap render any block as anything else, _including air_, which effectively hides the block.

So create a zip file with this file in it:

`CustomPack.zip/assets/<namespace>/blockstates/<block-id>.json`
```json
{
  "variants": {
    "": {
      "model": "minecraft:block/air"
    }
  }
}
```
Do this for all blocks you wish to hide.

Once you're done, put that zip into BlueMap's `packs` folder.
Then rerender your map(s) with `/bluemap purge <map-id>`
