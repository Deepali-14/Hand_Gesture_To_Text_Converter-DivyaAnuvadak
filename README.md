# Hand_Gesture_To_Text_Converter-DivyaAnuvadak
![image](https://github.com/Deepali-14/Hand_Gesture_To_Text_Converter-DivyaAnuvadak/assets/90978030/7aaebd7c-7a6e-4e47-9ed7-6e228cc3a520)


# Motivation
“APAJI’s  vision to educate girls, 
why not to extend it to specially-abled!”

-> Some people affected by speech and hearing impairment cannot express their feelings and emotions, hence are not able to communicate with the people. They rely on sign language which most of the people find hard to understand. Because of this, even if they are capable, they lack opportunities. 

-> Thus, we came up with the idea of ‘DivyaAnuvadak’ which takes hand gesture as input and translate it to equivalent text which could be understood by common people. This would further help both our community and our university build a startup to educate specially-abled girls. This would eventually boost up their self-esteem and can make them independent.

-> We are trying to widen Apaji’s(Banasthali Vidyapith University's Founder) vision to educate every girl (specially-abled) that would ultimately help these Shantas to shine too.


# Problem
-> The main problem that the project aims to solve is to reduce the communication gap of speech or hearing impaired people with the normal ones. 


# Solution
-> It converts ISL i.e., Indian Sign Language To corresponding equivalent Text.


# Overall Project Description
-> DivyaAnuvadak, would serve the speech and hearing impaired people by providing their gestures converted to the equivalent text. 

-> It will convert gestures into its corresponding text. The predefined gestures will be stored in the memory and will be compared with the original gesture performed by the user.


# Project Function
1. Capture the gestures made by the user through a web camera
2. Recognizing the gestures through Tensorflow Object Detection API by identifying features.
3. Pre-Processing the captured data.
4. Feeding the data to the model.
5. Predicting the word based on processed model.
6. Selecting the word of highest possibility.
7. Converting the word into text and displaying it on the screen.


# Dependencies
1. cv2
2. os
3. time
4. uuid

   
# Technologies Used
1. Tensorflow
2. Python
3. OpenCV (Open Computer Vision Library)


# IDE (Integrated Development Environment Used)
1. Python Notebook
2. Visual Studio Code


# Steps of building this project
1.  Collecting images for Deep Learning using webcam and OpenCV.
2.	Then label these images for Sign Language Detection using LabelImg tool of Python. 
3.  Further split these images into training and testing datasets.
4.	The next step is to create a model for training and setting up all the paths.
5.	Then create label map for each image, where each label will contain a unique id.
6.	Setup Tensorflow Object Detection pipeline configuration.
7.	Create TF records using Tensorflow API.
8.	Download Tensorflow pretrained models from Tensorflow models.
9.	Copy the model configuration to training folder.
10.	Update this configuration file for Transfer Learning.
11.	Use Transfer Learning to train the Deep Learning model
12.	Train the model by executing the code in terminal.
13.	Final step is to load the model from checkpoints.
14.	Tada! now the model will be able to detect the gestures in real time using OpenCV and convert them to equivalent text.


![image](https://github.com/Deepali-14/Hand_Gesture_To_Text_Converter-DivyaAnuvadak/assets/90978030/401953b2-e98e-4b74-b43e-310835bdebd0)

![image](https://github.com/Deepali-14/Hand_Gesture_To_Text_Converter-DivyaAnuvadak/assets/90978030/4bd7cd62-d146-426a-a766-a9a38c716bba)


# References
1. LabelImg - https://github.com/heartexlabs/labelImg
2. TensorFlow Object Detection API Installation - https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/install.html
3. Tensorflow Models - https://github.com/tensorflow/models



