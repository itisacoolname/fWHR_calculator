# Facial width to height ratio (fWHR) calculator

<h3>Just want to calculate the fWHR? Check my web app: <a href="https://www.tiesdekok.com/calculatefwhr">Calculate fWHR</a></h3>

This page contains the code to automatically calculate the fWHR using Python and the `face_recognition` package which is available here: https://github.com/ageitgey/face_recognition

For the source code and documentation for the functions see the `FWHR_calculator` notebook: [FWHR Calculator](https://github.com/TiesdeKok/fWHR_calculator/blob/master/FWHR_calculator.ipynb)

![](https://github.com/TiesdeKok/fWHR_calculator/blob/master/example.png?raw=true)

## Requirements

1. Python 3 (not tested on Python 2.7)
2. The `face_recognition` package (as such, only for Linux and MacOS)

## Thanks

* All the heavy-lifting is done by the [face_recognition](https://github.com/ageitgey/face_recognition) package, make sure to check it out!   
* Also thanks to [fhboswell](https://github.com/fhboswell/Guardian-face-recognition-API) for providing materials to deploy to AWS Beanstalk