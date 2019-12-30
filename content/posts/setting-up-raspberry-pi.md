---
title: "Setting up a Raspberry Pi"
date: 2018-03-06T18:30:21-05:00
draft: true
---
![](/static/raspberry-pi.jpg)

Raspberry Pi programming is a new passion of mine and when I started the setup, I ran into a few snags. I usually read documentation and manuals before I start working on something but I realize that may not be the same for others so, I thought I’d share some gotchas so I can help the next person. I didn’t find one source of information for all of these problems so, I wanted to share what worked for me!

Raspberry Pi Basic Starter Kit

Read the Raspberry Pi Quick Start Guide and the small white instruction manual. They’ll supplement each other if you run into problems.

If your kit didn’t include a microSD card (mine didn’t), then, you’ll need to do some extra steps. The important thing to know is that if you don’t have a card, you have to get the NOOBS software on your Pi. You can’t just download the software and put it on the Pi. Download the software on your computer and read the README. The README will give you specific instructions on how to get the software on your Pi.

Format your microSD card. Follow the exact instructions on the NOOBS README! It’s going to take a while to format so go do other stuff because mine took about 4-6 hours.

After the card is formatted, drag the contents of the NOOBS software, not the unzipped folder. (This is in the README but again, don’t just drag the folder over unzipped or not, make sure it’s unzipped and drag all the contents over.

Find out the IP address of your Pi. You can use Fing (a mobile app) or ipconfig in the terminal of your Pi once you get your Pi hooked to a TV.

Connect your Pi to a TV with keyboard/mouse and connect to your WIFI. (Every time you connect to a different WIFI connection, the Pi’s IP address will change so remember this.)

If you want to connect your Pi wirelessly to your MacBook like I did, install VNC Viewer on MacBook and on the Pi follow these instructions: **[raspberry pi doc link](https://www.raspberrypi.org/documentation/remote-access/vnc/README.md)** (Skip to: Authenticating to VNC server). You’ll enter your Pi’s IP address on VNC and connect.

These are the steps that worked for me for the project I was working on. I did find a lot of blog posts saying to use different tools the Mac already has instead of VNC Viewer but none of them worked fast enough for me and after I spent a little bit of time trying to make those work, I settled for this method and didn’t run into any problems.
