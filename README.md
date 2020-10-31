# Raccoon Detector

This project contains 2 part : <br/>
<br/>
First part <br/>
Training custom YOLO-v3 keras object detector (raccoon detector) <br/>
<br/>
Used RaccoonDetector.ipynb file on colab for training custom YOLOv3 model with dataset from https://public.roboflow.com/object-detection/raccoon/ <br/>

Second part <br/>
Using the trained raccoon model for real time detection using webcam <br/>
<br/>
model_data folder <br/>
_classes.txt file contains class names one wanted to detect (here it is 'raccoon') <br/>
yolo.h5 file contains saved trained raccoon model weights <br/>
yolov3.cfg contains configuration for yolov3 <br/>
yolo_anchors.txt contains anchors (width, height) - which are sizes of objects on the image that resized to the network size (width= and height= in the cfg-file).<br/>
<br/>
yolo3 folder <br/>
model.py file contains YOLO-v3 Model defination in keras <br/>
utils.py file contains miscellanous functions to perform operations on every frame <br/>
<br/>
web_detect.py contains code for interfacing with real time frames


