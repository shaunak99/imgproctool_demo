# Contour & Measurement

This repository demonstrates an interactive tool to find a contour in an RoI. The distance from a point on the image to the contour can then be calculated.

The tool uses [OpenCV.js](https://docs.opencv.org/3.4/df/d0a/tutorial_js_intro.html) for contouring.

 UI:
 * Draw rectangle to select RoI
 * Use Esc key to escape rectangle drawing in progress
 * Mouse click to select one of the generated contours 
 
 Note: Currently only one contour is allowed for demo.
 
 Two disabled buttons are present to showcase other implementations that may be added in the future. These are:
 * Draw Contour:- Manually draw contour and fit to base image
 * Find Tri-class Contour:- Find contour automatically using Tri-class.
 
 ## Demo
 
[![Demo](http://img.youtube.com/vi/S6u80YKieMQ/0.jpg)](http://www.youtube.com/watch?v=S6u80YKieMQ "Demo")
