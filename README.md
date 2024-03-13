# COSC354-Midterm: Android Malware Detection Project

## Overview
This project focuses on developing machine learning models to detect malware on Android systems. By leveraging a dataset comprising various application behaviors and characteristics, we aim to distinguish between benign and malicious applications. The project explores different machine learning approaches, including Logistic Regression and Feedforward Neural Networks, to identify the most effective strategies for malware detection.

## Objectives
- To understand the behavior and characteristics of Android malware.
- To evaluate the performance of Logistic Regression and Feedforward Neural Networks in detecting Android malware.
- To improve the accuracy and reliability of malware detection models for Android systems.
## Dataset
The dataset used in this project includes features extracted from numerous Android applications, categorized as either benign or malicious based on their behaviors and permissions.

## Models
- Experiment #1: Logistic Regression - Serves as an initial benchmark by employing a straightforward yet powerful classification method.
- Experiment #2: Feedforward Neural Network - Explores the capabilities of a more complex model to capture nonlinear patterns within the data.
## Performance Summary
The models were evaluated based on their F1 scores, balancing precision and recall:

All Positive Baseline: Training - 0.630, Validation - 0.629
Experiment #1 (Logistic Regression): Training - 0.766, Validation - 0.765
Experiment #2 (Feedforward Neural Network): Training - 0.894, Validation - 0.894
