---
description: Some info about BlueMap's performance
everyone: true
---

BlueMap is rendering completely **off** the server thread, asynchronously.
It can render with multiple threads at the same time, speeding up your render significantly. You can adjust the amount of threads that you want BlueMap to use, to have the best render-speed while not causing any lag on your server :)
To do that, open `core.conf` and set the `render-thread-count` option to whatever amount you want!

For example, if you have e.g. 4 CPU-Cores, you can set BlueMap to use 1-2 render threads, and your server will still have 2-3 CPU-Cores to use for other things during a render.
Test how your server performs and adjust the render-threads as needed.

If you already have your `render-thread-count` set to `1` but the server is still not performing great, then you can also tell BlueMap to pause all rendering when someone is online and only update the map while the server is empty.
To do that, open the `plugin.conf` and set `player-render-limit` to `1`.
