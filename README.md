# Deep Learning Homework 2024

This repository contains the Jupyter notebooks developed for the two assignments of the **Artificial Neural Networks and Deep Learning** course, taught by Professors Matteucci and Boracchi at **Politecnico di Milano**.

## Homework 1: White Blood Cell Classification

The objective of this assignment is to classify **96x96 RGB images** of blood cells into one of **eight distinct classes**, each representing a specific cell state. This is a **multi-class classification problem**, where the goal is to correctly assign a class label to each image.

![Class Distribution](https://github.com/GabrieleSinge/Deep-Learning-Homework-2024-/blob/main/classes.png)

### Methodology
We developed a **Convolutional Neural Network (CNN)** based on the **EfficientNetV2Small backbone**, incorporating additional regularization layers to improve the model's generalization capabilities. Key steps in our approach included:

- **Image Augmentation**: Applied various augmentation techniques to increase the diversity of training samples and enhance robustness.
- **Fine-Tuning**: Fine-tuned the pre-trained EfficientNetV2Small model to optimize its performance for this specific dataset.
- **Data Balancing**: Addressed the class imbalance issue (with a 0.36 ratio between the smallest and largest classes) using an oversampling technique to ensure better accuracy and performance.

### Results
- Achieved an accuracy of **0.90** during the development phase.
- Results for the final phase are pending and will be updated shortly.
