# AAI-590 Group-3 Capstone Project

## Object Detection for Unmanned Aerial Vehicles (UAVs)  
The main challenge facing UAVs is maintaining a safe distance from 
obstacles, a task known as sense and avoid (SAA). Despite careful route planning and generally sparse 
airspace, autonomous drones may still unexpectedly encounter airborne or static obstacles in their path. 
The autonomous SAA system for UAVs is responsible for handling situational awareness, decision-
making, and control of the aircraft to execute evasive maneuvers effectively. To address this issue 
various sensing options are available on UAVs, such as radar, LIDAR, passive electro-optical sensors, and 
passive acoustic sensors. However, using visual cameras for the SAA task is appealing due to their 
lightweight and cost-effectiveness (Amazon Prime Air, 2021). 

## Data Source  
The data for this project was sourced from the Airborne Object Tracking Challenge hosted on AI Crowd:  
https://www.aicrowd.com/challenges/airborne-object-tracking-challenge/   
GitHub user VuongTuanKhanh imported those files to Github for easier data manipulation:  
https://github.com/VuongTuanKhanh/Airborne-Object-Detection-and-Tracking  

## Files:  
* AOT_Dataset_EDA.ipynb  
  - Exploratory Data Analysis on 4,943 flight sequences of around 2 minutes each.
* CNN_MODEL.ipynb
  - Convolutional Neural Network Model built and trained from scratch using Keras and Tensorflow.  
* ViT_model.ipynb
  - Vision Transformer Model utilizing a pre-trained ImageNet dataset and fine-tuned on 100 airplane and helicopter images.  

## Methods Used
* Computer Vision
* Machine Learning
* Deep Learning
* Object Detection/Segmentation

## Technologies
* Python
* Hugging Face
* Keras
* Tensorflow
* Pytorch

## Authors:
Carson Edmonds, Patricia Enrique, and Jeremy Krick  
Shiley-Marcos School of Engineering, University of San Diego
