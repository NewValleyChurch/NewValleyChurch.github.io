---
title: Remote Access
layout: post
permalink: 2018-03-26-remote-access.html
comments: true
search: true
sidebar: main_sidebar
topnav: topnav
image_folder: images
document_folder: documents
categories: audiovisual
---

On March 19th, 2018, GoToMyPC, which was a significant monthly cost, was discontinued in favor of the already available screen sharing application that is native to OSX.

### How to Connect

#### On a MAC:

Open a new finder window.  In the menu bar at the top, click the GO menu then "Connect to Server" or simply press CMD-K in a new finder window.

In the server address, type **vnc://xxx.xxx.xxx.xxx** where the XXX's are replaced with our static, public facing internet IP address.  In order to prevent unwanted attempts at network intrusion, I won't publish the external IP address here.  You should have access to it through alternate channels, of which you may have already been notified.

You will be prompted for a user-name and password.  This is the user-name and password of the user account on the machine itself.

When you connect for the first time, you may see all of the connected screens.  This is an option that you can change once you're connected and it's a client-side setting, meaning it won't change how other people see it.

#### On a PC:

You'll need to install one of many available VNC Viewers.  Here is a link to one of them:

https://www.realvnc.com/en/connect/download/viewer/

Download and install and use this tool to connect using a similar method to the described method above.


#### Connecting to Other Machines

More than one Mac can be accessed from outside of the network when configured to do so.  Let me know if having your workstation accessible remotely would be beneficial and I can help you connect to it.

### Technical Side

Each machine on the network has a network address (IP Address.)  On computers that need to be permanently accessible, those numbers are static, meaning they never change.  Our internet connection also has an address.  

The tool we use to connect to OSX on a Mac is called Screen Sharing.  In order for screen sharing to be enabled, the sharing feature in system utilities needs to be explicitly instructed to allow it.

Connections to the computer are received on the computer's IP address on a specific port number.  So, for example, if the computer's address is 192.168.0.20, then Screen Sharing is listening to 192.168.0.20:5900.

The network router (wifi router) handles the task of forwarding outside access through the router to the correct computer (as multiple computers can be setup to be controlled remotely.)  This is done through port forwarding.

### Tunneling over SSH

Working on a plan to allow access through an SSH encrtypted tunnel instead of exposing port 5900 to the world.