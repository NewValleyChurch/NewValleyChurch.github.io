---
title:  "Activity Log: Sanctuary Display Update"
published: true
author: jon_griffith
side_bar: mydoc_sidebar
categories: media network
date: 2018-02-02 11:12:46 -0700
permalink: 2018-02-02-activity-log-media.html
tags: [media]
---

## Display Configuration

- The J5 Create Display Adapter (USB - HDMI was not working with the native driver, nor the updated driver from their website)
- Removed the J5 Adapter.
- Installed the DisplayLink USB Graphics Software for OSX and macOS version 4.1 on the Media iMac.  This is the driver found at [www.displaylink.com](http://displaylink.com/downloads/file?id=1085).  Coincidentally, it's the same source that Renewed Vision (ProPresenter) suggested I use when installing their recommended adapter, which we don't currently own.
- By default, during driver installation, the Security & Privacy settings automatically block drivers like this, but when you install these drivers, a popup asks you if you'd like to manage the blocked extension.
- While writing the previous point, the iMac flashed a blank white screen with what appeared to be burned-in images and then the Apple Logo and the loading bar appeared as though the system had been re-booted.  House lights automatically dimmed / FOH and Electrics remained on.
- 11:19 AM, currently waiting for the system to re-boot.  
- Login screen appeared again with a message: Your computer was restarted because of a problem.  That report has been sent to Apple.
- 11:22 AM, back to the main desktop.  The Security & Privacy screen sill reports Some System software was blocked from loading.
- Checked off DisplayLink Corp to enable driver extension.
- Rebooted Computer.
- 12:24 PM, computer is back online after updating OSX.
- 12:30 PM, Plugged the J5 video adapter into a USB port and it forced an instant re-boot of the iMac.
- Attempted to connect HDMI monitor to J5, no response, no additional displays in Arrangement.
- Disconnected J5 Create and threw it across the sanctuary.  (just kidding.)
- Conected the Fly Kan Multi-Display Adapter to the iMac.  Good news, it didn't crash the computer and it shows that it's receiving power from the USB Bus.
- 12:39 PM, Connected the HDMI display to the iMac and the iMac screen went completely black.
- 12:54 PM, after giving the system enough time, nothing changed.  Removed the HDMI monitor.  Screen is still black.  Removed USB Adapter.  Screen is still black.
- 12:56 PM, Forced a restart.

## System Cleanup

- Cleared out console logs to make room for new error detection.
- Updated iMac to High Sierra 10.13.3


{% include links.html %}
