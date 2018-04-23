---
title: ProPresenter 6 Configuration and Operations Guide
layout: page
comments: true
search: true
sidebar: main_sidebar
topnav: topnav
image_folder: images
document_folder: documents
permalink: propresenter-6-configuration-and-operations-guide.html
categories: propresenter
---

There is currently a wealth of information on Renewed Vision's Website regarding recommended practices for Pro Presenter, along with a bunch of tutorials.

Included here is an account of the way we're using ProPresenter, how it's configured, and our experiences with various attempted configurations.

## Basic Setup

New Valley only has a need for a single production workstation, so at the moment, we only hold a single license.  Anyone who is recruited to collaborate on presentations uses the trial version of ProPresenter to make edits, or uses screen sharing to remotely access the production system.

### Workstation

We just upgraded (April 2018) to a 27" iMac to solve USB 2.0 limitations for external video (Stage Display.)  Our system is a 2015 model, but it's more than sufficient for our needs.

### Projection

We use two Eiki projectors with a short throw and screen blending for a single wide screen canvas at a 3:1 ratio, approximately 28-30' wide.

### Interfaces

External hardware consists of a Matrox DualHead2Go Digital ME, a j5Create USB2.0 to HDMI adapter, and an external USB3.0 4TB Hard Drive.

### Stage Display

The Stage Display is a feature we haven't yet implemented, but will soon.  We have a single Visio display with 2 HDMI Baluns for Cat5 transmission.  Plans are to extend that signal to the stage and split it so multiple locations will have it.

## Configuration
The following represents the base configuration of ProPresenter, which is required for all of our procedures to work correctly.  From the configuration settings in OSX to the preferences in ProPresenter 6, this is how it's configured.

### Display Arrangement

In `System Preferences --> Displays --> Arrangement` you should see the following:

![](images/displayarrangement.png)

The center screen is the main iMac display.  The left screen is the Stage Display (SD) and the far right wide-screen is the DualHead2Go projection screen, which is actually 2 projectors blended into one desktop.

### Mission Control Settings

Mission control has a specific setting that must be unchecked to ensure the menu bar isn't visible on the projection screen.

In `System Preferences --> Mission Control` you'll need to make sure that `Displays have separate Spaces` is _unchecked_.

![](images/missioncontrolsettings.png)

### ProPresenter Preferences

In ProPresenter, all of the following settings can be found at `ProPresenter 6 --> Preferences...`

![](images/propresenterpreferences01.png)

#### General

Under `General`, make sure that the following settings match:

![](images/ppgeneralsettings.png)

- Library Folder: /Volumes/Blue/ProPresenter/Documents
- Support Files: _For All Users_ at /Users/Shared/Renewed Vision Application Support/ProPresenter6
- Media Repository: _Custom Path_ at /Volumes/Blue/ProPresenter
- Manage Media Automatically should be _Checked_.
* Search Paths:
    * /Volumes/Blue/ProPresenter/Video
    * /Volumes/Blue/ProPresenter/Images
    * /Volumes/Blue/ProPresenter/Audio
 
#### Display

Under `Display`:

![](images/ppdisplaysettings.png)

#### Services

![](images/ppservicessettings.png)

#### Edge Blend

![](images/ppedgeblendingsettings.png)

These settings are critical to ensuring the projectors blend properly.
 
## Resource Management

[Resource Management](brokenlink.html)

## Collaboration

[Collaboration](brokenlink.html)

## Methods
As outlined above, the resources used in ProPresenter are in the following locations, which is considered the media repository:

* /Volumes/Blue/ProPresenter/Video
* /Volumes/Blue/ProPresenter/Images
* /Volumes/Blue/ProPresenter/Audio

Since this is a shared folder on the network, other computers that have ProPresenter6 installed are able to be configured to use this location as the media repository.  Likewise, the documents and templates are also shared locations.  Documents are found in /Volumes/Blue/ProPresenter/Documents.

{% include important.html content="It's very important to note that if you are going to configure ProPresenter on another computer to point to these resources as the primary resources for that computer, that each computer's version of ProPresenter is the same." %}