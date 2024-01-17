# Face Detection 

Finding faces (can be single or multiple ) in an image. 

# Overview

Face detection using Haarcascade classifier is a widely-used and efficient approach to identify and locate human faces within images or video streams. This technique 
relies on a machine learning algorithm called Haar cascades, which is particularly adept at recognizing patterns in images. The Haarcascade classifier has proven to be
effective in real-time face detection applications, making it a popular choice in various domains, including computer vision, video surveillance, and facial recognition systems.

# Key Components and Steps

## Haarcascade Classifier: 
The Haarcascade classifier is a pre-trained machine learning model that can recognize specific features of objects, in this case, human faces. It works by employing a set of Haar-like features and a cascading series of classifiers to distinguish between faces and non-faces.

## Training Process: 
The Haarcascade classifier is trained on a large dataset of positive and negative images. Positive images contain faces, while negative images do not. The classifier learns to identify patterns and features that are indicative of the presence of a face during the training process.

## Feature Extraction:
Haar-like features are simple rectangular patterns that are used to represent the characteristics of faces. These features capture information about the distribution of light and dark regions in an image.

## cascade of Classifiers: 
The Haarcascade classifier employs a cascade structure with multiple stages. Each stage consists of a set of weak classifiers that progressively filter out regions of the image that are unlikely to contain a face. This cascade structure contributes to the efficiency of the face detection process.

## Sliding Window Technique:
The classifier uses a sliding window technique to scan through the input image at various scales and positions. At each step, the classifier evaluates the presence of face-like features within the window. If a region passes all stages of the cascade, it is classified as a face.

# Where Use Face Detection

Face Detection is used to collect data for or create dataset for model like face recognition. It is the a step in data collection which with use of  open cv can be used to create datasets

# Real Time Detection
use this peice of code:<br>
![gui](https://github.com/chauhan-mukul/Comment-toxicity-determiner/assets/143337342/e88870e7-4b18-4aa5-b3ce-63b7ae458517)<br>
Result:<br>
![real_time_face_detecitn](https://github.com/chauhan-mukul/Comment-toxicity-determiner/assets/143337342/a7848f1d-11bc-4f16-bace-acc1339206b9)
