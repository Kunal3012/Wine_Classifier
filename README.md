---

# Deep Learning for Wine Classification

**Author:** Kunal Yadav  
**Email:** mailmekunal2002@gmail.com

## Abstract

Wine classification is a critical task in the viticulture and wine production industry, aiding in quality control and wine type identification. This project leverages the power of deep learning to classify white and red wines based on their intricate chemical attributes. Using a comprehensive dataset sourced from the UCI Machine Learning Repository, we meticulously designed and trained a deep neural network (DNN) model. The achieved results are astounding, with a test accuracy rate of 99.5%. In this report, we delve into the dataset, data preprocessing, model architecture, training process, and comprehensive results, highlighting the potential applications of our model in the wine industry.

## Introduction

Wine classification based on chemical attributes is vital for the wine industry. This project employs deep learning techniques to classify white and red wines using their chemical composition.

## Methods

### Data Preparation

- Combined white and red wine datasets.
- Added a "type" column (0 for white, 1 for red).
- Visualized alcohol content distribution.

### Data Splitting and Scaling

- Split dataset into training and testing sets.
- Applied feature scaling.

### Deep Neural Network (DNN) Model

- Built a DNN model using TensorFlow Keras.
- Achieved high accuracy in classifying wines.

## Results

- DNN Model:
  - Test Accuracy: 99.5%
  - Training Accuracy: 99.7%

### Confusion Matrix

|            | Predicted White Wine | Predicted Red Wine |
|------------|-----------------------|--------------------|
| True White | 1447                  | 1                  |
| True Red   | 8                     | 494                |

## Discussion

The DNN model's exceptional accuracy and minimal misclassifications make it a robust tool for wine classification.

## Conclusion

This project demonstrates the effectiveness of deep learning in accurately classifying white and red wines based on their chemical attributes.

---
