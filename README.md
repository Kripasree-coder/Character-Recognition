# Handwritten Digit Recognition Using Support Vector Classifier (SVC)

## Project Overview

This project demonstrates a handwritten digit recognition system using a Support Vector Classifier (SVC). The objective is to accurately classify handwritten digits from 0 to 9 using image data. The model is trained and evaluated on the inbuilt digits dataset from Scikit-learn and achieves a test accuracy of approximately **99.11%**.

This project highlights the effectiveness of Support Vector Machines for image classification tasks involving small to medium-sized datasets.

---

## Problem Statement

Given grayscale images of handwritten digits, the goal is to correctly identify the digit represented in each image. This multi-class classification problem is solved using an SVC model with a non-linear kernel.

---

## Dataset Description

The dataset used is the **digits dataset** provided by `sklearn.datasets`.

### Dataset Characteristics

* 1,797 samples of handwritten digits
* Image size: 8 × 8 pixels (grayscale)
* Each image represented as a flattened vector of 64 numerical features
* Target labels: digits from 0 to 9

---

## Tools and Technologies

* Python
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

---

## Model Description

### Algorithm

* Support Vector Classifier (SVC)

### Kernel Used

* Radial Basis Function (RBF)

The RBF kernel enables the model to capture non-linear relationships between pixel values and digit classes, leading to high classification accuracy.

---

## Methodology

### 1. Data Preprocessing

* Loaded the digits dataset from Scikit-learn
* Flattened 8 × 8 images into 1D feature vectors
* Normalized and prepared the data for training

### 2. Train-Test Split

* Divided the dataset into training and testing sets to evaluate generalization performance

### 3. Model Training

* Trained the SVC model on the training dataset

### 4. Model Evaluation

* Evaluated performance on the test set
* Analyzed predictions using accuracy and classification metrics

---

## Results

The trained SVC model achieved an accuracy of approximately **99.11%** on the test dataset, demonstrating excellent performance in handwritten digit classification.

---

## Applications

* Optical character recognition (OCR) systems
* Automated form and document processing
* Postal code and bank cheque digit recognition
* Educational machine learning demonstrations

---

## Conclusion

This project demonstrates how Support Vector Machines can effectively solve image classification problems such as handwritten digit recognition. The high accuracy achieved confirms the suitability of SVC with an RBF kernel for non-linear, multi-class classification tasks.

---

## Future Enhancements

* Hyperparameter tuning using GridSearchCV
* Confusion matrix and misclassification analysis
* Comparison with CNNs and other machine learning models
* Deployment as a real-time digit recognition application

