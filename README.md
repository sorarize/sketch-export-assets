[sketch-export-assets]: https://github.com/GeertWille/sketch-export-assets

# sketch-export-assets

Export assets for Android, iOS, Windows Phone in Sketch.

## Note

This plugin is forked from [sketch-export-assets], and this version added two improvements
- added ldpi for android export
- folder name is configurable


## Installation

The actual location of your Sketch plugins directory will vary. To open it just click on the `Reveal Plugins Folder` under the `Plugins` menu in sketch.

Run following command after going to the sketch plugins folder:

`git clone https://github.com/sorarize/sketch-export-assets.git`


## Shortcuts

* iOS Export: ctrl + alt + shift + 1
* Android Export: ctrl + alt + shift + 2
* Windows Export: ctrl + alt + shift + 3


## Adding Padding to slices
From now on you can manually decide how big you want your exported asset to be. Just include a slicelayer in the group of that asset and it will not use the size of the group but the size of that slicelayer...
