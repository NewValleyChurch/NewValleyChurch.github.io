---
title: About DMXIS
keywords: DMXIS
summary: "Information on the DMXIS lighting control."
sidebar: main_sidebar
permalink: About-DMXIS.html
folder: lights
categories: lighting
---

# Hardware

The [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) is a hardware interface that connects to the media computer via USB.  It allows transmission of DMX512 protocol data without the need for a dedicated lighting console.  The computer becomes the lighting console.

<p align="center">
<img src="https://github.com/NewValleyChurch/Infrastructure-docs/blob/master/images/dmxis.jpg">
</p>

(_Note: Tactical control of the lights with faders and bank selections can still be achieved with external USB MIDI controllers of which there are many available on the market._)

# Software

[DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) Software controls all of the aspects of the DMX Universe.  The [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) software can control up to 512 channels of lighting functions.  Each light has one or more channels that can be addressed.

## Standalone Mode

[DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) can be launched independently of any other DAW software.  It can then be mapped to a midi controller, or you can use the mouse to design your lighting scenes.

## Plug-in Mode

[DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) can also be dropped into a DAW, like Ableton Live.  When operating inside of a DAW, the midi mappings are unique to the DAW and are not directly connecting to the [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) software.  Inside of Ableton, we map functions on the [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) to Ableton, then we assign those functions to MIDI signals.

**Note: [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) will only operate in one of those modes at a given time.  The first instance of [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) that is opened is the one that takes control.  If you open [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) from the OSX Dock at the bottom of the screen you lose the ability to control the lights with the MIDI mapped faders on the QU-32.  

Only ONE instance of [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) can actually be used, and it's the first one that gets loaded.**
