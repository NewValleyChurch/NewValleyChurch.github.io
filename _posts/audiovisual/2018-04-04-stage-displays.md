---
title: Stage Displays
layout: post
permalink: 2018-04-04-stage-displays.html
comments: true
search: true
sidebar: main_sidebar
topnav: topnav
image_folder: images
document_folder: documents
categories: audiovisual
---

The current project under way is configuration and deployment of the Stage Display (Confidence Monitor.)  Stage Displays are designed to provide those on stage and in production a visual reference of what's going on and what's coming up. 

The current limitation has been the age of the Front of House iMac.  The USB bus on our current workstation is only 2.0, and we require at least 3.0 to ensure that we can utilize both the mini-display port for the DualHead2Go splitter _and_ a third display through a USB to HDMI connection.

Today I created a mock setup of a proposed setup to ensure that we could in fact make it work.  The test was successful.  I was able to use the computer display, the DualHead2Go, and a third display for the Stage Display data.

## Big Picture

The big picture will include a video feed that can be split and sent to multiple locations.  Having a single monitor at a distance in the back of the sanctuary will prove to be limiting in terms of the potential that the Stage Display provides.  At best, from that distance, we will only be able to see timer elements, and even then, it will be relatively small.

So, if you can imagine, from nearly every vantage point on stage, anyone presenting in a given service, including the band, pastors, and special speakers will have a visual reference with timed cues that are synchronized to ProPresenter.  Imagine a service where nobody needs to turn around and look at the screen for liturgy, or to ensure a video is being played, etc., because there are small monitors that the congregation won't be able to see, that will provide us with our cues.

## Current Limitations

Well, right now our current limitations are that we only have a single display in the back.  Another limitation is that in order to design Stage Display layouts (which can be assigned to specific slides for multiple configuration use) the dimensions of the design window will take on the display dimensions of the hardware we're using.  So, if the Stage Display aspect ratio is larger than the screen on the iMac, it will be a bit awkward.  There's no way around it other than implementing a splitter and putting a stage display reference monitor in the sound booth that matches the dimensions of the actual display device.

## Change Log

#### 11:11AM

- Installed Skitch on the iMac computer.  Skitch is a great screen clipping tool that's more robust than the native Apple OSX screen capture.  This was done to capture the default settings of ProPresenter and the video setup prior to testing a new system in order to troubleshoot the 3rd monitor (stage monitor) problem.

While using the iMac, if you press Shift-CMD-5 it will allow you to drag a box around something and capture it, then add any notations to the graphic.  Once you have a graphic you like, you can drag the PNG icon at the bottom of the Skitch window into just about anything to share it or save it.

- Disconnected DualHead2Go from the iMac and tested it alongside a 2nd monitor connected to a completely different Mac with ProPresenter.  The J5Create USB to HDMI adapter works as long as the system has a USB 3.0 bus.

## Critical Warning

DisplayLink provides USB drivers for Apple.  Apple recently released High Sierra 10.13.4 which is **NOT** compatible with the current DisplayLink drivers.  Renewed Vision released this announcement on their site and in the information pane inside of ProPresenter and it is widely known now.

As a result, upgrading to 10.13.4, the latest release of High Sierra, is a **BAD** idea as it will disable any external USB video adapters.