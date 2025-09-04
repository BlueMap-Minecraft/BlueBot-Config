---
description: Some things you can try to hopefully get around Windows Server issues
everyone: true
---

Windows Server (not Home, Pro or Enterprise) has some issues with BlueMap, sadly
Here are some things you can try:
(Your mileage may vary, though!)
- Exclude BlueMap from Windows Defender. [Here is a guide](<https://github.com/BlueMap-Minecraft/BlueMap/issues/471#issuecomment-1837283254>)
- Make sure the drive you're storing BlueMap on uses NTFS as format
- Make sure BlueMap's data is on the main C: drive
- BlueMap 5 has a new hidden setting in `storages/file.conf`:
  You can add `atomic: false` to disable the whole `.filepart` stuff, which makes it just directly write the files.
- Use an SQL database instead of file storage. The SQLite type is the easiest to set up :)   [Here is a guide on how to set that up](<https://bluemap.bluecolored.de/wiki/customization/Storages.html>)
