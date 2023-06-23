# Volume_Contoller
The volume controller is designed by inheriting the concepts of computer vision and utilizes mediapipe framework from google.
The volume of PC can be controlled by gesturing using this repository.
Mediapipe is developed by google and is open to use by everyone
![image](https://github.com/SrinadhVura/Volume_Contoller/assets/83588454/754fdb4a-da41-45a1-be47-bd1db1c243cb)
The above image shows the various points that can be detected by mediapipe framework. In this repository to control to volume, I've used the distance between point 8 and 12 i.e., INDEX_FINGER_TIP and MIDDLE_FINGER_TIP
The repository contains two python files.
1. HTrack.py --> It is a module that utilises mediapipe framework, detects the points on hand
2. VolCon.py --> It is the file that makes use of HTrack and controlls volume
