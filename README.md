# mouth-open
Detecting when a human's mouth is open

## Referenced Code

[Adrian Rosebrock - drowsiness detection](https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/)

I was interested in implementing a similar function for calculating the aspect ratio of the mouth instead of both eyes. 

## Dependencies
Python modules for:
* scipy
* imutils
* numpy
* dlib
* cv2

## Usage
This sample version uses your webcam, so make sure that the device you are using has one.  Otherwise, you will need to change the code to take in a video file.

#### To run the code
```bash
python detect_open_mouth.py
```

![sample gif](./video/mouth_open.gif)
