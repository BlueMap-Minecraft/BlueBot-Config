---
description: How to get the in-game chat on BlueMap
everyone: true
---

There are currently two chat addons that we know of:
- [BlueMap Chat Markers](<https://github.com/TechnicJelle/BlueMapChatMarkers>), which is more simple, and just shows the chat messages from in-game on the map, as temporary markers on the location where the chat message was sent
- [BlueMap-Chat](<https://github.com/Chicken/Auth/tree/master/BlueMap/Chat>), which is more advanced, and shows all chat messages in a box in the bottom left of the screen. This addon allows you to chat from the map to the game!

**Background:**
BlueMap on its own has fewer additional features built-in than some other maps may have, which allows Blue (the dev) to focus on making the map itself better!
But he provides a very solid API that allows *other developers* to easily extend BlueMap through addons that add functionality like this, instead!
It's a more modular system, as opposed to a monolithic system

Chat, specifically, can get VERY difficult to get right if you want all the features. Especially regarding security!
