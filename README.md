# iris-hinode-meeting-2024
Materials for my presentation at the IRIS-Hinode 2024 meeting in Bozeman, Montana.

## Abstract

**Inverting ESIS Observations of the Solar Transition Region using Convolutional Neural Networks**

Roy T. Smart, Charles C. Kankelborg, and Jacob D. Parker

The EUV Snapshot Imaging Spectrograph (ESIS) is a sounding rocket instrument
designed to capture a hyperspectral image of the solar
transition region over a wide field of view in a single exposure.
ESIS achieves this by using four identical slitless spectrographs, each oriented
with a different dispersion direction, to capture four different "overlappogams"
of the solar atmosphere.
These overlappograms are then inverted (in a process analogous to computed
tomography) to retrieve a hyperspectral image of the solar atmosphere.

In this work, we present a convolutional neural network (CNN) that has been
trained to invert ESIS overlappograms using Si IV 1394 Å observations from the
Interface Region Imaging Spectrograph (IRIS) as a proxy for the O V 630 A
spectral line observed by ESIS.
We will use this CNN to invert observations gathered during the 2019 flight of
ESIS and investigate the nature of small-scale dynamic events observed in the
quiet solar transition region.

## The slides on the web

https://roytsmart.github.io/iris-hinode-meeting-2024/ shows the slides with
their movies playing. It is built from the deck with
[pptx-to-html](https://github.com/roytsmart/pptx-to-html):

```bash
pptx-to-html "Inverting ESIS Observations of the Solar Transition Region.pptx" docs \
    --title "Inverting ESIS Observations of the Solar Transition Region using Convolutional Neural Networks" \
    --subtitle "IRIS-Hinode 2024 · Bozeman, Montana · the slides as they were presented, with the movies playing" \
    --reencode
```
