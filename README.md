# WebVR with Cesium.js and milsymbol.js

This is based on the Cesium Cardboard example to respond to a VR device orientation.

The [WebVR](https://w3c.github.io/webvr/) API provides purpose-built interfaces to VR hardware 
to allow developers to build compelling, comfortable VR experiences. 
 
[Cesium](http://cesiumjs.org/) is a JavaScript library for creating 3D globes and 2D maps in a web browser without a plugin.
A Scala.js facade to Cesium is at [CesiumScala](https://github.com/workingDog/CesiumScala).

[milsymbol.js](https://github.com/spatialillusions/milsymbol) is a library in pure JavaScript that creates SVG symbols according to MIL-STD-2525C,
MIL-STD-2525D and NATO STANAG APP6(b). 

## Usage

Install [Cesium](http://cesiumjs.org/).

Download [milsymbol.js](https://github.com/spatialillusions/milsymbol/tree/master/dist) and put it in the 
"Cesium/Apps" directory.

Put this file "testwebvr.html" also in the "Cesium/Apps" directory.

Connect your VR headset to your computer.

Launch Cesium (node server.js).
 
Point your browser to http://localhost:8080/Apps/testwebvr.html

Push the VR button on the bottom right corner to go into VR mode.
 
Move your head around Sydney Australia.
 
I don't have a VR device, so let me know if this works. 
 