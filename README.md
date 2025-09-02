🐶🐱 Dogs vs Cats Classification using SVM
📌 Project Overview

This project implements a Support Vector Machine (SVM) to classify images of cats and dogs using the Kaggle Dogs vs Cats dataset.
The goal is to understand how traditional ML models like SVM can be applied to image classification tasks.

📂 Dataset

Source: Kaggle Dogs vs Cats

Contains:

25,000 training images (12,500 cats, 12,500 dogs)

12,500 test images (unlabeled, used in Kaggle competition)

Images are in JPG format.
🚀 Steps Implemented

Data Preprocessing

Images resized to 64x64

Converted to grayscale

Flattened into feature vectors

Normalized pixel values (0–1)

Train-Test Split

80% training

20% testing

Model Training

Used SVC from scikit-learn

Tried different kernels (linear, rbf)

Evaluation

Accuracy score

Confusion matrix

Sample predictions

📊 Results

Accuracy: ~70–80% (depends on sample size & kernel)

Linear kernel works decently, but deep learning (CNNs) outperform SVM on raw images.

📌 Future Improvements

Use CNNs (Convolutional Neural Networks) for higher accuracy

Apply data augmentation (rotation, flipping, scaling)

Experiment with feature extraction (HOG, PCA) before SVM

🏆 Acknowledgements

Dataset: Kaggle Dogs vs Cats

Guide: SkillCraft Technology – Internship Task 03
