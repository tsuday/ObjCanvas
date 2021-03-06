# ObjCanvas
Load and draw *.obj file on Canvas, and download as image.

## How to Use

### Import
You can import _ObjCanvas.js_ by the ways below:
* Import by _script_ tag in your HTML.
* Import into your app scripts by build tools(e.g. _webpack_).

### Implementation
1.Locate _div_ area used as Canvas in your HTML

2.Relate div area to ObjCanvas.js object by calling its constructor

3.Load *.obj file and draw it on canvas by calling ObjCanvas#loadObjFile

4.Save scenes drawn on canvas as image by calling ObjCanvas#save or ObjCanvas#autoSave

### Options
ObjCanvas.js has options below:
* Object can be drawn as Depth Map
* Threshold angle drawn as contour

Please see JsDoc for more details.

## Sample Application
This project contains sample application _SampleApp_ for reference.<br>
SampleApp needs to be run on web server(e.g. _Apache_ or _nginx_).


## Requirements
ObjCanvas requires libraries below:
* Three.js
* OBJLoader(Contained in examples for Three.js)
* OrbitControls(Contained in examples for Three.js)
* Canvas-toBlob.js
* FileSaver.js

SampleApp requires:
* Libraries mentioned above
