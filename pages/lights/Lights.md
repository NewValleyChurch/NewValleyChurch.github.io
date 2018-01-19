---
title: Lighting
keywords: lights
summary: "Information on the DMXIS lighting control."
sidebar: lighting_sidebar
permalink: Lights.html
folder: lights
---

# Current Lighting Situation

Go to [[Steps to Controlling the Lights]] for quick reference.

- [Here is a primer](https://newvalleychurch.slack.com/files/U75QP3JLU/F8BRWFCU8/lighting_system_layout_overview.pdf) on the DMX lighting system.

The house lights, FOH lights and Electrics make up the core of the lighting at New Valley.  There are currently twinkle stringers over the congregation that will probably come down after the holidays, and there is a fairy light string on the microphone stands that will come down after the holidays.

## Front of House Lights

Front of house stage lights are typically the lights that are in front of the stage apron (the curved part of the stage.)  

## Electrics

Electrics are lights that are over the stage.  We currently have two of them, not counting the house lights that are behind the apron.

## House Lights

There are 7 banks of house lights.  They are all track lighting with LED lights.  I do not know what type of light is actually installed in the track yet.  This is an issue we can track.

## DMX Universe

There is one DMX universe.  It consists of two cable runs that are split from the FOH.  The entire universe is controlled by the [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) controller and is split by the D-SPLIT controller.  One feed is run over Cat5 cable to the FOH and Electrics and the other is also on Cat5 cable but it runs into the office behind the sound booth.  

In DMX language, the house lights are considered a single fixture with 8 channels.  Each bank of lights is a channel.  The 8th channel is routed to the lights that are pointed to the logo in the foyer.  That is another issue to track.
