# DayZCommunityOfflineMode Namalsk Edition 1.0a

**Thank you to Arkensor for his Mod DayZCommunityOffline Mode**
**For without his Mod this would not exsit**  

The DayZ Community Offline Mode Namalsk Edition offers the ability, to explore the world of DayZ in a singleplayer environment on the Namalsk Map. While this mode does not represent the actual DayZ gameplay it offers other possibilites for developers, content creators and player who do want to experiment around but not loose all their progress from online.

This is UNOFFICIAL, so don't blame the DayZ development team if this is not working at all for you!

# Important Warning

You Must Have Namalsk Island and Namalsk Survival mods downloaded and Installed to play this Mod .. The mod folders you need to play Namalsk is not included with this download.
* To download Namalsk Island please visit the steam store [HERE](https://steamcommunity.com/sharedfiles/filedetails/?id=2289456201)
* To download Namalsk Survival please visit the steam store [HERE](https://steamcommunity.com/sharedfiles/filedetails/?id=2289461232)

# Info for server owners & mappers
There is now a wiki page available on how to use the community offline mode to spawn map objects on your server or mission you are working on: [Add custom objects to your server or mission](https://github.com/Arkensor/DayZCommunityOfflineMode/wiki/Add-custom-objects-to-your-server-or-mission)

# Installation:
To Download ```Namalsk Island``` and ```Namalsk Survial``` please visit the steam store https://steamcommunity.com/sharedfiles/filedetails/?id=2289456201 and https://steamcommunity.com/sharedfiles/filedetails/?id=2289461232 and click on Subscribe and wait for steam to download the Workshop content, Once installed Run DayZ via Steam by clicking play on the DayZ page from within your game libary, when the Steam DayZ Launcher screen shows, Click on Mods on the menu to the left, Find ```Namalsk Island``` in your mods List and click the drop down box arrow to the right of the Namalsk Island line, Click the 3 dotted line to ```"Display More Options"``` and select "Open Folder in Windows Explorer", Click "I understand" in the next window, now copy ```@Namalsk Island``` and ```@Namalsk Survival``` folders, press up one level in your current folder and paste the ```@Namalsk Island``` and ```@Namalsk Survival``` folders into the DayZ folder that you should now be in ```C:\Program Files (x86)\Steam\steamapps\common\DayZ```

Download [THIS](https://github.com/CypherMediaGIT/DayZCommunityOfflineMode-Namalsk-Edition/releases/download/1.0a/NamalskCommunityOfflineMode.zip) zip archive.  
Make sure you are on the latest `STABLE` or `EXPERIMENTAL` version of the game.

Unpack and Place the ```DayZCommunityOfflineMode.namalsk``` folder inside your ```Missions``` folder in the DayZ game directory (```For example: C:\Program Files (x86)\Steam\steamapps\common\DayZ```).  
Even though this is not directly bannable by Battleye, just to make sure: Rename your Battleye folder to Battleye.disabled, and rename the DayZ_BE.exe to DayZ_BE.exe.disabled.

Now you now start the script ```DayZ/Missions/DayZCommunityOfflineMode.namalsk/DayZCOfflineMNamalsk.bat``` to start the game. You will be loaded directly into the offline mode.  
Or add the following start parameter to your game: ```-mission=.\Missions\DayZCommunityOfflineMode.namalsk```

To unstinstall this mod, simple delete all downloaded files, and rename your .disabled folders back to their original name.   
You might delete your whole ```Missions``` folder and validate your game files via steam to get the original DayZ files back.

# Controls:
* Y (Z for QWERTZ-Keyboard) - Open the COM toolbar menu.
* X - Toggle Autojog/walk/run
* X + SHIFT - Enable Autorun (Just X to disable it again)
* X + CTRL - Enable Autowalk (Just X to disable it again)
* END - Teleport at the position you are looking at
* O - Spawn a random infected (Zombies)
* O + CTRL - Spawn a wolf (Agressive and will fight both players and infected)
* O + SHIFT - Spawn a random animal
* R - Reload the weapon and refill the ammo (Infinite ammo)
* P - Display your current position in the chat and print it to your logfiles (See logfiles section for their location)
* B - Toggle debug monitor
* INSERT - Toggle free camera. This teleports your player to the position you looked at when turning it off

# Object Editor Controls:  
* Click objects to select them.  
* Click and drag objects to move them.
* Click on nothing to deselect the current object.
* Middle Click to snap to ground (Might not be accurate)
* Spawn in new items using the object spawner menu that can be found in the toolbar.
* You can either enter values on the object editor gui or hover above the value with your mouse and use the scroll wheel to in-/decrease them.

# Teleportation
* This Version of DayZCommunityOfflineMode Namalsk Edition has had the Teleport locations updated to match all the loction found on the Namalsk Map using VPPMap Mod
* You can download the Map Mod from [HERE] (https://steamcommunity.com/sharedfiles/filedetails/?id=1623711988)
 
# Logfiles:
In case you want to report errors to us or the offical dayz dev team, you might need logfile info.
We also save the positions you printed ingame in it so that you might revisit them later on by saving them in some textfile.
Locations are stored inside the script.log for now.

You find your logfiles here: ```Press WINDOWS + R  -> Type in %localappdata%/DayZ -> Hit enter```. 

# Developers
* [Cypher](https://github.com/CypherMediaGIT)
* [Arkensor](https://github.com/Arkensor)
* [DannyDog](https://github.com/DannyDog)
* [Jacob_Mango](https://github.com/Jacob-Mango)

# Contributors:
* [Chubby The Gamer](https://github.com/ChubbyTheGamer) - Custom Objects sinking fix on reboots
* [gallexme](https://github.com/gallexme) - Suggestion for the mission based version
* [DuhOneZ](https://twitter.com/DuhOneZ) - Code snippets
* [Watchman](https://twitter.com/watchman113) - Documentation
* [n8m4re](https://github.com/n8m4re) - Code: SaveManager
* [wriley](https://github.com/wriley) - Code snippets beards
* [PR9INICHEK](https://github.com/PR9INICHEK) - Object spawner additions
