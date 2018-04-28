---
title: Stage Display Progress Report Part 1
layout: post
permalink: 2018-04-28-stage-display-progress-report-part-1.html
comments: true
search: true
sidebar: main_sidebar
topnav: topnav
image_folder: images
document_folder: documents
categories: audiovisual
---

## Planned Configuration

In terms of video distribution to multiple displays, the front of house MediaOne iMac's configuration roadmap is as follows:

- Built in display, how can you go wrong.  It just works.
- DualHead2Go display splitter for projectors, in conjunction with two Geffen HDBaseT Lite DVI to Cat5 extenders, working just fine.  The signal leaves the iMac through a single mini-display port, enters the DualHead2Go, is split into two separate feeds and then blended between the projectors.
- j5Create USB2.0 to HDMI display adapter, operational, and works perfectly when connected directly via HDMI to another HDMI device, like another computer monitor.

That, however, is not the plan.  The plan is to feed the HDMI signal coming from the j5Create into an HDMI to Cat5e (network cable) transmitter Balun which will deliver the signal across a longer distance than traditional HDMI cables will.  On the other end, a receiver that converts back from Cat5e into HDMI and into the Vizio TV.

## Project Stumbling Blocks

- The receiver that was installed in December when the TV was hung fails to respond to power when plugged in.  I suspect it's dead.

- I replaced the Transmitter and Receiver with a new combination of TX/RX Baluns, but before hanging them in the final locations, I tested the setup at the sound booth with a 10' blue network patch cable.  The test succeeded.  I was able to fire up the Asus 24" computer display without fail at 1920X1080 resolution.

- The next step was to move the Asus monitor to the end of the actual network cable that we're using at the Vizio TV.  After connecting the monitor to the balun and firing up the system, it failed.  It also fails connected to the Vizio TV.

## Conclusion

At present, I suspect one of two things.  Either the network cable is faulty, or the connectors aren't wired up correctly, -or- the run is too long.  At this point, we still don't know if the TV works properly, but since the Asus monitor failed to respond, it's less likely that the TV is the problem.

## Further Investigation

The next step we can attempt is to lower the TV to the sound booth and connect it using the shorter RJ45 network patch cable.  If that works, then we would test it on a long patch cable.  If _that_ works, then we need to confirm the RJ45 connectors were wired up correctly on the cable that was run to the TV.

## Tools to Acquire

It will be beneficial and helpful for us to own our own cable tester, and network toner/cable probe kit.