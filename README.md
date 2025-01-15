# Rice Plant Disease Detection Using Deep Learning

## Overview
This project focuses on early and accurate detection of rice plant diseases using deep learning. Early detection is crucial to minimizing crop losses and ensuring sustainable rice production. The study employs three deep learning models—EfficientNetB1, ResNet50, and VGG16—to classify rice plant images into different disease categories with high accuracy.

## Table of Contents
- [Introduction](#introduction)
- [Objectives](#objectives)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Scope](#future-scope)
- [Installation and Usage](#installation-and-usage)
- [References](#references)

## Introduction
Rice is a staple crop worldwide, but its productivity is frequently hindered by diseases. This project leverages artificial intelligence (AI) and deep learning techniques to detect rice plant diseases efficiently and accurately. The models were trained on a dataset comprising 4,452 images of rice plants, covering nine disease classes and healthy plants.

## Dataset
Link: https://drive.google.com/drive/folders/1bFvV6NCikCmZxcZk7dPr8kslW7f0trub

## Objectives
- Develop a deep learning model for rice plant disease detection.
- Preprocess a dataset of rice plant images to enhance quality and consistency.
- Train and evaluate models on the dataset.
- Deploy the best-performing model for real-time inference.

## Methodology
1. **Data Collection**: Images of rice plants were collected from agricultural organizations and online repositories.
2. **Data Preprocessing**: Techniques such as resizing, normalization, and augmentation were applied to improve data quality.
3. **Model Training**: EfficientNetB1, ResNet50, and VGG16 were used to classify diseases, with training optimized through hyperparameter tuning.
4. **Evaluation Metrics**: Accuracy, precision, recall, F1-score, and confusion matrices were used to evaluate performance.

## Results
- **EfficientNetB1**: Achieved the highest accuracy of **96.88%**.
- **VGG16**: Achieved an accuracy of **93.97%**.
- **ResNet50**: Achieved an accuracy of **92.63%**.

The EfficientNetB1 model demonstrated superior performance in terms of accuracy, sensitivity, and specificity, making it the most effective model for rice plant disease detection.

## Conclusion
The study successfully developed a deep learning-based system for rice plant disease detection. EfficientNetB1 proved to be the best-performing model, showcasing its ability to accurately classify diseases and healthy plants. This technology has the potential to revolutionize disease management in agriculture.

## Future Scope
- Integration of the model into mobile applications or on-field sensors for real-time detection.
- Development of ensemble methods for improved robustness.
- Expansion of the dataset with diverse samples to enhance generalization across different regions and conditions.

## Installation and Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/YourGitHubUsername/rice-plant-disease-detection.git
