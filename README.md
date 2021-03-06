LPMT - Little Projection-Mapping Tool
---------------------------------------
(C) 2011, HVA - Hermanitos Verdes Architetti / Modena, Italy

[![Flattr this git repo](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=hv_francesco&url=https://github.com/hvfrancesco/lpmt&title=LPMT Little Projection-Mapping Tool&language=&tags=github&category=software)


LPMT is a little projection-mapping tool for use in our office,
it is developed in C++ using OpenFrameworks.
It’s based on simple quad warping paradigm, and, though rather simple, can
be used to achieve complex and professional projection-mapping sets.

This is the up-to-date version of lpmt, based on OpenFrameworks 007

DOWNLOAD:
----------

At the moment LPMT is only available as source code, and we've only tested it on linux systems
but thanks to the multi-platform nature of OpenFrameworks it should work out-of-the-box on
Windows and OsX too.

up-to-date code (git repository):
http://gitorious.org/projection-mapping

for the github fans, the repository is mirrored here:
https://github.com/hvfrancesco/ProjectionMapping

if you don't like git, you can find a rarely updated zip file:
http://www.hv-a.com/projectTiles/projection-mapping.zip



MAIN FEATURES:
--------------

* up to 36 independent layers (remember you can use a solid black quad even as a mask)
* possible content: solid color, images, video, live-cam, slideshows, smoothly changing solid colors, and more ...
* independent opacity setting for each content element
* customizable green-screen (chromakey) for video and live-cam sources
* horizontal and vertical flipping for image, video and live-cam content
* customizable colorization for each content element
* customizable video speed and volume
* save/load project set to/from xml file
* syncronized start for video elements
* vertex snap function for adjacent quads
* cam snapshot background for rough positioning of quads
* customizable speed for slideshows and color transitions
* synced multi-projectors shows
* control and setup through a rich set of OSC messages


KEY COMMANDS:
-------------

’s' – saves settings to xml (projection_settings.xml in data folder)
‘l’ – loads settings from xml file

‘a’ – adds new quad
‘>’ – go to next quad
‘<’ – go to previous quad
'+' - raise active quad position in layers pile
'-' - lower active quad position in layers pile
‘z’ – selects first gui page for active quad settings
‘x’ – selects second gui page for active quad settings
‘c’ – selects gui page for active quad corner position fine-tuning
‘q’ – fills window with active quad
‘1’ – shows general settings page of gui

‘g’ – toggles gui (for quad warping with mouse gui must be switched off)
‘f’ – toggles fullscreen mode
‘w’ – toggles cam snapshot window background

‘spacebar’ – toggles projection/setup modes
‘r’ – resyncs all videos and slideshows in all quads to starting point
‘p’ – starts projection
‘o’ – stops projection

‘m’ – connects to a MostPixelsEver sync server



TODO:
----------

- quad masking (needs some OpenGL-fu)
- a timeline (?)
- grid warping
- edge feathering for multi-projector shows
- overlay modes for quads


CONTACT:
----------

you can contact us at:
francesco[at]hv-a.com

-------------------------------------------------------------------------------

this README was last edited by hv_francesco on Wed Feb 23, 2011 19:54 GMT+1,
edited 1 times in total.

__________________________________

HVA - hermanitos verdes architetti
modena - italy
www.hv-a.com
