---
title: iMac Media Computer
layout: post
permalink: 2018-03-18-imac-media-computer.html
comments: true
search: true
sidebar: main_sidebar
topnav: topnav
image_folder: images
document_folder: documents
categories: audiovisual
---

**Updates were made today (Sunday March 18th) that impact the core functionality of the current workstation in FOH.**

These changes strengthened the system integrity and enhanced our method of remote access. 

The settings herein are critical to ensuring the system is up and accessible at all times.  The following will help accomplish these goals:

- Provide remote desktop access to the iMac through the native Screen Sharing (VNC) server that is already included with the Operating System from anywhere in the world.  GoToMyPC is no longer _required_ to access the computer remotely.

- Ensure the network settings of the workstation are static, providing connection stability.

#### 1:15 PM

- Updated the iMac Media Computer network settings.

Details:  The media computer in the sound booth is connected directly to the network router via Ethernet cable.  It _does not need to have WIFI connected nor enabled_.  Having two network adapters may provide redundancy when used on the same network, but may also cause services to be confused between which adapter to use.

- Disabled WIFI on iMac
- De-activated WIFI adapter on iMac.
- Set static IP address, Gateway, and Subnet for Ethernet Adapter (cable connection)
- Assigned Static IP to network router to ensure only this device has the IP and no IP conflicts occur.

**Having two network adapters fighting for attention may have been why GTMPC was failing intermittently.**

#### 1:24 PM

- Enabled Screen Sharing
- Enabled Remote SSH for command line maintenance and administration.
- Tested screen sharing connection from MacBook Air (my laptop) internally on the network.  I was able to connect to and remotely control the computer.

- The username and password to access the computer remotely isn't optimal.  It is currently the name of the user on the computer and the login password for that account.

- Future iterations of the network infrastructure might include a directory server for network-wide logins with individual user accounts for each person who needs to access the workstation.  This type of setup affords us flexibility and versatility, but also comes with trade-offs that would need careful planning.

#### 1:27 PM

- Configured port forwarding for iMac in network router to enable outside access to the VNC server.

#### 3:00 PM

- Tested remote access to VNC from outside of the network.  Passed.