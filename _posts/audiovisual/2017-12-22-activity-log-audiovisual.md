---
title:  "Activity Log: Stage Reconfiguration and Audio Routing"
published: true
side_bar: main_sidebar
categories: audiovisual
author: jon_griffith
date: 2017-12-22 14:03:35 -0700
permalink: 2017-12-22-activity-log-audiovisual.html
tags: [stage, sound, lights, qu-32, slack, dSnake]
---

- Cleaned up the entire stage.  Re-routed most cabling to dSnake ports that were closer to the source.  Created a new scene on the QU-32 called [Re-Routed](https://github.com/NewValleyChurch/Infrastructure/wiki/QU-32-FOH-Setup).  Mappings can be found on [this page.](https://github.com/NewValleyChurch/Infrastructure/wiki/QU-32-FOH-Setup)

  Unless any other changes are to be made, this scene can be permanently saved as the NV Base scene.

- Looked at the QSC DSP concerning the routing of a custom mix to the lobby.  Please see the issues tab for more information.

- Installed Slack app on the media computer.

- Turned off Phantom power on VOX 2 and 3, unless otherwise required for some reason, the dynamics on in those spots don't need 48V power.

- Turned ON phantom power on Stage R (or maybe it was L)  Either way, both are on now as only one was before.  If this is a problem due to a mix issue or the microphone has malfunctioned, we can kill it again.

- dSNAKE inputs are mapped to accommodate the cabling changes but none of the channel strips have changed to effect the end result.  The cabling _has_ changed on the stage.  For ease of reference, if you need to know which dSNAKE input a specific musician is using, look at the I/O Patch -> dSNAKE In screen.

- It’s actually possible to map one dSNAKE input to multiple channels.  You’ll see this reflected on Channel 10, which we haven’t used for anything yet.  The click track _and_ channel 10 will both be blipping along with the click.  That’s because the I/O setting for both channel 10 and the click channel are dialed in to dSNAKE Main 10.  As long as 10 is muted on the console like it usually is, it won’t come through the house.

- I relocated the Scarlett 18i8 from between the legs of my keyboard stand to the top of the Main dSNAKE (Stage right) and patched in to the inputs with small pigtails instead of using full cables, and ran a USB cable from my station to the 18i8.  This is a tool that we should all be able to use and isn’t exclusive to the keyboards, but does require a Mac or PC to control the mix.

- I rotated my keyboard setup to face the congregation, just to see how it feels live.

- I rotated the ME-U 180 degrees to hide the cabling and the lights.  I realize now that the lights may have been a visual indicator of activity for you guys so if that’s a problem, we can turn it back around, but a good indicator of a problem on the ME-U will be evident on the ME-1 consoles.

- I removed two of the three white Cat5e cables near Chris’s bass amp and re-ran darker cables.

- There were 4 power strips plugged into the stage left outlet for a total of 6 devices.  I removed two of the white power strips, and replaced them with the purple power strip that sits next to Carson’s feet.  It was and still is powering his tuner/mute pedal.  The power cord for the adapter for the mute pedal was tied up.  I untied it and ran it through a corrugated cable channel along with all of Carson’s feeds back to the dSNAKE Extender.  

- The power strip that was powering Chris’s two pedals was moved slightly stage left and the power source was changed from the stage to off-stage at the back-stage steps.  That same outlet also powers the stage left sub-woofer.

- There was a power cable on the apron of the stage on the first step leading around to the Christmas tree.  I pulled that as well as the taped cable on the floor of the sanctuary stage left, which was _only_ there to power the DMX light on the pole for the wedding.  _That_ power cable now feeds the sub-woofer stage left and the Christmas tree lights stage left from the back-stage power outlet on the step.

-  I ran fairy lights up everyone’s stands and across the stage, leaving the remaining lights to rest on the back-stage-left steps.  There were too many lights this time…I could have done the drum set but was too far along to go back.  The lights lay across the floor.  Last year I taped them down to cover the light between the stands because I thought it would have been distracting.  This year, as I look at them, it doesn’t look half bad as it is in my opinion.  It may look worse to have tape spanning between mic-stands, despite the fact that they may present a slight tripping hazard.

-  The male-female XLR cables are in a Tupperware box on the stage.  I have two boxes of gear in the last row of the sanctuary near the FOH with all of my cables etc.

-  I picked up a 55 yard roll of gray Gaff tape which unfortunately turned out to clash with the stage instead of blend.  Black seems to work better.  If we could find a darker gray it might be better, but this gray just doesn’t work well.

{% include links.html %}
