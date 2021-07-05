# YoloV5


It refers to “You Only Look Once” is one of the most versatile and famous object detection models. For every real-time object detection work, YOLO is the first choice by Data Scientist and Machine learning engineers. YOLO algorithms divide all the given input images into the SxS grid system. Each grid is responsible for object detection. Now those Grid cells predict the boundary boxes for the detected object. For every box, we have five main attributes: x and y for coordinates, w and h for width and height of the object, and a confidence score for the probability that the box containing the object.

To understand the YOLO algorithm, it is necessary to establish what is actually being predicted. Ultimately, we aim to predict a class of an object and the bounding box specifying object location. Each bounding box can be described using four descriptors:
center of a bounding box (bxby)
width (bw)
height (bh)
value c is corresponding to a class of an object (such as cat,dog,etc..)

Steps: 
1. Created yaml file to give the path of dataset. YAML (a recursive acronym for "YAML Ain't Markup Language") is a human-readable data-serialization language.
2. Created the Setup for YOLOv5 by installing the requirements and clone the repository.
3. Applied the YOLOv5 model (pre-defined) 
4. Trained the model with yolov5s

