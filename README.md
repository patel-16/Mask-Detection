# Mask Detection

## Table of Contents

1. Problem Statement
2. Description
3. Technology used
4. Contributors

## Problem Statement

During these unprecedented times, for the sake of safety of everyone, ensuring the people wear masks at public places becomes utmost critical and 
there should be a simple mechanism for it. Here, with the help of powerful Machine Learning field, we suggest some models which could detect 
whether a person is wearing mask or not.
<!-- from a 64*64 pixel image -->

## Description

- ### Pre-Processing
  All Images were converted to 120 X 100 size and Dimensionality Reduction techniques like PCA and LDA were applied to the them 
- ### Training and Testing
  3 different classifiers were used to train the dataset and test it on testing dataset . Classifiers used were : 1)SVC 2)MLP 3)KNN
- ### Comparision
  Among the classifiers used, SVC classifier was the best followed by MLP classifier and KNN classifier respectively.
- ### Prediction on an unseen image
  On receiving an unseen image, firstly its face area is extracted with the help of Mediapipe framework , followed by feature extraction by 
  PCA/LDA , and then finally feed to the classifiers, which finally detects the mask in the image if present

## Technology Used

- Python
- Sklearn
- Numpy
- Pandas
- Mediapipe Framework

## Contributors

- Patel Darsh Babubhai (B19CSE115)
- Savani Hard Hareshkumar (B19CSE080)
