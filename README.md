![](https://github.com/iyresh0t/Modlist/blob/main/splash.png)

# "Lyra" - A Fantasy Skyrim Modlist
by iyreshot

## v. 0.5.0



- [Overview](README.md#overview)
  - [Requirements/Information](README.md#requirements-and-information)
  - [Recommended Hardware](README.md#recommended-minimum-hardware)
- [Installation](README.md#installation)
  - [Pre-Install](README.md#pre-install)
  - [Main Install](README.md#main-install)
- [Post Installation](README.md#post-installation)
  - [Exclude Mod Organizer from your Anti-Virus](README.md#1-exclude-mo2-from-your-anti-virus)
  - [Disable Steam Overlay](README.md#2-disable-steam-overlay)
  - [Set Your Affinity](README.md#5-set-your-affinity)
  - [AMD Specific Requirements *IMPORTANT*](README.md#6-amd-specific-requirements)
- [Included Tools](README.md#included-tools)
  - [About Adding More Tools](README.md#about-adding-more-tools)
- [Some Notes on Basic System Setup](README.md#some-notes-on-basic-system-set-up)
  - [Performance Tweaks](README.md#performance-tweaks)
  - [The MCM Menu](README.md#the-mcm-menu)
  - [Known Issues](README.md#known-issues)
- [Some Important Default Keys to Know](README.md#some-important-default-keys-to-know)
  - [Word of Warning](README.md#word-of-warning)
- [Recommended Difficulty Levels](README.md#recommended-difficulty-levels)
  - [Shout Out To Some Awesome People](README.md#shout-out-to-some-awesome-people)
  - [Final Words Before I Let You Go](README.md#final-words-before-i-let-you-go)

   
 # Overview:
 

Lyra is my personal Skyrim modlist, something that will continue to develop with time. 

I wanted to build a list that is fun to explore, visually beautiful, 
and doesn't destroy my PC...although this list is still pretty heavy, my main focus is performance.
Currently I will focus on the land of Skyrim and it's DLCs, 
making everything feel more immersive and fun to experience again. 
So if you want to experience what this list has to offer, 
and are excited for what's to come, 
I invite you to try Lyra.


 # Requirements and Information:

 
### This modlist requires the Steam version of Skyrim AE v. 1.6.1170

### All Anniversary Edition Creation Club Content

### The Skyrim Special Edition Creation Kit

It will auto Downgrade and run Skyrim SE 1.5.97 with CC content.

It is released with Open Permissions per the Wabbajack License Agreement 

[Wabbajack License](https://github.com/wabbajack-tools/wabbajack/blob/main/LICENSE.txt)

Support will be provided for non-modified installations of the mod list via the Discord server

[Discord Invite Link](https://discord.gg/kHehbzuFZ4)

## *We will only offer support for legally purchased copies of the game from Steam installed following this installation guide on hardware that meets or exceeds the minimum requirements*



 # Recommended Hardware:
  
Absolute minimum if using every provided option for optimization, and run VRAMr at 'performance' settings is:

Video card with 12GB of VRAM

Processor of 3Gz or better and minumum 4 cores

16GB system ram

Sata SSD with minimum 500 GB of free space and 40GB virtual memory 

   NOTE: The minimum specs will certainly struggle to maintain 30-50fps


# Installation:
  ## Pre-install:
1. Install a fresh copy of Skyrim AE from Steam version 1.6.1170
2. Install the Creation Kit from Steam for Skyrim AE
3. Launch the game once from Steam and at the prompt download all CC Content from the full version of AE.
4. Start new game and after hearing  "So you're finally awake" open console (~) and type QQQ then press enter to quit out.

  ## >Important Note<:
**You will need a Vector Plexis account for High Poly Head download in the Wabbajack**


  ## Main Install:

Make sure you are on the latest version of Wabbajack. As of this readme writing it's 3.5.0.1

[Wabbajack Version 3.5.0.1](https://github.com/wabbajack-tools/wabbajack/releases/tag/3.5.0.1)


1. Download the Wabbajack file from Nexus, extract the file and locate it within the Wabbajack installer
2. When download is complete click the play arrow in the same location.
3. Choose your install location, and Download location in the Wabbajack window.
  ### **Make sure the install location is minimum 500GB and OUTSIDE of any program or system files**

  ### NOTE: **There will be one file that requires you choose and click the download on Vector Plexus window. The file you want is High Poly Head v1.4 SE**

After that file is downloaded the rest of the install should be automated.


 # Post Installation:

   ### MO2 and System Settings
   
   ## 1. Exclude MO2 from your Anti-Virus
   
   For Windows Defender click Windows tab in bottom left
   
   Type 'Virus' and select 'virus and threat protection'/ 'Manage settings'/ 'Exclusions'/ 'Add or remove exclusions'
   
   Add an Exclusion and navigate to your Mod Organizer 2. exe

   ## 2. Disable Steam Overlay
   
   Find the game in your Steam Library then go to Properties
   
   Under the General tab, you'll find a checkbox for Enable the Steam Overlay while in-game.
   
   Make sure it's unchecked.


  ### *Don't forget to change your resolution in Bethini to match your screen resolution. You may also wish to enable TAA at this time if using an AMD card (nVidia cards will use the Upscaler DLAA included in the list) or change preset*

  ## 5. Set your affinity

In MO2 top left find the tools tab, and click on it.

Find: 
### *Set CPU Affinity* 

Click it and allow it to set the affinty for your processor.

## 6. AMD Specific Requirements 

In MO2 left pane find line #4 Optimization, and expand

Uncheck DLAA as it's set up for DLAA which won't work on AMD cards (will cause crash)


## Congratulations you are now installed and set up.


 # Included Tools:

Bethini Pie

SSEedit and QuickAutoClean

LOOT

Cathedral Assets Optimizer

Nemesis

Bodyslide and Outfit Studio

NifSkope

ReSaver

VRAMr


 # About Adding More Tools:


All the tools you choose to install in addition to these need to link in the top right executable bar in MO2 so these programs can start from within the virtual file structure of MO2.
This Wabbajack uses a file structure that contains a folder called 'Stock Folder' in the MO2 directory.
This is where the game will run from. It will NOT run from Skyrim Special Editions Folder so ALL links to executables NEED to point to the Stock Folder in Arguements to work correctly.
 

Find this in MO2 executable bar under <EDIT....> then on the binary click the 3 dots and navigate to your file path for that exe to change this file paths to lead to your specific file install paths OR IT WILL NOT WORK. They are currently set for my file paths. Use those as a reference on how to set them up.
Good tutorial on how to set these up is here >>>>
[Tutorial on setting up executables in stock folder](https://github.com/LivelyDismay/Learn-To-Mod/blob/main/lessons/Setting%20up%20Stock%20Game%20for%20Skyrim%20SE.md#tool-setup)



  # Some Notes On Basic System Set Up:
	
This mod list IS graphically taxing on the hardware but systems can run it if they have the room to breathe.
I'm not going to hold your hand on this, and assume you know Google-fu for anything you don't understand here.

1. Turn off any start up programs or background programs that do not need to be on while running the game.   
[Blackviper.com](https://www.blackviper.com/) is a wonderful resource on trimming the fat out of the Windows System Services.

2. strip that graphics driver down of any AA, AO, AF settings (Turn off) as those effects will be handled by the game engine or the ENB. 
DO NOT DOUBLE UP ON EFFECTS!  It will kill your framerate and will not look any better than only one doing that specific effect.
Run Gsync if avialable and for Heavens sake DO NOT use the in game vsync. Use driver vsync instead.
Run latency at ultra and any settings you can at high performance in the driver.

3. Run resizable bar if your hardware is capable of it. It widens the bandwidth for better file transfer speeds (i.e. smoother gameplay)
Panjano has a good video on how to set this up
 [>>>Here<<<](https://www.youtube.com/watch?v=5DqcgHtkm9I)


4. Go to system settings and set virtual memory on the drive the mod organizer is on at 40GB min and 40GB Max. Save and restart.
This will be your swap file and supplement the VRAM if needed.


# Performance Tweaks

   Here are some things I recommend if your framerate is still suffering after applying the 12GB VRAMr and following the notes on 'Basic system set up' above.

  1. Run BethINI (included tool) and choose a lower preset setting like Medium. The default is High. Be sure to NOT use Ambient Occusion, Screen Space Reflections, and turn Tree LOD Distance to '0'. These effects are being handled by Reshade, ENB, and DynDOLOD. Remember DO NOT DOUBLE UP ON EFFECTS! It will cost twice the frame cost with no change in visuals!
   
  2. Turn the settings on the effects in ENB to low or medium (default is high/Very high). These are in the left pane when you open ENB and can be seen when expanding each effect individually.
   
  3. Run at a lower resolution.
   
  4. Lower the grass density in 'Explore Virtual Folder/Net Script Framework/Plugins/GrassControlConfig.txt/OverwriteMinGrassSize = 65' by INCREASING this number to something like 75-80.

  5. Consider frame generation software.

     ## *NOTE*
     ### This is software I chose to purchase from Steam for my own game. Decide for yourself what is right for you.

   [Lossless Scaling Frame Generator](https://store.steampowered.com/app/993090/Lossless_Scaling/)

   
 # The MCM Menu:

MCM Recorder should Auto Run on new game start with recommended settings.

You can still go through the menu and change things to suit your preference afterward but this will give you a solid base to start from.

### Some important things to leave disabled for stability reasons

Leave Minatours and Spiders Off in OBIS

Leave Extra spawns Ore Guardians Off in Immersive Creatures

Leave shadows OFF in Strange Runes

  # Known Issues:

## With MO2 Executables not working as intended

Find the tools folder within your MO2 installation folder, and the .exe of the application inside it's respective folder (Example: D:\The Nico Experience\MO2\Tools\SSEedit)

Right click/ compatability/ Run as administrator

## Within the game

Sometimes when jumping you might get stuck in the jump animation. Jump again to fix

Sometimes the Bow rapid combo attack won't work correctly. Switch weapons then switch back to fix

# *Some Important Default Keys To Know*:

Caps Lock + Enter = ENB Menu

Caps Lock + F12 = Toggle ENB Effect

Caps Lock + F11 = Toggle Wire Frame

F11 = Toggle A matter of time widget and clock

Backspace = Immersive Equipment Displays

Shift + O = Open Animation Replacer

Shift = Toggle use or take, and talk or pet for cats, dogs, and horses

Ins = Blink Spell Hotkey (Can be modified in it's ini file)


Dodges= Direction + Left Shift (can be changed in ini file for TK Dodge RE)

G = Ultimate Immersion Toggle

Q = Wheeler menu

Alt (Hold) = Sprint

Home = dMenu


While falling

Paraglider pull or put away = activate key

# *Word Of Warning*:

Some creatures will be deleveled so you might come across a level 30 ogre at level 1 and have to run to survive. Ye have been warned!
You will learn....stick and move, stick and dodge, run and heal or just plain run away to survive at lower levels.

# Recommended Difficulty Levels (if running solo):

Level 0-9 Apprentice

Level 10-15 Adept

Level 16-20 Expert

Level 21-30 Master

Level 31 and up Legendry (if you have the stones for it)

The game also has survival built in using Sunhelm but can toggle this on or off along with Cold survival in the MCM.

Some quality of life / fun mods are also included.

Paraglider, magical jumping, bow rapid combo v3, mist flight, and others you can have fun discovering and exploring.

There are added worldspaces to explore as well.

Wyrmstooth and Beyond Reach will start at a certain level but some you will just find in your exploring like Chanterelle, The Shire, Moonpath to Elswyer, Darkend, Skyrim Sewers, and Skyrim Underground.

 
# Shout Out To Some Awesome People:

Halgari for creation of this wonderful tool

-For play testing and feedback>>

Nicoroshi - Without you, none of this would be happening. I cannot thank you enough. I have never felt so driven to do something before and you sparked that in me. :)

Gears - Thank you for everything you do, you're the GOAT! 

BiggieBoss - You're the boss for a reason! Everything you do inspires me, and I really look up to what you do.

-Race Menu Presets>>

Wren - You are such a kind hearted person, and I am more than happy to include your presets in this list! Thank you for everything.

Islam - I hope it's ok to call you that! Thank you for the amazing presets, truly a work of art. :)

# Final Words Before I Let You Go:

I designed this mod list to be tougher than anything vanilla with FAR more creatures that are tougher than stock ones.
As such I have included a mod called skyrim skill uncapper. It has an ini file you can tweak to your liking increasing (or decreasing) the amount of perk points per level as well as amount things like health, magica, and stamina go up per level. 
CC Survival mode will conflict with SunHelm survivial. I recommend using ONLY Sunhelm as it covers cold, eat, drink, and sleep needs.

It you are still reading to this point, please note that this list is still very much in Alpha state, and I intend to work tirelessly to make it the best experience I can and remain consistent with my vision. I appreciate you for taking the time to read this far...So for now, I will leave it here, and I can't wait to see where this goes. 
Enjoy <3

-iyreshot
