---
description: Some info about BlueMap's performance
everyone: true
---

BlueMap is rendering completely **off** the server thread, asynchronously.
It can render with multiple threads at the same time, speeding up your render significantly. You can adjust the amount of threads that you want BlueMap to use, to have the best render-speed while not causing any lag on your server :)
To do that, open `core.conf` and set the `render-thread-count` option to whatever amount you want!

For example, if you have e.g. 4 CPU-Cores, you can set BlueMap to use 1-2 render threads, and your server will still have 2-3 CPU-Cores to use for other things during a render.

Also note, that the more threads are active, the more RAM will be needed. So just test how your server performs and adjust the render-threads as needed.
