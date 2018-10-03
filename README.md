[![Build Status](https://travis-ci.com/hoopoe/FR-android-dlib-opencv.svg?branch=master)](https://travis-ci.com/hoopoe/FR-android-dlib-opencv)

Facial Recognition on Android using dlib and opencv
============


This app demonstrate semi realtime face detection, tracking and recognition based on predefined face vectors.


Notes:

1. From https://github.com/davisking/dlib-models

  copy 
  * shape_predictor_5_face_landmarks.dat
  * dlib_face_recognition_resnet_model_v1.dat
  
  to /sdcard/Download 

2. To enable Mobilenet/TF activity:

  You need to find spc_mobilenet_v3_1x_0.52_cleaned.pb
  Copy it into app\src\main\assets
  

3. To enable SSD face detection:
  Copy frozen_inference_graph_face.pb from 
  https://github.com/nodefluxio/face-detector-benchmark/blob/master/models/ssd/frozen_inference_graph_face.pb
  into app\src\main\assets