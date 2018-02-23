---
title: Ableton Live Basics
keywords: Ableton
summary: "Basics of Ableton Live"
sidebar: main_sidebar
permalink: ableton-live-notes.html
folder: media
---

#### Ableton Live

Current Version:  9.7.5
Build: build 2017-10-02

# Basics for NV setup

Ableton Live is a DAW (Digital Audio Workstation).  It allows you to record and manipulate audio and MIDI in as many creative ways as you imagine.  Any device that can send or receive MIDI can be integrated into Ableton and controlled by Ableton.

When you load Ableton Live, a default template is loaded and given the name "Untitled."  

  **This is not the working set.**  _**It is a snapshot in time of a previous version of the working set.**_  

  It's purpose is to create a new workspace with familiar settings, but it does not load recently created new content.  That data is stored in the main set that was created recently.

## Initial Startup Sequence

1.  Start Ableton Live.
2.  Before you do anything, load the actual New Valley set.  This is found in the File Browser on the left side of Ableton Live and is named "NV Default Setup.als."

### Loading a New Session

You do not need to do this before each service.  Only at the beginning of the day before the first event.  Both sermons can be captured on the same timeline either back to back, or on duplicated tracks, or if you record in session mode, each sermon can be recorded inside of it's own Clip Slot.

1.  In Ableton, there's a file browser on the left.  The far left contains a list of Categories and Places.
2.  Make sure "User Library" is selected on the far left under PLACES.
3.  In the next pane to the right, you should see a few entries.  One of those is NV Default Setup.als.
4.  Double Click it to load it as the current set in Ableton Live and disregard any of the Untitled document's settings.

You are now ready to proceed.

## Elements of the NV Set

The following explains the NV Set and it's basics.

Ableton has two modes for workflow.  The Arrangement View, and the Session View.  Arrangement view situates the tracks horizontally and Session View situates them vertically.  Each view has a purpose.  Press TAB to switch between them.

Arrangement view is great for laying out a song arrangement, or a series of recorded clips over time, like a video editor.

Session View is great for organizing clips that have already been created, and is _also_ great for recording.

_Understanding how to record the sermon, or other input in both Session and Arrangement view is a good skillset to have._

### Current Track Setup

There are multiple audio tracks in this set.  Each track corresponds to a Fader Strip on the QU-32, with one exception:  the [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) track is a _MIDI_ track, and it controls every aspect of the lighting automation.  

The QU-32 has Custom Layer mappings (Fader 1-3) which control the [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) Plug-in which sits in the [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) MIDI Track.  (If you wish to see the devices that are dropped into the track, Double click the [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) track title.)

The position of the tracks on the set is relevant only to the organizational strategy chosen.  Where tracks are doesn't matter as much as setting up each track with the right input source.  The input/output section of each track determines where audio or midi comes from and goes to.

- **Wireless Microphones:**  There are 3 tracks assigned to the wireless mics.  They are grouped together, which is why you'll see 4 columns with one column having a heading that spans the width of the other three columns above their titles.

