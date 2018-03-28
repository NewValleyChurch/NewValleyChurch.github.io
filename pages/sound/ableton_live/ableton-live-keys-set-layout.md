---
title: Set Layout
keywords: recording, MIDI, sequencing, digital audio workstation, DAW
summary: "A detailed account of the New Valley Worship set (New Valley Worship.als) used for Keyboard and Live Backing Tracks during services."
image_folder: ableton
sidebar: main_sidebar
sidebar_2: ableton_sidebar
permalink: ableton-live-keys-set-layout.html
folder: sound
category: ableton
tags: [recording, MIDI, sequencing, digital audio workstation, DAW]
toc: false
---

## Intro

We use a comprehensive Ableton Live template designed with worship in mind to manage our entire song library for live performance purposes.

## History

The original version of the set that we use was designed by [Kristian Ponsford](https://www.kristianponsford.com/), worship pastor and creative director at [Sunnyhill Church in the UK](http://www.sunnyhillchurch.org.uk/).

Kristian is a certified Ableton Live trainer and is part of the [Multitracks.ocom](http://www.multitracks.com) team.

It was this template and tutorials by Kristian that finally gave me the knowledge to proceed with using Ableton Live as a primary performance and production workstation.

## What it does

Currently this template provides 4 core functions:

- Click Track for in-ear monitoring.
- Backing Tracks and custom composed track automation for certain songs.
- Automated Patch Selection for the keyboard (and other instruments if so desired)
- Automated control of OnSong chord charts on the iPad.

# Layout Details

## Group Definitions

{% include image.html file="ableton-set-groups.jpg" caption="Figure 1A: New Valley Worship Set Groups" float="right" max-width="250" %}

Tracks in this template are grouped to save space.

- **VIP MIDI:** This set of tracks is designed for live playback of individual VIP Multi Slots.  Pre-recorded MIDI clips are stored here and may or may not be used.  This is the MIDI equivalent of the Multi-Track columns.
- **MIDI Routing:**  Handles inbound MIDI signals for instruments and external MIDI controls.  
- **VSTs:** VST Tracks contain software instruments with various MIDI input sources.  No audio output is selected on these tracks.  
- **Audio Routing:[^1]** Audio routing tracks listen to the audio being produced by the VST tracks, routing them to the appropriate location.
- **In Ear:[^2]** Contain only tracks that will be routed to the in-ear system.
- **Automation:** Nearly all of the MIDI and IAC Driver automation is located in this group, with some exceptions.
- **Our Tracks:[^3]** Audio and MIDI tracks and instruments that contain original recorded and composed material.
- **MultiTrack:[^3]** A vast collection of Audio tracks for stems and backing track arrangements.
- **Originals:[^3]** Tracks that hold the original studio recording of any given song that we've captured from Spotify or YouTube, etc.

### Group Definition Footnotes

Unless specified below, grouped tracks are set with Audio To "Sends Only" which indicates that they do not provide any direct routing to any external sources.

[^1]: Audio Routing feeds the main outs on the Scarlett 18i8 through "Ext. Out 1/2" and provide the main piano performance mix for FOH.

[^2]: The In Ear group is routed to "Ext. Out 5" which is the left side of the Scarlett 18i8's _right_ hand headphone jack.  It is used exclusively to provide in-ear monitoring feeds to the ME-U Distribution Hub.

[^3]: The Audio output settings are set to "Ext. Out 3/4."  3 & 4 are the outputs on the Scarlett 18i8 that come from the left headphone jack on the front of the unit and are routed to fader strips 9 & 10 on the QU-32 to provide an independent mix for backing tracks.

## Track Details

{% include ableton-live-worship-set-tracks.html %}




{% include links.html %}
