## LeftOverLove - Food Quality Detector
    We are creating a projects on deep learning in Semester V.the project is a classification model used to classify the fruits based on it's quality as 'Fresh' or 'Rotten'.

## A CNN based classifier to differentiate between rotten and fresh, apples, bananas and oranges.

   Detecting the rotten fruits become significant in the agricultural industry. Usually, the classification of fresh and rotten fruits is carried by humans is not effectual for the fruit farmers. Human beings will become tired after doing the same task multiple times, but machines do not. Thus, the project proposes an approach to reduce human efforts, reduce the cost and time for production by identifying the defects in the fruits in the agricultural industry. If we do not detect those defects, those defected fruits may contaminate good fruits. Hence, we proposed a model to avoid the spread of rottenness. 
   
   The proposed model classifies the fresh fruits and rotten fruits from the input fruit images. In this work, we have used three types of fruits, such as apple, banana, and oranges. A Convolutional Neural Network (CNN) is used for extracting the features from input fruit images, and Softmax is used to classify the images into fresh and rotten fruits. The data is extracted from various sources and produces an accuracy of 93.78%. The results showed that the proposed CNN model can effectively classify the fresh fruits and rotten fruits. In the proposed work, we inspected the transfer learning methods in the classification of fresh and rotten fruits. The performance of the proposed CNN model outperforms the transfer learning models and the state of art methods.

## Steps for using it
    1. Download the static, templets and app packages and store them under one directory
    2. Open command prompt and choose the directory where you stored the above packages
    3. Execute python app.py
    4. Copy the link given in output and paste it on your default browser
    5. Upload the image and test it!

## Description
    The Food Quality Detector is a cutting-edge, web-based application aimed at enhancing customer trust and satisfaction within the hyperlocal food delivery market. Utilizing a Convolutional Neural Network (CNN) model built with TensorFlow, this AI-powered tool efficiently addresses food quality complaints by allowing users to upload images of their food for real-time quality assessment. This initiative not only streamlines the complaint resolution process but also provides valuable feedback to partner restaurants, ultimately reducing churn and fostering a more trustworthy service environment. The frontend is developed using React, offering a user-friendly interface, while the backend is powered by Django REST Framework to handle image processing and prediction.

## Features
    1. Image upload functionality for food quality analysis.
    2. Real-time image preview before submission.
    3. Deep Learning model for accurate classification of food quality.
    4. Responsive web interface for a seamless experience across various devices.

## Backend Setup
    Create a virtual environment and activate it:
    1. python -m venv venv
    2. venv\Scripts\activate
    3. python app.py
    4. Copy the link shown in output ( http://127.0.0.1:5000 ).
    5. Paste the link to access the frontend

## Dataset - Kaggle
    1. https://www.kaggle.com/datasets/swoyam2609/fresh-and-stale-classification