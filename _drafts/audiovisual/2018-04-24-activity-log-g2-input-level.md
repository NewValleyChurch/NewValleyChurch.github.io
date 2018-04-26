---
title: 'Activity Log: G2 Input Level and Ableton Live Recording'
layout: post
permalink: 2018-04-24-activity-log-g2-input-level.html
comments: true
search: true
sidebar: main_sidebar
topnav: topnav
image_folder: images
document_folder: documents
categories: audiovisual
---

## Problem

Ableton Live input levels from QU-32 USB source are recording too low, requiring post-production boosting which adds an unnecessary step and contributes to inconsistencies in mastered audio for publication.

## Actions Taken

Spent some time working with a few different settings, including the transmitter pack sensitivity, the receiver AF DB setting, the Gain on QU channel strip 25, which needs to be EQ'd after being set to a range somewhere between 26-30DB (Currently set at 16DB).  

There's a critical setup feature that needs to be in place in order to deliver the appropriate levels to Ableton Live for the sermon to avoid having to boost the recording post production.

On the QU-32, under Setup -> I/O Patch -> USB Audio, the setting for CH/ST/Grp source: needs to be Direct Outs.
Under Routing for the channel that needs to be recorded (press select on the channel strip for LPL1 25) and then press routing near the touch display, the Direct out source needs to be set to "Post Preamp" and then Direct Trim should be boosted to 10dB.  Now you'll have a good level coming in to Ableton Live.
