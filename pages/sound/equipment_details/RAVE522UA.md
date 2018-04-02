---
title: "QSC Rave 522ua Digital Signal Processor"
keywords: signal processor, DSP
sidebar: main_sidebar
permalink: RAVE522UA.html
folder: /sound/equipment_details
toc: false
---
<div class="row">
        <div class="col-lg-12">
            <ul id="myTab" class="nav nav-tabs nav-justified">
                <li class="active"><a href="#service-one" data-toggle="tab"><i class="fa fa-camera"></i> Picture</a>
                </li>
                <li class=""><a href="#service-two" data-toggle="tab"><i class="fa fa-pencil"></i> Details</a>
                </li>
                <li class=""><a href="#service-three" data-toggle="tab"><i class="fa fa-book"></i> Equipment Documentation</a>
                </li>
                <li class=""><a href="#service-four" data-toggle="tab"><i class="fa fa-question"></i> FAQ</a>
                </li>
            </ul>
            <div id="myTabContent" class="tab-content">
                <div class="tab-pane fade active in" id="service-one">
                    <p>This is the DSP that routes all of the audio input from the board to the appropriate amplification systems including the mains, subs, and the lobby.</p>
                    <p markdown="1">**From the manufacturer's website:** RAVE units, which combine DSP functions with CobraNet digital audio transport, and the DSP 322ua dedicated signal processor, are also integral to QSControl.net systems. BASIS, RAVE and DSP units are all programmed and controlled via QSC’s Venue Manager software.
</p>
                    <p>{% include image.html %}</p>
                </div>
                <div class="tab-pane fade" id="service-two">
<div markdown="1">
## QSC Digital Signal Processor Wiring Details

The RAVE 522UA is a rack mounted digital audio router and signal processor.  Every bit of audio that we produce at New Valley passes through this box and is sent to one of many locations.

There are currently 3 inputs and 6 outputs being utilized.

### Inputs and Sources

- Input 1: Receives all main mix faders from the Main L output.
- Input 2: Receives all main mix faders from the Main R output.
- Input 5: Receives all Mix 4 output.

- Input 3, 4, 6, 7, & 8 are not connected.

### Outputs and Destinations

- Output 1: Stage Left Subwoofer
- Output 2: Stage Right Subwoofer
- Output 3: Stage Left Mains
- Output 5: Center Mains
- Output 6: 70V Amp Channel 1, Foyer.
- Output 7: Stage Right Mains

### Network Connection

- QSControl:  Standard RJ45 Ethernet port connected to the network switch.  Can be accessed using QSControl.net software on a Windows based computer only.

(Note:  The RAVE is a signal processor as well as a router.  It's the first place the audio signal is pre-processed with custom EQ after it leaves the QU-32.  It is also where the signal is crossed over to send the appropriate frequency ranges to the active speakers.)  In other words, it isolates the low frequencies from the high frequencies and sends the appropriate signals to the sub-woofer and the high/mids.

### Wiring Diagram

<img src="images/RAVE522UAWiringDiagram.png" width="100%">
</div>
                </div>
                <div class="tab-pane fade" id="service-three">
                    <p>{% include document.html type="User Manual" %}</p>
                    <p><a href="{{page.document_folder}}/RAVE522UAWIRING.PDF">Rave 522UA Wiring Diagram</a></p>
                </div>
                <div class="tab-pane fade" id="service-four">
                    <p>Items from the Sound FAQ that are specific to this device will be listed here.  Until then, use the FAQ link under the sound menu in the sidebar.</p>
                </div>
            </div>

        </div>
</div>

{% include links.html %}
