# Face-Emotion-and-Gender-Recognition

## Abstract

This project includes data-gathering, data-preprocessing, and employing supervised and unsupervised methods.

## Data Preprocessing

Data preprocessing encompasses cleaning data and dealing with missing values.
We took three approaches when dealing with missing values. 
  * Removing all the missing values
  * Replacing the missing values with their corresponding column's mean.
  * Utilizing the combination of the removing and replacing.
  
  
Also, we make use of a dimentionality reduction method named PCA in order to keep more abstarct dimentions of data.

Moreover, we upsamle the data beglonging to females to equilize the number of samples in the both male and female data.

## Unsupervised learning

As for the unsupervised learning, we make use of Kmeans++ for the clustering purpose.
Also we tried to find a meaningful reasoning for data in each cluster by altering the number of clustres.
A case in point is for 2 clusters which may probably have a similar disturbution per cluster as the data belonging to females and males.









