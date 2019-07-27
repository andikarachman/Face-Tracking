# Face Tracking System


## Introduction

An ideal object tracking algorithm only require the object detection phase once (i.e., when the object is initially detected). Therefore, it will be extremely faster than running the actual object detector itself. We use MobileNet SSD as our face detector. The input of this system will be image streaming from webcam.

## Dependencies
  * opencv
  * numpy
  * imutils

## Command format

_$ face_tracker.py [-h] -p PROTOTXT -m MODEL [-c CONFIDENCE]_

- PROTOTXT: path to Caffe 'deploy' prototxt file. This is included in the 'model' folder.
- MODEL: path to Caffe pre-trained model. This is included in the 'model' folder.
- CONFIDENCE: minimum probability to filter weak detections

