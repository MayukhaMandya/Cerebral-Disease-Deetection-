# Cerebral-Disease-Detection- A Pose Estimation Model using BlazePose MediaPipe

This repository contains a Python implementation of a pose estimation model using BlazePose MediaPipe. The model takes input from the webcam or a video file, calculates angles of the body joints, and displays the stage as either "normal" or "effected" depending on the threshold angle. The model also displays the frames per second (FPS) of the video.

Installation:
To run the model, you will need to install the following libraries:

MediaPipe
OpenCV
NumPy


 Fig. Pose Landmarks 

![image](https://user-images.githubusercontent.com/119781075/230920501-5d389e62-b91f-4ada-b8e2-1d791faeb776.png)![image](https://user-images.githubusercontent.com/119781075/230920709-4e4ece79-f610-410b-8dd8-2ec8df844c7b.png)

Model Evaluation:

We evaluated the performance of our model using logistic regression and achieved an accuracy of 98.54%. 
This high accuracy demonstrates the effectiveness of our approach in accurately classifying the data.

Detection Frame:

![image](https://user-images.githubusercontent.com/119781075/230921697-a8a75e81-fef7-4814-8993-d49ba5cb606d.png)

Fig. Model detecting "stage" as Effected 

![image](https://user-images.githubusercontent.com/119781075/230921726-5ea071cd-7ff6-473b-9304-4fd86cb6ed2c.png)

Fig. Model detecting "stage" as Normal 
