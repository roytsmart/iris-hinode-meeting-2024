# Inverting ESIS Observations of the Solar Transition Region using Convolutional Neural Networks

The EUV Snapshot Imaging Spectrograph (ESIS) is a sounding rocket instrument
designed to capture a hyperspectral image of the solar 
transition region over a wide field of view in a single exposure.
ESIS achieves this by using four identical slitless spectrographs, each oriented
with a different dispersion direction, to capture four different "overlappograms"
of the solar atmosphere.
These overlappograms are then inverted (in a process analogous to computed 
tomography) to retrieve a hyperspectral image of the solar atmosphere.

In this work, we present a convolutional neural network (CNN) that has been
trained to invert ESIS overlappograms using Si IV 1394 Å observations from the 
Interface Region Imaging Spectrograph (IRIS) as a proxy for the O V 630 Å 
spectral line observed by ESIS. 
We will use this CNN to invert observations gathered during the 2019 flight of
ESIS and investigate the nature of small-scale dynamic events observed in the
quiet solar transition region.