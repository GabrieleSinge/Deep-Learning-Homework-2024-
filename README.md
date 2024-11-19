# Deep Learning Homework 2024

This repository contains the Jupyter notebooks developed for the two assignments of the **Artificial Neural Networks and Deep Learning** course, taught by Professors Matteucci and Boracchi at **Politecnico di Milano**.

## Homework 1: White Blood Cell Classification

The objective of this assignment is to classify **96x96 RGB images** of blood cells into one of **eight distinct classes**, each representing a specific cell state. This is a **multi-class classification problem**, where the goal is to correctly assign a class label to each image.

![Class Distribution](https://github.com/GabrieleSinge/Deep-Learning-Homework-2024-/blob/main/classes.png)

### Methodology
We trained a **Convolutional Neural Network (CNN)** using the **EfficientNetV2Small backbone**, combined with additional regularization layers to improve generalization. Key steps included:

- **Image Augmentation**: Applied various augmentation techniques to enhance the robustness of the model.
- **Fine-Tuning**: Fine-tuned the pre-trained EfficientNetV2Small model to adapt it to the specific dataset.

### Results
- Achieved an accuracy of **0.90** during the development phase.
- Final phase results are pending and will be updated soon.
