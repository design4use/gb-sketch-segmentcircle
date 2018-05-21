*To install*, [Download here](https://github.com/design4use/gb-sketch-segmentcircle/archive/v2.05.zip), then double click the .sketchplugin file inside the zip file.

# Segmented circles
Saves hours by automatically creating precise circular graphics as areas or lines with custom segments for analytics, graphs and dashboards.

![](./img/screencapture.png)

## Brand new version 2.04
Completely rewritten v2 plugin, now also creating variable values pie chart segments, perfectly spaced dashed circles and tick mark graphics. 2.04 adds support for Sketch 50 as well as Sketch Runner (http://www.sketchrunner.com)

## Description
### Create segmented circle

![](./img/seg.png)

➊ Radius  ➋ Number of segments  ➌ Thickness

This is the base circle with a configurable number of segments and thickness.
Will be drawn as line segments if thickness is specified as 1. Remembers previously used values.

### Create variable segments circle

![](./img/var.png)

➊ Radius  ➋ Custom values  ➌ Thickness

A pie chart style segments circle with a configurable set of comma-separated values and thickness.
Will be drawn as line segments if thickness is specified as 1. Remembers previously used values.

### Create tickmarks circle

![](./img/tix.png)

➊ Radius  ➋ Tick marks stroke width  ➌ Tick marks length

Tick marks circle with completely configurable major and minor tick marks.
Drawn as separate groups and easily configurable. Remembers previously used values.

### Create dashed circle

![](./img/dsh.png)

➊ Radius  ➋ Dash length  ➌ Gap length

For an evenly spaced dashed circle with dashes and spaces customizable (in px).
Will be drawn as line segments if thickness is specified as 1. Remembers previously used values.

Note: Some of these will allow to configure a bottom cut-out angle (in degrees). When specified to be other then 0, the segmented circle will render as open, with the opening at the bottom.

### Reset to defaults
Removes last used values and resets to defaults.

## License
(c)2016 German Bauer. All code covered by [this BSD 2-clause style license](./LICENSE.md)
