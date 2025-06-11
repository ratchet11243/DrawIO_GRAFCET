# DrawIO_GRAFCET
A Draw.io library containing simple GRAFCET symbols with reference to IEC 60848:2013.

All symbols are created using draw.io's existing standard palette.

The library can be implemented via download ~or through direct URL access~.

Draw.io's website contains guidance for importing custom libraries in draw.io - https://www.drawio.com/blog/custom-libraries

Currently it has not been possible to figure out automatic updating of the library via github URL - this had previously worked, so I am unsure if it is caused by an update in the desktop version of draw.io

#### Branching Transitions
Currently, the implementation of transition-connectors means that transitions can be difficult to place on a vertical line, in accordance with the standard.
The solution for this is to alter the relative placement of the transition bar-object, via that object's 'Arrange'-tab, as seen below.

![An image showing the 'Arrange'-tab for a transition's horizontal bar-object in draw.io](images/branchTransitionWorkaroundBranch.png)
