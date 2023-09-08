# Volume_Contoller
The volume controller is designed by inheriting the concepts of computer vision and utilizes mediapipe framework from google.
The volume of PC can be controlled by gesturing using this repository.
Mediapipe is developed by google and is open to use by everyone
![mp](https://github.com/SrinadhVura/Volume_Contoller/assets/83588454/3b25a4b3-bbc8-4425-87f3-48a0c844e7da)
The above image shows various points that can be detected by mediapipe framework. In this repository to control to volume, I've used the distance between point 8 and 12 i.e., INDEX_FINGER_TIP and MIDDLE_FINGER_TIP
The repository contains two python files.
1. HTrack.py --> It is a module that utilises mediapipe framework, detects the points on hand. Also used to draw hands and detect landmarks on hands.
2. VolCon.py --> It is the file that makes use of HTrack and controlls volume
* pycaw is used to control the system volume
* opencv is used to capture the hand using PC's camera. With the help of opencv the volume bar is drawn on the screen.
