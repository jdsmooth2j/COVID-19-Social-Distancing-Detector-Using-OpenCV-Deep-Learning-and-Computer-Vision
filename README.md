# COVID-19-Social-Distancing-Detector-Using-OpenCV-Deep-Learning-and-Computer-Vision-in-10-Mins
OpenCV Social Distancing Detector

Big shoutout and credits to Pyimagesearch blogs for their amazing works and tutorials.

## Basic Requirements
```
1. Download and Install Python
2. Install the Necessary Packages: Numpy, OpenCV
```

## Quick Summary
This repository explores the step by step process for running your the social distancing detector in 5 to 10 mins.
* https://www.youtube.com/watch?v=O9mB_VvRqpw 

This readme explores every step required to get you running your the social distancing detector quickly:
```
1. Download the Repository
2. Setting up the Social Distancing Detector Directory Structure
3. Running the Social Distancing Detector
```
Enjoy the run... :)

## Procedure
### 1. Download the Repository
Download all the files from my repository to your "Downloads" folder.

### 2. Setting up the Social Distancing Detector Directory Structure
Unzip the downloaded files from the Downloads folder and then create new folder and name it as "social-distancing-detector".
Under this folder create another subfolders namely pyimagesearch and yolo-coco.
Inside the pyimagesearch folder is the detection.py and social_distancing_config.py scripts which are connected to social_distance_detector.py main python script.
Inside the yolo-coco folder is the coco.names, yolov3.cfg and yolov3.weights COCO labels and YOLO weights and model configuration which are also connected to social_distance_detector.py main python script.
The structure of "social-distancing-detector" folder should look like this.
```
├── pyimagesearch
│   ├── __init__.py
│   ├── detection.py
│   └── social_distancing_config.py
├── yolo-coco
│   ├── coco.names
│   ├── yolov3.cfg
│   └── yolov3.weights
├── output.avi
├── RUN.mp4
└── social_distance_detector.py
```

### 3. Running the Social Distancing Detector
After all files in the "social-distancing-detector" folder has been structured and setup, your social distancing detector is now good to go by doing the following:
1. In the command prompt, change the directory to the exact "social-distancing-detector" folder location by running:
```
C:\Users\hp>cd C:\Users\hp\Downloads\social-distancing-detector
```
2. Now you're in the /social-distancing-detector directory. 
```
C:\Users\hp\Downloads\social-distancing-detector>
```
3. You can now run the social distancing detector in this directory by calling:
 ```
C:\Users\hp\Downloads\social-distancing-detector>python social_distance_detector.py --input RUN.mp4
```
Note: You can call --input 0 or --input 1 if you intend to use your webcam or other connected camera.

4. If you intend to save or record your work while it's displaying, call the folowing:
```
C:\Users\hp\Downloads\social-distancing-detector>python social_distance_detector.py --input RUN.mp4 --output output.avi 
```
Note: The output should be saved in the /social-distancing-detector directory as "output.avi". You can always change the file name to whatever filename you want.

5. If you intend to save or record your work without displaying, call the folowing:
```
C:\Users\hp\Downloads\social-distancing-detector>python social_distance_detector.py --input RUN.mp4 --output output.avi --display 0
```

## Outro
I hope you have enjoyed this quick tutorial. If you have any suggestions, concerns or feedback from this work, please do let me know by hitting me up in my social media accounts:
Facebook: https://www.facebook.com/jdsmooth2j/
LinkedIn: https://www.linkedin.com/in/jmdawa/

Thank you!



