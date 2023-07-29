# crime-classification
Crime classification application built using HTML and Flask, powered by ResNet model. This project was conducted as a part of SmartBridge Externship on Artificial Intelligence.
The templates folder contains the html pages, where you can upload an image and the website will predict what crime is occurring in it.
The uploads folder stores all the images uploaded to the 'predict' webpage.
'crime_clf' Jupyter notebook contains data analysis of UCF crime dataset (imported from Kaggle) and trains and tests a ResNet model with test accuracy of 98%.
The model can be saved as 'crime.h5' and used with 'main.py' which runs the application using Flask.
