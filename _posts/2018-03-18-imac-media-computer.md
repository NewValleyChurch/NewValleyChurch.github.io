---
layout: post
comments: true
search: true
sidebar: main_sidebar
topnav: topnav
image_folder: images
document_folder: documents
title: iMac Media Computer
permalink: 2018-03-18-imac-media-computer.html
---

Updates that were made today are critical updates.  The settings herein are critical to ensuring the system is up and accessible at all times.  The following will help accomplish these goals:

- Provide remote desktop access to the iMac through the native Screen Sharing (VNC) server that is already included with the Operating System from anywhere in the world.
- Screen Sharing allows the remote user to view ALL screens that the iMac is generating.
- Ensure the network settings of the workstation are static.

#### 1:15 PM

- Updated the iMac Media Computer network settings.

Details:  The media computer in the sound booth is connected directly to the network router via Ethernet cable.  It _does not need to have WIFI connected nor enabled_.  Having two network adapters may provide redundancy when used on the same network, but may also cause services to be confused between which adapter to use.

- Disabled WIFI on iMac
- De-activated WIFI adapter on iMac.
- Set static IP address, Gateway, and Subnet for Ethernet Adapter.
- Assigned Static IP to network router.

This might be the reason we have had so much trouble with GoToMyPC.  

#### 1:24 PM

- Enabled Screen Sharing
- Enabled Remote SSH
- Tested screen sharing connection from MacBook Air (my laptop) internally on the network.  I was able to connect to and remotely control the computer.
- Username and password to access the computer remotely isn't optimal.  It's the name of the user on the computer and the login password for that account.  Considering changing the user name to something more manageable, and thus, considering isolating the Administrative account from a standard user account to prevent undesired or accidental system changes.

#### 1:27 PM

- Configured port forwarding for iMac in network router to enable outside access to the VNC server.
