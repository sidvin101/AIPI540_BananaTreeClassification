# AIPI540_BananaTreeClassification

# Project Description

## Overview

This project uses machine learning to detect banana tree diseases early, helping farmers prevent crop loss.

## Problem  

Banana trees can suffer from diseases that harm yield. We trained a model to classify tree health into four categories:  

Healthy  

Fusarium Wilt  

Natural Leaf Death  

Rhizome Root Issues  

## Dataset  

44,000 images, with augmentations  

Source: [Kaggle Dataset](https://www.kaggle.com/datasets/shuvokumarbasak4004/banana-tree-disease-detection-new-and-update-dataset/data)

Publicly available for research and education

## Approaches

1. Naive Approach  

Always predicts the most common class (baseline test)  

2. Non-Deep Learning (SVM)  

Feature extraction: HOG, LBP, Color Histogram  

Trained an SVM, achieving high accuracy at low cost  

3. Deep Learning (ResNet50)  

Transfer learning with fine-tuning  

High accuracy (~99%) but more computationally expensive  

## Evaluation

Metrics: Accuracy, Precision, Recall, F1 Score, Confusion Matrix  

Robustness Test: Applied adversarial patches to measure impact  

## Contributors

Siddarth Vinnakota  

Rajiv Raman  

Jesse Warren  

Dayeon Kang 

# How to Run

You can either run app.py if your would like to run this locally. Alternatively, the demo can be found through this link: https://aipi540bananatreeclassification.streamlit.app/

Additionally, if you would like to run the deep learning part of the repo, please use the packages in requirements2, as the streamlit uses the non-dl approach and has no access to tensorflow. 
