# AR-Examples
The examples from [Lee Stemkoski](https://github.com/stemkoski/AR-Examples) was forked and a few examples are added.
* for using these examples, print out the [markers](markers/Marker_Printout_AR_demo.pdf) and
* switch on the WebCam and let browser to access the WebCam.
* place the marker mentioned in the [demo page](https://niebert.github.io/AR-Examples) in front of the camera and move the markers
* in some AR examples multiple markers can be used and different objects can be places
* also [360-degree (equirectangular) images](https://www.github.com/niebert/HuginSample) are used to and you could use e.g. the [hiro-marker](markers/Marker_Printout_AR_demo.pdf) to look around

Check out the online demos with:
## [Online-Demo](https://niebert.github.io/AR-Examples)
* [Download ZIP-file](https://github.com/niebert/AR-Examples/archive/refs/heads/master.zip) of this repository
* see also [Wikiversity learning resource about 3D-modelling](https://en.wikiversity.org/wiki/3D_Modelling/Examples/AR_with_Markers)
* [HuginSample - Equirectangular Images](https://www.github.com/niebert/HuginSample) or [AFrame Navigation](https://niebert.github.io/aframe360navigation/)
 
## 3D-Models on Marker
Sketchfab publishes 3D-Models as creative commons. One the CC-BY-4.0 models a dinosaur (Spinosaurus) is used as a 3D model on a marker. The model is called 
* "[primal carnage spinosaurus](https://skfb.ly/pswyN))" (URL: https://skfb.ly/pswyN) created by `seth the yutyrannus`.
* The 3D model is licensed under Creative Commons Attribution (http://creativecommons.org/licenses/by/4.0/).
* ***AR-Web-Demo:*** [Spinosaurus on AR-Marker](https://niebert.github.io/AR-Examples/spinosaurus_hiro_ar.html) - ***VR-Web-Demo:*** [Spinosaurus in VR](https://niebert.github.io/HuginSample/spinosaurus_rieselfelder_aframe.html)
* GLB-File: [model3d/primal_carnage_spinosaurus_small.glb](model3d/primal_carnage_spinosaurus_small.glb)
![Spinosaurus on AR-Marker](./img/spinosaurus_on_ar_marker.png)

* **(Print Marker)** Use Hiro-Marker as print out
* **(Display 3D Model in Browser)** Start [Web-Demo - Spinosaurus on AR-Marker - "Hiro"](https://niebert.github.io/AR-Examples/spinosaurus_hiro_ar.html)
* **(Marker in Camera Viewport)** Allow camera to record Hiro-Marker in Webcam.
* **(3D Model in Webpage displayed on Marker)** Dinosaur will be placed on Hiro-Marker in camera image.
* **(Coordinate System)** Hiro marker (and any other marker) defines in the asymmetric shape a coordinate system in which the objects are placed.
* **(Scaling of Object - Marker Size)** The size of the Hiro marker defines the unit length in the coordinate system. E.g. triple size of printed Hiro marker scales the objects by the factor 3.
  
![Hiro-Marker](./markers/hiro.png)
