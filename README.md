<h1 align="center"> 2022_IBM_Code_Challenge_PedestrianSignDetection </h1>


## Problem Statement:
* To create a program to recognize the hand signals provided by pedestrians and take appropriate action on the Autonomous Vehicle. For example,if the pedestrian is showing 'STOP' signal, then the vehicle should decrease the speed and stop.
* Differentiate between road signals and normal message signals. For example, vehicle should clearly understand the difference between 'STOP' signal and a 'HI" signal.

## How it works
* The video is captured with the help of OpenCV. Then keypoints from various elements are extracted using mediapipe.
* These keypoints and landmarks are used to train the new model.
* By using this model, the signal that the pedestrian is showing is interpreted.
### Presentation : [Google Slides](https://docs.google.com/presentation/d/176ZI5EOF0AXElZLJ9NnMTjSnmssYXgpPsXHF-5kVssk/edit?usp=sharing)

## Architecture
### Import and Install Dependencies
* Importing the dependencies that are used in this code.

### Extract Keypoint Values
* Extracting values of keypoints from hands and faces.

### Setup Folders for Collection
* The folders are created that are useful for data collection.

### Collect Keypoint Values for Training and Testing
* The collected keypoints are converted into numpy array which is useful for training.

### Preprocess Data and Create Labels and Features
* The Data which is collected are preprocessed and assign the labels.

### Build and Train LSTM Neural Network
* Build the LSTM Neural Network and used for training.

### Evaluation using Confusion Matrix and Accuracy
* Evaluation of model by Confusion Matrix and Accuracy.

### Test in Real Time
* Testing in real time to evaluate results.

## Personas of the System
* Automotives,emergency responders and autonomous vehicles.

## Screenshots

![Screenshot (252)](https://user-images.githubusercontent.com/65020263/167149582-dde78c57-20ec-4059-b8dc-725f341520e8.png)
![Screenshot (248)](https://user-images.githubusercontent.com/65020263/167150666-e4df0efd-9c92-4d42-b92a-58501836f2cf.png)
![Screenshot (256)](https://user-images.githubusercontent.com/65020263/167148414-3c4635ac-5d1d-4a4e-99dc-e8185757b48d.png)
![Screenshot (255)](https://user-images.githubusercontent.com/65020263/167148423-95be6e89-a738-4123-9223-c6a354c37d1b.png)



## Contributors
* [S Sankara Subramanian](https://github.com/S-Sankara) 
* [Muhammed Kaif](https://github.com/m25kaif)
* [Sanjeev Kumar Upadhyay](https://github.com/Sanjeevkrup)
* [Arun](https://github.com/Arunsasi07)

## Contributing and Support

Feel free to open a pull request if you can help in improving this project.


## License
Code released under the [AGPL](LICENSE)
