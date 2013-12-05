ai_resize_artboard
==================

This script is based on the script shrinkABtoFitArt.jsx by Carlos Canto. 

## Description

Use this Adobe Illustrator Script Extension to resize the artboard to a user-defined size, then center the artwork on the artboard.

## Installation

Download the ResizeArtboard.jsx file and copy to Illustrator/Presets/{language}/Scripts/

You will need to relaunch Adobe Illustrator after installing the script.

### Running the Script

1. Open an Adobe Illustrator file with. The file must contain only one artboard and at least one object on the page
2. Select File > Scripts > ResizeArtboard
3. Enter a positive integer value at the prompt
4. After the script has run, save your file

### Batch Processing Files

More to come ...

### Known Issues

* 2013-12-05 - The script was created for a very specific use case: To resize the artboard for vector icons and to center the icon.
* 2013-12-05 - The artboard is assumed to be square.
* 2013-12-05 - The script has not been tested with more than one artboard. It is known to work well with a single artboard.
* 2013-12-05 - In order to center the artwork, the script adds every element to a new group. The items are not un-grouped after they are centered (not yet anyway).