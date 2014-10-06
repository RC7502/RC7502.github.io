---
layout: post
title: "My MAME Cabinet Project"
date: 2004-05-12 08:35
author: rcadmin
comments: true
categories: [General News]
tags: []
---
I decided to start a new topic on Bitsmack so that I could discuss my MAME Cabinet project. This way you can enjoy all my misfortunes and all my triumphs. You eat who I eat. As I mentioned before, I bought a Raiden arcade machine back in March with the intention of putting a PC inside and playing games through emulation. Raiden is in my living room now and it runs but I don't have sound for some reason and the controls are less than ideal. This project is divided into two phases. First I will get all the emulators running on my machine. Then I will take out the Raiden hardware and monitor and replace them with my PC, monitor and new controls. I hope to have pictures to put up from time to time.
<br />

<br />
The first step was wiping out my PC and starting from scratch. I'm working with a home built (aka crappy) 700 MHz Athlon with 256 MB RAM, on board audio and an ATI Radeon video card. It has two hard drives, a 6 GB and a 60 GB. Since I don't have another machine to put the 60 GB in right now I decided that my MAME cabinet would also become my file server. The mere mention of the words "file server" caused a knee-jerk reaction in Goz, "you're going to install Linux on it then?" I have messed around with Linux in the past and usually I give up after about a week. There's just something about spending an hour installing a program that takes 30 seconds to install on Windows or 10 seconds on a Mac, that doesn't really appeal to me. But now I'm getting ahead of myself.
<br />

<br />
Goz recommended I install Knoppix to the 6GB hard drive. Partitioning my drives and installing to the hard drive went really smooth. Once I had Linux up and running I played around with the desktop and window manager settings. From what I understand the primary reason to use Linux is for the pretty wallpaper and window designs. Anyway, I started searching the web for a frontend that would allow me to play multiple emulators in addition to MAME. I found one called AdvanceMenu that looked really cool. Unfortunately I could only find the source files and not the magical "mindless install" that I am used to on Windows and Mac. What happened to "Linux is ready for casual users"? Take that Slashdot's beliefs! I then decided I would just try to get MAME running and forget about the frontend for now. Since Knoppix is based on Debian I could use the very handy "apt-get" and install the xmame package. However when I tried to run xmame from the command line it said "no cards detected" and "some files are missing". I did notice my newly installed Linux machine had been quiet. Sure enough I didn't have sound for any program. 
<br />

<br />
My next step is trying to get sound to work and/or installing an old sound card. I also need to do some more research into my xmame error messages. If anyone has advice for me at any time throughout this process I'd like to hear it.
