---
layout: post
title: "Macbook + XP = Great imaging fun!"
date: 2006-05-02 15:31
author: rcadmin
comments: true
categories: [General News]
tags: []
---
Problem:
Getting a Mactel to load XP via an image and not have to install XP, install drivers, install software everytime.

Tools needed:
A Mactel with 10.4.6 loaded, the firmware updated and Boot camp installed
Symantec Ghost (to send the image from the XPMac to the ghost server to the new mac)
A Mactel with XP already installed (to make the image)
A ghost server machine (or something that can run ghost server)
reatogo (For building the bootable XP PE disc with Ghost support)
A Windows XP disc
Solution:
1) Install Ghost server on the XP mactel
2) Install reatogo on the XP Mactel
3) Run reatogo and use the autodriver application to create the network drivers for your mactel (NOTE: If the mactel has a different network driver on it than the destination mactel you will need its network drivers for this process to work).
4) From the reatogo menu, click the "Plugin" button on the "Open Folders" side of the application
5) From there run "autoHelp-Creator.exe" and click the "Plugin Creator" button
6) Press Enter, select the path C:\Program-Files\Symantec\Ghost and click "ok"
7) Select "Ghost32.exe" when it asks you what files you'll need to run.
8) After that is finished, return to the reatogo menu.
9) You are now ready to click "Start PEbuilder" and make your .iso to image your mactel.
10) after you have created and burned your reatogo image you are ready to image your MacXP install.
11) Load your MacXP machine using the reatogo cd you just burned.
12) Setup your ghostcast server to create the image
13) Once your MacXP machine is ready to start dumping its image run Ghost from the reatogo cd as you would any normal Windows machine <strong><em>BUT remember to select to image as a partition!!!</em></strong>
Cloning to the other mac
14) After you are done, startup your 10.4.6 Mactel you want to dump that image onto into the Mac OS.
15) After you have installed the firmware update and bootcamp, run the bootcamp assistant.
16) Partition the drive however you'd like, insert your XP cd and click "Start Installation"
17) Once the installer starts, Select that you would like to quick format the C: drive (using NTFS or FAT32 it doesn't matter at this point)
18) Once the drive is formatted you are done at this point and can shut the mac off.  You do not need to wait for it to install the files into \windows because this steps just tells MacOS that we've installed windows onto this partition and the mac then lets the partition boot.
19) Turn on the computer holding down the "Option" key and eject the XP cd in the drive.
20) Insert the reatogo CD from before and boot to that.
21) Setup your ghostcast server to broadcast the image we created earlier and <strong><em>REMEMBER to select the partition option (so it doesn't reformat the entire drive)</em></strong>.
22) After the drive gets done imaging you can reboot the mac and it will now have an active Windows partition!!!!

This was all tested using 2 Macbook Pro laptops running at 1.83Ghz with 1GB of RAM.

<a href="http://digg.com/apple/Imaging_the_Mactels">Digg this article!</a>
