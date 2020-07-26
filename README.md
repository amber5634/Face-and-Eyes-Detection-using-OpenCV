# Face-and-Eyes-Detection-using-OpenCV
To detect face and eyes using Open CV

## Installation Required
- Numpy
- CV2

## To install Numpy using PIP
```
pip install numpy
```

Make sure that pip is upgraded. To do using pip command :
```
pip install -- upgrade
```
## OpenCV setup documentation for windows
(https://docs.opencv.org/master/d5/de5/tutorial_py_setup_in_windows.html)

> For other OS please go to OpenCV official installation documentation.

## OpenCV setup using pip command
```
#if you need only main modules
pip install opencv-python 
#if you need both main modules and contrib modules
pip install opencv-contrib-python
```
## Documentation for OpenCV setup using PIP command
(https://pypi.org/project/opencv-python/)

## To check whether OpenCV is installed correctly or not
```
import cv2 as cv
print( cv.__version__ )
```
If you don't get error then it is correctly installed.

> OpenCV comes with a trainer as well as detector.

## Key point to remember
- Remember to copy the files haarcascade_frontalface_default.xml and haarcascade_eye.xml in your current directory. 
- They are located in opencv/data/haarcascades

## Documentation for Cascade Classifier
(https://docs.opencv.org/2.4/doc/tutorials/objdetect/cascade_classifier/cascade_classifier.html)

## Documentation for Cascade Classifier Training
(https://docs.opencv.org/2.4/doc/user_guide/ug_traincascade.html)

## Documentation for Face Detection using Haar Cascades
(https://opencv-python-tutroals.readthedocs.io/en/latest/py_tutorials/py_objdetect/py_face_detection/py_face_detection.html#face-detection)

## Demo
![49g4uv](https://user-images.githubusercontent.com/30586187/88472952-36098a80-cf36-11ea-9d37-37b2ea19bf19.gif)





