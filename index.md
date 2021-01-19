---
title: Retro Gaming System | Linux
description: A Retro Gaming System that I configured using Retropie in Ubuntu 20.04.01 LTS.
image: ProjectScreenshots/RetroGamingSystem.png
youtubeId: dctKhohG0cQ                                      
---

<link rel="stylesheet" type="text/css" href="video-embed.css">

![NES Header Pic](ProjectScreenshots/NES Screen.jpg)<br>

# Intro
I've always had a love for old school video games. The most cherished gaming memories I had as a child were from playing Galaga and Pac Man on my uncle's arcade cocktail cabinet. I was able to recapture this nostalgia using RetroPie on my Raspberry Pi 3 where I loaded my favorite games on it. The Raspberry Pi is a very capable SOC given its size, but it does have its limitations when it comes to emulating more recent systems like PlayStation, PSP, and GameCube. 

An old office PC would provide sufficient computing power to run games on those more demanding systems. Luckily, I was able to pick up a cheap Lenovo ThinkCentre PC from a local listing and got to work configuring RetroPie on it. Although I have had experience setting up RetroPie on a Raspberry Pi, this is my first time installing it on an x86-based system. This project post details my experience working with a Linux-based PC and navigating through the setup using the terminal.

# PC Specs
𝗖𝗣𝗨:  Intel Core i5-2400 <br>
𝗥𝗔𝗠: 4 GB (1 x 4 GB)<br>
𝗛𝗗𝗗: 640 GB Western Digital Hard Drive Disk<br>
𝗢𝗦: Ubuntu 20.04.01 LTS<br><br>

#### Picture of the PC specs viewed in the Computer Summary
![Picture of PC Specs](ProjectScreenshots/PC Specs.jpg)<br>
#### The PC I used was a Lenovo ThinkCentre M81.
![Picture  of PC front](ProjectScreenshots/PC Front.jpg)<br>

#### I used a SNES style controller and a keyboard to configure the inputs for most of the systems. 
![Picture  of PC front with controller](ProjectScreenshots/PC and Controller.jpg)<br>

#### There was no HDMI output so I had to use a Displayport to HDMI adapter to connect it to my TV.
![Picture of PC Back](ProjectScreenshots/PC Back.jpg)<br>

#### There was no included storage when I picked up the PC, so I added a 640 GB Western Digital HDD as the boot drive and storage drive.
![Picture of PC inside](ProjectScreenshots/PC inside.jpg)<br>


# Live Demo
Click on the YouTube video to see a live demo of the Retro Gaming System!

{% include youtube.html id='dctKhohG0cQ' %}

# Future Improvements

* Use SFTP (SSH File Transfer Protocol) to transfer ROMs and other files over the network instead of manually copying files from a USB stick
* Custom splash screen that greets the user when the unit boots up
* Test out more experimental packages such as PSCX2 (PlayStation 2 emulator)

