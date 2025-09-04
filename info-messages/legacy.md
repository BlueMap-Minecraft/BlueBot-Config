---
description: How to use BlueMap on 1.12
everyone: true
---

BlueMap's latest versions don't support Minecraft 1.12.2 anymore. The last version that supports 1.12.2 was BlueMap v1.5.5.
Only Spigot, SpongeForge, and the BlueMap CLI are supported for 1.12.
If you have a modded Forge server, you will need to use SpongeForge to load BlueMap.

Please also double-check that your modpack doesn't include one of the incompatible mods:
<https://github.com/BlueMap-Minecraft/BlueMapWiki/blob/9ffe114fae2bef3cf4eec8b3e0567d7b45a3ab82/wiki/FAQ.md#known-incompatibilities-with-other-mods>

You can download v1.5.5 here: <https://github.com/BlueMap-Minecraft/BlueMap/releases/tag/v1.5.5>
Then start the server, go to `config/bluemap/core.conf` and set the `accept-download` setting to `true`

Now you can also check the `render.conf` file and manage your maps there, in case you want to change something :)

Then type `/bluemap reload` and it should work

Also, here's an old version of the BlueMap Wiki page about mods, that explains how to get them rendering properly in 1.5.5: <https://github.com/BlueMap-Minecraft/BlueMapWiki/blob/9ffe114fae2bef3cf4eec8b3e0567d7b45a3ab82/wiki/customization/Mods.md#configuring-mods>