- **[DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS):**  This is the MIDI track that contains the [DMXIS](https://github.com/NewValleyChurch/Infrastructure/wiki/About-DMXIS) lighting controller plug-in.

- **Drums:**  There are 6 tracks that have been assigned to the drum faders and they're all grouped together.

- **Vocals:**  Vox 1 - 4 have been assigned to their own tracks and are also grouped together.

- **All other Instruments and inputs:**  Nothing else is grouped, but the remainder of the set has almost every input that we use.  Horn, Bass, Keys, AC Guitar, etc.  The stage mics do not currently have an input track in this set.

### Recording

Any track that is armed _(the little red dot at the bottom of the track in Session view, or to the right in Arrangement View)_ will record whatever signal is received on that track.  Remember, the track I/O Input setting in Ableton determines the source of the audio.

#### Recording in Session Mode

Recording in Session Mode accomplishes the same goal as Arrangement Mode, but looks a little different.

You can record by arming a track, then by clicking one of the little circles in a clip slot.  

  1. Arm the track(s).  Multiple tracks can be armed by holding down CMD while clicking them.

  - Click the little circle in a clip slot to initiate recording.  You will see a count-in on the transport at the top of the screen, and then a clip fills the slot and recording begins.

  - If you want to see the wave file being built in real-time, double click the clip that's currently recording.  Be careful NOT to click the start arrow on the clip as that will stop recording and queue the clip to replay at the next downbeat on the time transport.

#### Recording in Arrangement Mode

If you switch to Arrangement Mode, the first thing you need to do is click the little red arrow/hamburger menu on the far right side of the "Beat Time Ruler."  (That's the measure counter on the top of the track display just to the left of the 'set' button.)  

**This will activate Arrangement Mode** and disengages Session Mode.

  1. **Set up workspace:**  If this is a brand new session (i.e. new Sunday), click somewhere in the track display where no data has been recorded then:

    - Press Command-A to select all.

    - Press Del to delete all recorded events.

    - Click and hold on the Beat Time Ruler and drag the mouse up.  This will zoom OUT to the full length of the current set timeline.  Zoom level is a personal preference.  Sometimes you'll zoom in to see more detail.  Sometimes you won't.

    - Double click the STOP button in the transport to ensure we're at the beginning of the timeline (1.1.1 or Measure 1, Beat 1, Sixteenth note 1).

  - **Locate Track:** Find the track you want to record.
  - **Arm the track.**

  - **Prevent Loop:** Make sure the LOOP Switch is OFF.  The loop switch is at the top of the screen.  It looks like a rectangle with a little arrow denoting a loop.  

  **If this is switch is on, the recording will begin at the start of the loop brace and will end at the end the loop brace, looping back to the beginning, overwriting the recording over and over again.**

  It's a hard lesson to learn.  :)

  - **Record:** Once you're ready...press the Record button in the transport. (Circle at the top of the screen.)  You'll see a count-in if the Quantization menu is set to anything other than None, and it will begin recording.  If Quantization is set to NONE, recording begins immediately.

  - **Zoom Level:** During recording, you might find you're zoomed in too close, and the play head will have already left the screen to the right.  If this is the case, you can press Shift-CMD-F to have the track display follow the clip recording in real-time.  This will put the playhead in the center of the screen and start auto-scrolling the display.

  - **End Recording:** When finished recording, press the Stop button on the transport, then disarm the track so you don't accidentally overwrite it.
  - **Reset Transport**:  Double click the stop button to return to 1.1.1.

  - You're ready to begin post production.

### Post Production

#### Preserve

  1. **Name the Clip:**

    -  Clip naming is simple, and it's a great habit to get into.  Plus it makes it easy to know what you're about to hear when you refer to it later. Click the title of the clip in either Session or Arrangement Mode and press Command-R, or right click and Rename.  (If you recorded in Arrangement Mode, the clip will not appear in Session Mode.  That would be done manually.)

    - Enter the title of the Sermon or title of the recording as needed and press Enter.  Now your clip has a name.
  - **Listen to the clip to ensure there is output.**

  - **Adjust the clip output level if needed:**
    - Double click the clip.

    - Make sure you can see the Sample section in the Clip View at the bottom.  If you can't, click the little circle icon with the squiggly thing next to the E icon.  It should light up, and you should be able to see the Clip View.

    - Adjust the clip Gain to boost the output of the clip.  (Note: This may change in the future as it's possible to put a Utility device on a return track to boost the output of any given track with less overhead.)

    - Once you have the right level, proceed.

  - **Select the entire clip for exporting:**

    - Click the clip header to select it.

    - Right click the clip and click Loop Selection or press CMD-L.  This wraps the start and end point of the sermon with the loop brace and defines the start and end point that will be exported.

    - Select the Loop Brace.  Click somewhere in the middle of the loop brace.  This selects ALL clips in the entire arrangement set and prepares for export inside of the range of the loop brace.

  - **Export the Audio:**

    1. Click File -> Export Audio/Video.

      - Settings:

        - If Master is selected as the Rendered Track, then every track that is being sent to Master will be exported to the audio file.  You can, if you wish, select just the sermon audio track for export.  This selection is dependent upon what you're arrangement looks like and what you do or do not want to be a part of the final file.

        - File type is relatively irrelevant given the fact that we have good cross-compatibility between computer systems, and because we convert to MP3 anyway.  If the file will be needed in a Windows environment, export it as WAV.  If it will only be used in OSX, go with AIFF.  Both can be converted to MP3.

        - Leave the Sample Rate at 48,000.

        - Bit Depth 16.

        - No Dither.
        - All buttons set to OFF.   

    - Click Export and Choose a location for the export.

    - Listen to the exported file to confirm audio routing was correct during export.

    - **Please make sure we don't print a blank audio file.**

  - **Convert the file to MP3:**
    - This can be done right inside of iTunes, or you can use the MP3 converter in the launch bar.  

  - **Publish.**

### Cleanup

  - If you recorded in Arrangement Mode, you'll want to drag the entire clip from Arrangement Mode to the next available clip slot in Session Mode in the corresponding track:

    1.  In Arrangement Mode, click and hold the clip header (where the name of the clip is).

    2.  While holding the mouse button, press TAB to switch to Session Mode.

    3.  Drop the clip into the next available slot down in the track you recorded.  Truth be told, it can be dropped into _any_ audio track, but for organizational purposes, keep the sermons in the appropriate wireless mic track.

    4.  You can return to Arrangement Mode by pressing tab.  Then, you can delete the clip from Arrangement Mode as it has now been moved to Session Mode.

  - If you recorded directly into a slot in Session Mode, start here:

    1.  Click and drag the clip from the clip slot to the file browser into the Sermons folder.  This step saves the clip into the user library such that it can be dragged into any future set.

    -  Rename the Scene:
      - In Session Mode, click the Scene number in the Master track that lines up with the clip you just dropped into the slot.  (The row that you're working on.)

      - Rename it to the date of the recording by pressing CMD-R, then press Enter to save.

  - **Press CMD-S to save the entire Set.**
