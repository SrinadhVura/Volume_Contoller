# Volume_Contoller
The volume controller is designed by inheriting the concepts of computer vision and utilizes mediapipe framework from google.
The volume of PC can be controlled by gesturing using this repository.
Mediapipe is developed by google and is open to use by everyone

The repository contains two python files.
1. HTrack.py --> It is a module that utilises mediapipe framework, detects the points on hand. Also used to draw hands and detect landmarks on hands.
2. VolCon.py --> It is the file that makes use of HTrack and controlls volume
* pycaw is used to control the system volume
* opencv is used to capture the hand using PC's camera. With the help of opencv the volume bar is drawn on the screen.
