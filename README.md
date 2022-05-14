# Hand-Tracking-Module
The code captures frames using a web camera (tested on windows camera) and outputs a video with the schematic scaling of all the fingers. In the video, there will be a number of dots that are connected to each other spanning all over the hand. Works for multiple hands.

This project is written in Python 3.8.10. The following libraries are used in this project and necessary to be add to your computer:
•	Time - usually comes with Python 3.8.10 
•	cv2 (4.5.5) -  https://pypi.org/project/opencv-python/
•	 Mediapipe (0.8.10) -  https://google.github.io/mediapipe/ 

The code is consisting of a single file and can be executed from the commandline or terminal by calling python HandTrackingMin.py
When running the python file, you can expect to see the real time frame from your camera with a bounding rectangular framing your hand. The bounding rectangular will contain red circles corresponding to the fingertips and finger webbing. The centre mass of your hand will also appear in the bounding rectangular. A number on the upper left side of the frame corresponds to the number of frame rates in real time.

To increase accuracy of the gesture recognition, it is recommended to run the code in a bright light room. Additionally, this code can analyse multiple hands, and the hands needs to be in front of the camera for better recognition.

References: 
cv2 documentation  https://pypi.org/project/opencv-python/ 
Mediapipe documentation  https://google.github.io/mediapipe/

For any question related to the code please contact via email: arnabroy770@gmail.com

Arnab Kumar Roy
