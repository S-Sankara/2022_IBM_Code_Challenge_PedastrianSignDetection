<h1 align="center">022_IBM_Code_Challenge_PedestrianSignDetection </h1>

## Problem Statement:
* To create a program to recognize the hand signals provided by pedestrians and take appropriate action on the Autonomous Vehicle. For example,if the pedestrian is showing 'STOP' signal, then the vehicle should decrease the speed and stop.
* Differentiate between road signals and normal message signals. For example, vehicle should clearly understand the difference between 'STOP' signal and a 'HI" signal.

## Presentation : [Google Slides](https://docs.google.com/presentation/d/176ZI5EOF0AXElZLJ9NnMTjSnmssYXgpPsXHF-5kVssk/edit?usp=sharing)

## How it works
* The video is captured with the help of OpenCV. Then keypoints from various elements are extracted using mediapipe.
* These keypoints and landmarks are used to train the new Holistic model.
* By using this model, the signal that the pedestrian is showing is interpreted.

## Contributors
• Sankara Subramanian
• Muhammed Kaif
• Sanjeev
• Arun


## Contributing and Support

Feel free to open a pull request if you can help in improving this project.
