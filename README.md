# Virtual-AI-Keyboard

INTRODUCTION
This project implements a hand recognition and hand gesture recognition system using OpenCV on Python 2.7. A histogram based approach is used to separate out a hand from the background image. Background cancellation techniques are used to obtain optimum results. The detected hand is then processed and modelled by finding contours and convex hull to recognize finger and palm positions and dimensions. Finally, a gesture object is created from the recognized pattern which is compared to a defined gesture dictionary.

Platform: Python 2.7

Libraries: OpenCV 2.4.8, Numpy

Hardware Requirements: Camera/Webcam
