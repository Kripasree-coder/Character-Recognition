**Handwritten Digit Recognition using SVC**
This project demonstrates a Handwritten Digit Recognition system using a Support Vector Classifier (SVC). 
The model has achieved an impressive accuracy of 99.11% on the test dataset. 
The digits are classified using the digits dataset, which is inbuilt in the scikit-learn library.

**Overview**
Handwritten digit recognition is a popular application of machine learning and image classification. In this project, we use a Support Vector Classifier (SVC) to classify digits from 0 to 9. The digits dataset contains 8x8 grayscale images representing handwritten digits.

**Dataset**
The dataset used for this project is the digits dataset provided by the sklearn.datasets module. It contains:
1,797 samples of 8x8 images of digits.
Each image is represented as a flattened array of 64 features (pixels).
The dataset includes the corresponding labels (target values) representing the digit in each image.

**Model**
The model used for this task is a Support Vector Classifier (SVC), which is a powerful algorithm for classification tasks. 
We have used the Radial Basis Function (RBF) kernel in this implementation to achieve high accuracy.

**Steps:**
**Data Preprocessing:**
The digits dataset is loaded from sklearn.datasets. The images are flattened into 1D arrays.
**Train-Test Split:**
The dataset is split into training and testing sets.
**Model Training:**
The SVC model is trained on the training set.
**Model Evaluation:**
The model's performance is evaluated on the test set.
