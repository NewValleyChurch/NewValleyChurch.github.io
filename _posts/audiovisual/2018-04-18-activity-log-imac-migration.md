---
title: 'Activity Log: iMac Migration'
layout: post
permalink: 2018-04-18-activity-log-imac-migration.html
comments: true
search: true
sidebar: main_sidebar
topnav: topnav
image_folder: images
document_folder: documents
categories: audiovisual
toc: true
---

This is a rather comprehensive log of actions that were taken to implement the new iMac for Media.  It may melt your face off if you read all of it.  The short of it is that we now have a newer 27" iMac in place of the older 21" iMac.  It has been configured to utilize a 3rd external display which will feed the Stage Display signal to wherever we please.

The downloads folder is automatically purged every 24 hours, so if you download something, know that it needs to have a home or it will need to be downloaded again.

The following page was added to the site:  [Matrox DualHead2Go Video Display Adapter](DualH2GDME.html) along with the [configuration instructions](matrox-dual-head-2-go-configuration-guide.html).

### ProPresenter Media

Images, Videos, and Audio files that are utilized in ProPresenter are automatically stored in the media repository as configured in ProPresenter.  This means that when you drag a resource to the image/background bin, it is _copied_ to the media repository.

**Note:** If the file you are dragging into ProPresenter _is a duplicate of the original artwork_ make sure you delete the duplicate.

We will be developing a catalog standard and naming convention as well as a network repository independent of ProPresenter to store NVC digital media files so they're available to us regardless of whether or not they'll be used in ProPresenter or some other publication(s).  That is a work in planning, currently.

### The following events occurred regarding the implementation of the new iMac:

- Unboxed and fired up the new iMac.
- OS Version is currently 10.12.4.
- Created user `Administrator`.
- Connected user `Administrator` to iCloud account `media@newvalleychurch.org`.
- Keychain and File Storage on iCloud is disabled for `Administrator`.  Siri is disabled as well.
- Created user `MediaOne`.
- Created group `Users.`
- Added user `MediaOne` to group `users`.
- Named computer `MediaOne` in NetBIOS settings and Sharing.
- Disabled system sounds.
- Enabled Volume control in menu bar.
- Installed Google Chrome and made it the default browser.
- Created cron job to automatically empty downloads folder daily at midnight.
- Updated to OSX Sierra version 10.12.6

High Sierra 10.13.3 isn't available for install without jumping straight into 10.13.4 which we don't want to do.

- Increased mouse tracking to maximum speed (most efficient.)
- Enabled right click and double-tap to zoom.
- Created Software Library to contain driver and app installations in the root of the hard drive.
- Cleaned up the media@newvalleychurch.org e-mail account.
- Signed into chrome using media@newvalleuchurch.org.
- Installed Matrox Powerdesk
- Installed DisplayLink USB Video Driver
- Disabled Notification sounds.
- Added Toshiba eStudio to the list of available printers.
- Enabled Screen Sharing.
- Enabled Remote Management and Remote Login
- Set screen to 30 minute power off.
- Disabled screen saver.
- Installed Alfred 3.
- Installed j5Create USB to HDMI Video adapter and driver, configured 3rd (4th) display.
- Installed A&H TCP Midi Driver for QU-32 Sound Board
- Installed A&H DAW Control for QU-32
- Installed ProPresenter 6
- Deactivated Edge Blend and Multi-Screen on old iMac, enabled on new.
- Installed Ableton Live 10
- Authorized and enabled Ableton Live 10
- Installed Skitch screen capture tool.
- Installed DMXIS Light Control Software
- Installed and connected to Spotify.
- Installed Slack.
- Created slack account for `media@newvalleychurch.org` with the display name of `MediaFOH` (front of house.)
- Disabled WIFI
- Assigned Static IP to Ethernet Connection
- Added user `MediaOne` to authorized remote screen sharing users.
- Tested screen sharing on local network, success.
- Disabled "Displays have separate spaces" in Mission Control settings.

- Restored images, documents, and templates to new iMac.
- Started playlist for this coming Sunday
- Reconfigured bare-bones lighting to get it going.

## [Matrox Powerdesk Setup](matrox-dual-head-2-go-configuration-guide.html#matrox-powerdesk-setup)

## [DisplayLink USB Video Driver Setup](displaylink-USB-video-driver-setup.html)

** Notes:** The keyboard and mouse are both wireless devices that require charging via the USB cable that is attached tot he keyboard.  They both need to be charged regularly.