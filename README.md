This is only a fork off of Xb2Input. Last upload was Feb 1 2022. No progress has been made at this time.   TBD if this fork will go further.

 
Xbox OG kit provides an easy solution to configure your Xbox Original Controller from 2001 on Windows 10+!


Checkout the release of Xbox OG Kit for Windows!


Release: Xbox OG Kit v1.5c
https://github.com/JustTrev/Xb2XInput/releases/tag/Xb2Input


Credits:
https://github.com/emoose/Xb2XInput
https://github.com/ViGEm/ViGEmBus/releases

​
Hey everyone,

 

Just thought I'd share an application that hasn't seen much traction other than hard google searching lol; Xb2Input.  
 

I've never quite shared anything that I've written in the past before, which has me quite nervous/scared about it, and I've wanted to tip my hat into the community ring for a while.. I am very much a n00b when it comes to programming, please don't take this the wrong way as I've spent serval days working on a small C# project for the Xb2Input program (that was lovely written by emoose on Github).

 

The reason behind my app is that I absolutely loved Xb2Input so much that I had to write something that would quickly work for me, improving Xb2Input's quality of life in a more formal way, since I have it setup on more than one of my PCs..

 

So here is what I came up with; The Xbox OG Kit
https://github.com/JustTrev/Xb2XInput/releases/tag/Xb2Input

 

The Xbox OG Kit, is a frontend API that enables you to adjust any old Xbox Controller without the hassle of closing Xb2Input in order to make changes to it's ".ini" file, then relaunch Xb2Input to see the changes take affect.  

 

The "XboxOG Kit Installer" will unpack and setup Xbox OG Kit, ViGEmBus and Xb2Input with all of its components.  Without these, Xb2Input would be rendered useless, and my project a total waste of time.

 

Current Release Notes:

Spoiler
Notes:
• The installer will create a new registry key item for installation for future support to Xbox OG Kit and potentially the Xb2Input project (TBD). 

• The setup will install all the necessary files and run them without much human intervention.

• The Installer places shortcuts in the Start Menu after installing, so finding the Xbox OG Kit should be easy. 

• You can launch Xb2Input from the Settings dropdown menu within the Xbox OG Kit.

• Saving controller layout and clicking Apply, will close and restart Xb2Input if it is not already running.

• You can edit the guide button mappings in order to use the guide menu. 

• You can enable or disable the controller vibration.

• The Triggers and Stick Dead Zones can be fully adjusted.

• Xbox Memory Units are detected in Windows and can be used as stroage. (USB 1.0 Devices)

• See different button icons if games were designed with either the Xbox 360 or Xbox One controllers in mind. (wish all game devs added all the button icons and detected any controller precisely, including analog controllers somehow).

To-Do:
• Fix installer to restart PC when checkbox is checked at the final stage of installation. (This is supposed to be working but it isn't. Manual restarts will be necessary after the installer has finished.)

• Swap buttons with Remap Controller enabled.

• Run analog Driver Installer batch script in background to update the installer progressbar.
• Open Xb2Input when launching Xbox OG Kit, if it is not already running. (This does not work in the beta release)

• Add Windows startup support. (This works natively within Xb2Input at this time).   

• Detect controller and button presses from within Xbox OG Kit.
• Look into installing ViGEmBus silently or without human intervention completely.
• Update the background controller image to show the right connected controller, based on it's serial number. (such as racing wheel, or madcatz wireless controllers, etc.)
• Remove the guide button checkboxes and info key when "Enable Guide?" is disabled. (unchecked)
• Detect the Xbox Communicator and it's serial number for full headset support and Xbox Original style voice changer. (might need to make a sound device driver for this to happen much like the controllers).
• Add an Uninstaller for Xbox OG Kit to remove all of it's contents.


Known Bugs:
• Other controller accessories such as the headset communicator, might cause Xb2Input from being able to detect your controller. (Work around - Disconnect controller and remove accessories before reconnecting your controller into your PC. Let Xb2Input detect your controller first before plugging in any accessory into the controller.)
• Windows 11 wont start the toolbar services (i.e No clock, speakers or anything) if a controller is plugged in upon after a reboot after logging in. Current work around is reboot and disconnect your controller until after login. (This issue is Not present in Windows 10 at this time .) 


 

This is my Xbox OG Kit in a nutshell. I hope this helps anyone who would prefer a more user friendly experience when attempting to play with any old Xbox Original(OG) Controller on PC.

 

I would love to hear feedback about the the tool and if there are any bugs you may find to please report them here or with special features you would like to see added to the Xbox OG Kit.

 

To those who would like to enhance this project further, please contact me directly as I am very careful about my work.

 

I would like to give an honorable mention to emoose on GitHub for making this a reality in the first place and I hope to see a new update come out of Xb2Input soon!!  

 

I am so thankful I am able to use my ultimate favorite controller of all time again!!!!! 

 

Xbox OG Kit: (Beta)

Download Zip: Xbox OG Kit Installer v1.0c

Source: https://github.com/JustTrev/Xb2XInput/releases/tag/Xb2Input

About - A frontend user interface for Xb2Input with included requirements.

 

Current Supported Platform: Windows 10+


Image Snapshots:

Spoiler














 

Xbox OG Kit Installer includes:

• XboxOG Kit v1.0 (Beta)

• Xb2Inputv1.5c with driver packages

• ViGEmBus Setup 1.21.442

 

 

Xb2Input Source:
https://github.com/emoose/Xb2XInput

About - XB2X: User-mode Windows driver for Xbox OG controllers, supporting both XInput and DirectInput.

 

ViGEmBus Source:

https://github.com/ViGEm/ViGEmBus/releases/tag/v1.21.442.0

About - Windows kernel-mode driver emulating well-known USB game controllers.

 

 


​
License
---
"install/uninstall driver.bat" is taken from [ProconXInput](https://github.com/MTCKC/ProconXInput/) which is MIT (Expat) licensed.

ViGEmClient code taken from [ViGEmClient](https://github.com/ViGEm/ViGEmClient), licensed under MIT license.

wdi-simple taken from [libwdi project](https://github.com/pbatard/libwdi) which is LGPL 3 licensed.

The rest of the code is licensed under GPLv3.
