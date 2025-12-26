---
description: How can i access my map?
everyone: true
---

### How can I open my map?
By default, use your servers public ip-address (e.g. `123.45.67.8`) and the port (`8100`) like this:  
`http://123.45.67.8:8100/`  
and enter that in your browsers address bar.  

Make sure you replace `123.45.67.8` with **your** server-ip. *(The same ip that you are using to connect to your minecraft-server.)*  
And replace `8100` with the port you assigned to bluemap.

### I still can't access the website!
Here is a checklist:
- When bluemap loads, you should have this message in your server-console/log: 
  ```
  WebServer bound to all network interfaces on port 8100
  Webserver started...
  ```
  If not, look for any errors/warnings and check the configuration again.
- Make sure you are using `http` and not `https` when connecting to the webpage.
- Is the port (`8100` by default) open and forwarded correctly? Or is your firewall blocking incoming connections 
  on the port? And is the port configured for your container?

### :warning: If you still have problems accessing your map after that, please answer these questions: :warning:
1. How / on which host you are hosting your server? Explain your complete setup.
1. Is your server running in something like [Pterodactyl](<https://pterodactyl.io/>), [Docker](<https://www.docker.com/>), [CasaOS](<https://casaos.zimaspace.com/>) or anything container-like?

:)
