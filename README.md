# Udacity Data Science Capstone Project

Human Activity Recognition Using Smartphones

## Installations
This project was written in the Anaconda environment and Python 3.7

## Motivation

The purpose of this project was to analyse data generated from smartphone sensors and to build a model that could accurately classify 6 different activity types: walking, walking upstairs, walking downstairs, sitting, standing, and laying.

## Files

This repository contains the following:
- data
    - README.txt -> readme accompanying UCI HAR dataset
    - train.zip -> zip file containing training data
    - test.zip -> zip file containing test data
    - activity_labels.txt
    - features.txt
    - features_info.txt
- (insert jupyter notebook file)
    
## Summary

The following 3 models were attemped and each resulted in accuracy scores of >90%:
- K-nearest Neighbours
- Random Forest
- Support Vector Machine

A 3D visualisation from PCA showed that some activities overlap significantly, indicating the variations in which different individuals perform different activities.

Dimensionality reduction through PCA was shown to be effective whilst maintaining high accuracy.

## Acknowledgements

Davide Anguita, Alessandro Ghio, Luca Oneto, Xavier Parra and Jorge L. Reyes-Ortiz. A Public Domain Dataset for Human Activity Recognition Using Smartphones. 21th European Symposium on Artificial Neural Networks, Computational Intelligence and Machine Learning, ESANN 2013. Bruges, Belgium 24-26 April 2013. 

UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/index.php

Udacity - for setting up the project and course contents.

