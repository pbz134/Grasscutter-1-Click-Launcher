# Grasscutter-1-Click-Launcher
A 1-Click Launcher for Grasscutter, with an easy configuration
Original: https://github.com/Grasscutters/Grasscutter

**Features**

- No installation required, simply download, decompress and launch
- Everything is configured automatically
- Save Backup/Restore function with 3 save slots (can be expanded easily by changing the script)
- Automatic Banner Rotation every 21 days to simulate the original banner scheduling
  
**Setup Tutorial**

- Download my 1-Click Launcher
- Extract the .7z file with 7-zip or WinRar
- Install the included MongoDB and MongoDB Compass setups (two .exe files)
- Download all the "Complete Game Part" files 1 through 6 from here: https://www.reddit.com/r/Genshin_Impact/comments/15qisqg/direct_download_links_for_genshin_impact_40/
- Download a voice-over pack from here (English): https://autopatchhk.yuanshen.com/client_app/download/pc_zip/20230804185804_eTmE8EZjJZdAJapq/Audio_English(US)_4.0.0.zip
- After downloading all Game parts and the voice-over pack, decompress the archives with 7-zip or WinRar
- Merge the voice-over pack files with the Game parts
- Put the game files in /GenshinImpact_4.0.0 (so that Genshinimpact.exe is directly inside the /GenshinImpact_4.0.0 folder)
- Execute Launch.bat to open the game launcher
- In the UI, click the small yellow button next to "Launch", and then the "Launch" button

**Troubleshooting**
If facing any errors, make sure you:
- Check out the "Tips & Fixes" folder inside the 1-Click Launcher files
- Open the UI with "Launch.bat", click the Download icon at the top next to the cog icon and click "Download AIO" (This will update the server files in case they are outdated)
- Make sure all files are placed correctly
- In case anything went wrong, navigate to the 1-Click Launcher directory, open the "Utils" folder and execute "#FullReset-DeleteAllCopiedFiles"

**Banner Rotation (Optional)**

- Open the Windows Task Scheduler
- Right click on the "RotateBannersEvery21Days" task in the list
- Click on "Properties", then tick "Run task as soon as possible after a scheduled start is missed"

More information available inside "#INFO.txt" (German)
