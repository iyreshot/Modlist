
![](https://github.com/iyreshot/Modlist/blob/main/Logo_16x9.png)


# Version 0.0.6 ~ by iyreshot

<table stlyle="border: none;">
<tr>
<td><a href="https://www.nexusmods.com/skyrimspecialedition/mods/118277">Nexus Page</a></td>
<td><a href="https://www.wabbajack.org/">Download Wabbajack</a></td>	
<td><a href="https://loadorderlibrary.com/lists/lyra-a-fantasy-skyrim-modlist">Load Order Library</a></td>
<td><a href="https://discord.com/invite/7ePVFvV58n"><img alt="Discord" src="https://cdn.logojoy.com/wp-content/uploads/20210422095037/discord-mascot.png" width="64px" ></a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

***
*TABLE OF CONTENTS*

- [Overview](README.md#overview)
  - [Requirements and Information](README.md#requirements-and-information)
  - [Recommended System Specifications](README.md#recommended-system-specifications)
- [Installation](README.md#installation)
  - [Pre-Installation](README.md#pre-installation)
  - [Wabbajack installation](README.md#wabbajack-installation)
  - [Downloading and Installing Lyra](README.md#downloading-and-installing-lyra)
  - [Problems with Installation](README.md#problems-with-installation)
- [Post Installation](README.md#post-installation)
  - [First Start Up](README.md#first-start-up)
  - [Updating](README.md#updating)
  - [About Adding More Tools](README.md#about-adding-more-tools)
- [Some Notes on Basic System Setup](README.md#some-notes-on-basic-system-set-up)
  - [Performance Tweaks](README.md#performance-tweaks)
  - [Known Issues](README.md#known-issues)
- [Removing the Mod List](README.md#removing-the-mod-list)
- [Shout Out To Some Awesome People](README.md#shout-out-to-some-awesome-people)
- [Final Words Before I Let You Go](README.md#final-words-before-i-let-you-go)

# Overview:

> ## Lyra is a SFW Requiem modlist with a cozy and warm fantasy vibe; emphasizing exploration, challenge and fun! Built with Requiem Lite in mind. ❤️ — Powered by Wabbajack.

# Requirements and Information


- :warning: :exclamation: **"LYRA" REQUIRES THE FULL PAID UPDATE TO SKYRIM ANNIVERSARY EDITION. IT IS NOT/WILL NOT BE MADE COMPATIBLE WITH THE NON PAID UPDATE OR OLDER VERSIONS** :exclamation: :warning:


- **Lyra** only supports **English Steam** versions of Skyrim Anniversary Edition. **GOG and other Languages are not supported**. The specific version used is 1.5.97 with the creation club content from 1.6.1170.


- Only, Windows 10 and 11 work with Wabbajack fully. LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK**. Your windows version **must be 21H2 or newer** to run both Wabbajack and **Lyra**.


- Running the list from Hard Disk Drives or external drives is **STRONGLY ADVISED AGAINST**. A lot of content is swapped at game run time and, as a result, fast storage and RAM are needed.

# Recommended System Specifications
### **Lyra** requires a mid to high-tier modern system to run to its fullest potential. The recommended specs given below are based on utilizing the ENB in the list, and running the included VRAMr at Performance settings. For community shaders, you can subtract a little bit from them. Users have reported being able to run on hardware slightly lower than this, however your mileage may vary.
> ### Space required: ~300GB

| Component    | Recommended for 1080p | 
|:--------------:|:-------------:|
| CPU | Ryzen 7 5800x
| Ram | 16GB DDR4 Ram  + 40GB Pagefile 
| Storage | SATA SSD or higher
| GPU | RTX 3060 or better/equivalent (12GB VRAM)


| Component    | Recommended for 1440p | 
|:--------------:|:-------------:|
| CPU | Ryzen 9 7900x
| Ram | 32GB DDR4 Ram  + 40GB Pagefile 
| Storage | M.2 SSD
| GPU | RTX 4070ti Super or better/equivalent (16GB+ VRAM)

> See how to setup a page file here: https://www.tomshardware.com/news/how-to-manage-virtual-memory-pagefile-windows-10,36929.html :warning: **NOTE**: AMD RX 580 and older cards are **not supported**. :warning:

# Installation

## Installing **Lyra** is relatively easy and, if you have Nexus Premium, will be a simple waiting game. If you are updating the modlist, you can safely skip to the [updating section](README.md#updating).

***

# Pre-installation

> Prior to installing **Lyra**, please complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/download/dotnet/5.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Fully uninstall Skyrim by deleting the folder and the Skyrim Special edition folder inside \Documents\My Games\.
4. Fully disable OneDrive and any other programs which hook into user file areas.
5. Reinstall Skyrim into a location that is not Program files. Somewhere like `C:\Games` is a good location. If you only have one drive, look into LostDragonist's [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
6. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
7. Launch the game to the main menu and allow it to download the paid addon files. **DO NOT VERIFY YOUR GAME FILES**
8. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will** mess with the installation and, in the case of the latter, causes more problems than it solves.

***

# Wabbajack Installation

> Once you have completed pre-installation, download the [Latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

 - :warning: **NOTE**: **Lyra** will **always** require the latest version of Wabbajack **UNLESS IT IS SPECIFICALLY STATED HERE**. :warning:

***

# Downloading and Installing Lyra

Downloading and installing **Lyra** can take a while depending on your internet connection and computer. To install, complete the following steps.

1. Go to the Nexus page and download the [wabbajack file](https://www.nexusmods.com/skyrimspecialedition/mods/118277)
2. Download the file somewhere safe, then extract it.
3. Open the wabbajack client, and select "Install from Disk". Set the target modlist to the Lyra.wabbajack file.
4. Set the installation folder to be somewhere like C:\Lyra. **Do not install it to your desktop or downloads folder.**
5. The download location does not need to be on a SSD but it makes installing a bit faster.
6. Press the play button to begin.
7. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
8. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

***

# Problems with installation

> It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

## Could not download x:
> Big files or files hosted on metered connections like google drive can fail to download due to connection issues. You can either run Wabbajack again or download the file manually. If you decide to manually download it, make sure to place it in the same place as the other downloads.

# Potentially Problematic Files

- ### If the log mentions ANYTHING starting with 'cc'
	- Make sure you have downloaded all the Paid AE update content!

- ### If the log specifically mentions 'Curios'
	- You did not follow the installation instructions!
	-  Go back to [Pre-Installation](README.md#pre-installation) and follow it this time.

- ### Wabbajack could not find my game folder:
	- Either buy the game or go back to the [Pre-Installation](README.md#pre-installation) step.

- ### Antivirus reports a virus:
	- You did not follow the steps in [Pre-Installation](README.md#pre-installation). Go back and follow it.
  	- If you have followed it then you can fix this by [adding an exclusion for Mod Organizer in Windows Defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).   

# Post Installation

## Set your Affinity
-  In MO2 top left find the button that looks like puzzle pieces, and click on it.

## Find: "Set CPU Affinity"
- Click it and allow it to set the affinty for your processor.

>  *Congratulations you are now installed and ready for first start up.*

# First Start up

- Open the installation folder and double-click on the program called `ModOrganizer.exe`. 
- Make sure the dropdown box on the right is set to `Play "Lyra"` and press the `Run` button. 
- This will start the game and bring you to the character creation menu.
- After your character is created and you name them >>>

 # The MCM Menu:

- As of Version 0.0.6 the MCM is set up automatically. 
- If you wish to find any MCM menus that are hidden, click on the very first option labeled "Lyra Menu Maid" and uncheck any of the menus that you're looking for. 
- This mod is simply used to keep the MCM clean and organized.


> ❗ IT IS RECOMMENDED AT THIS TIME TO OPEN THE IN GAME MENU TO 'CONTROLS' AND CHANGE ANY KEY BINDINGS TO SUIT YOUR PERSONAL PREFERENCES Use This to find the number for the key you want to change something to >>>> [DirectX Scan Codes for ini values](https://gist.github.com/arithex/3e953d1eb096afe58ce05ba6846493e4) ❗

# Updating

> Unless noted otherwise in the change log all Updates will be Save Safe Updating should be as simple as downloading the latest .wabbajack file for 'Lyra' from Nexus, and running it with the same MO2 and Downloads install paths as your existing installation making sure to check the 'overwrite installation' box in the bottom right corner.

# About Adding More Tools:

> All the tools you choose to install in addition to these need to link in the top right executable bar in MO2 so these programs can start from within the virtual file structure of MO2.
This Wabbajack uses a file structure that contains a folder called 'Game Root' in the MO2 directory.
This is where the game will run from. It will NOT run from Skyrim Special Editions Folder so ALL links to executables NEED to point to the Stock Folder in Arguements to work correctly.
 

> Find this in MO2 executable bar under <EDIT....> then on the binary click the 3 dots and navigate to your file path for that exe to change this file paths to lead to your specific file install paths OR IT WILL NOT WORK. They are currently set for my file paths. Use those as a reference on how to set them up.
> Good tutorial on how to set these up is here >>>> [Tutorial on setting up executables in stock folder](https://github.com/LivelyDismay/Learn-To-Mod/blob/main/lessons/Setting%20up%20Stock%20Game%20for%20Skyrim%20SE.md#tool-setup)

# Some Notes On Basic System Set Up:
	
> This mod list IS graphically taxing on the hardware but systems can run it if they have the room to breathe. I'm not going to hold your hand on this, and assume you know Google-fu for anything you don't understand here.

 1. Turn off any start up programs or background programs that do not need to be on while running the game. There are guides on the web on how to go through Services.msc to trim the fat out of the Windows System Services.
 2. Strip that graphics driver down of any AA, AO, AF settings (Turn off) as those effects will be handled by the game engine or the ENB. 
 3. DO NOT DOUBLE UP ON EFFECTS!  It will kill your framerate and will not look any better than only one doing that specific effect.
 4. Run Gsync if avialable and for Heavens sake DO NOT use the in game vsync. Use driver vsync instead.
 5. Run latency at ultra and any settings you can at high performance in the driver.
 6. Run resizable bar if your hardware is capable of it. It widens the bandwidth for better file transfer speeds (i.e. smoother gameplay) Panjano has a good video on how to set this up [>>>Here<<<](https://www.youtube.com/watch?v=5DqcgHtkm9I)
 7. Go to system settings and set virtual memory on the drive the mod organizer is on at 40GB min and 40GB Max. Save and restart. This will be your swap file and supplement the VRAM if needed.
 8. Make sure your power plan is set for High performance and **NOT** balanced or power saver

# Performance Tweaks

> Here are some things I recommend if your framerate is still suffering after applying the Performance VRAMr and following the notes on 'Basic system set up' above.

 1. Run BethINI (included tool) and choose a lower preset setting like Medium. The default is High. Be sure to NOT use Ambient Occusion, Screen Space Reflections, and turn Tree LOD Distance to '0'. These effects are being handled by Reshade, ENB, and DynDOLOD. Remember DO NOT DOUBLE UP ON EFFECTS! It will cost twice the frame cost with no change in visuals! 
 2. Turn the settings on the effects in ENB to low or medium (default is high/Very high). These are in the left pane when you open ENB and can be seen when expanding each effect individually.
 3. Run at a lower resolution.  
 4. Lower the grass density in 'Explore Virtual Folder/Net Script Framework/Plugins/GrassControlConfig.txt/OverwriteMinGrassSize = 65' by INCREASING this number to something like 75-80.
 6. Go into Display Tweaks in the left pane of MO2 (search it then explore to SSEDisplayTweaks.ini) and lower this line number value:
         ResolutionScale = 0.85
  To something like .75

   > ❗  Lowering this value too much WILL make the Wheeler menu partially off screen so test any changes ❗ This will reduce the resolution but also decrease the amount of pixels the game needs to render helping frame rate. Try to find a happy medium between graphical fidelity and FPS. ❗

# Known Issues:

- None as of yet...

# With MO2 Executables not working as intended

- Find the tools folder within your MO2 installation folder, and the .exe of the application inside it's respective folder (Example: D:\Lyra\MO2\Tools\SSEedit) and Right click, then click Properties, then compatability and check "Run as administrator"

# Removing the Mod List 

- Simply delete the folder, and you have uninstalled it.

# Shout Out To Some Awesome People:

- You, for reading this 🙂
- Ivy, for being so kind and motivating me to keep modding :)
- Gears, for being amazing
- Anna and Meg, you are the best ever!
- Althro, for the wonderful ANVIL modlist that I built this from. It helped jumpstart the list and without it I may never have started this.
- Althros, for writing the license.
- Halgari, for creation of this wonderful tool
- To everyone out there who supports the streams ❤❤

***

# Final Words Before I Let You Go:

- Since I consider this an Alpha, I just want to make it clear that this list is far from polished. 
There is a lot of patching to be done, and many changes to consider still before I call this a 1.0 release.
So bare with me as this is just the beginning, I hope you enjoy the list!

> -iyre
***

















