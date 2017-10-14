# Microphone Array Impulse Responses (MAIR) - Library and Renderer >
by Applied Psychoacoustics Lab, University of Huddersfield

Authors: Hyunkook Lee and Connor Millns
h.lee@hud.ac.uk, connor.millns@hud.ac.uk

## Description
MAIR is an open-access library of an extensive set of room impulse responses (RIRs) captured using numerous microphone arrays from 2-channel stereo to 9-channel surround with height. The RIRs were obtained for 13 loudspeakers placed in various positions on the stage at St.Paul's concert hall in Huddersfield, UK (RT60 = 2.1s). The library features five 2-channel stereo pairs, 10 main surround arrays, nine height microphone arrays for 3D main arrays and 15 4-channel configurations for surround and 3D ambience arrays, each with varied microphone polar patterns, directions, spacings, and heights. A dummy head and a first-order-Ambisonics microphone are also included. The library is provided with a rendering tool, with which the user can easily simulate different microphone combinations in both loudspeaker and binaural playback for 13 source positions. The audio inputs for the rendering tool can be directly fed from a DAW session as well as by manual file allocation.

## Prerequisites
Max 7 must be installed to run this software. It can be found and downloaded for free here:
https://cycling74.com/downloads
NOTE: A Max 7 license is not required to run the MAIR Rendering Tool. 

## Installing
Once Max 7 is installed, simply run the MAIR_RenderingTool_v1.mxf max collective file.

## License
This project is licensed under the CC-BY-4.0 License - see the license.md file for details

## User guide
Technical details of the MAIR library and the user guide for the MAIR renderer are presented in the attached "MAIR technical descriptions and user guide" document.

## Publication
The MAIR library and renderer was presented at the Audio Engineering Society 143rd International Convention. 
Download link: http://www.aes.org/e-lib/browse.cfm?elib=19307

## Referencing
If you use the MAIR library and renderer for your research, please reference it as follows.
Lee, H. and Millns, C. (2017), "Microphone Array Impulse Response (MAIR) Library for Spatial Audio Research," presented at the 143rd Audio Engineering Society Convention, New York, e-Brief 356.

## Acknowledgements
All microphones used for this project were provided by Sennheiser/Neumann, UK.

The University of Huddersfield's HISStools (the multiconvolve~ object) was used for multichannel convolution within the MAIR renderer.
http://eprints.hud.ac.uk/id/eprint/14897/

The University of York’s SADIE BRIR database was used for the binauralisation of 9ch 3D reproduction of the MAIR Library.
The full database and the licence can be found here:
https://www.york.ac.uk/sadie-project/binaural.html

## Feedbacks and bug report
All feedbacks are welcome. To report any bugs or ask any query about the rendering tool, please contact Connor Millns (connor.millns@hud.ac.uk) and Hyunkook Lee (h.lee@hud.ac.uk).
If you would like to be updated for MAIR or other research news by the Applied Psychoacoustics Lab, please sign up here: https://goo.gl/forms/CkqgkdePwOTR8XCI2


