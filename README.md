# AlexNet and VGG11-Based Image Classification - Performance Analysis and Optimization Trials


<!-- MOTIVATION -->
## Motivation

The motivation behind this project was to explore the effectiveness and adaptability of the AlexNet and VGG11 architectures in the realm of multi-class image classification. By experimenting with various optimization techniques and hyperparameter tuning, the project aimed to evaluate whether advanced methods like gradient accumulation and learning rate scheduling could significantly enhance the model's performance compared to its base configuration. This investigation offers valuable insights into the robustness of AlexNet and the impact of different optimization strategies in deep learning models for image classification.


<!-- ABOUT THE PROJECT -->
## Introduction

This project explores the effectiveness of the AlexNet and VGG11 architectures in multi-class image classification. We employ advanced techniques like gradient accumulation, learning rate scheduling, and experiment with different dropout values, optimizers, and activation functions to gauge performance enhancements.


<p align="right">(<a href="#top">back to top</a>)</p>

## Built With

Here are the awesome tools we used:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-0081C8?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=seaborn&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![splitfolders](https://img.shields.io/badge/splitfolders-0080FF?style=for-the-badge)



<p align="right">(<a href="#top">back to top</a>)</p>


## Datasets

The dataset contains various images of alphabtes and numeric charcacters. The dataset contains 100,800 samples and 36 categories. Each sample is a 28x28 image.

## Key Metrics
- Baseline Accuracy: 91%
- Evaluation Metrics: Precision, Recall, F1-Score, ROC Curve
- Comparative analysis of base and optimized models

## Methodology
1. **Base Model**: Implementation of the AlexNet architecture for multi-class image classification.
2. **Early Stopping**: Incorporated to prevent overfitting.
3. **Performance Testing**: Evaluated using precision, recall, f1-score, and ROC curve.
4. **Optimization Techniques**:
   - Gradient Accumulation
   - Learning Rate Scheduler
5. **Hyperparameter Tuning**:
   - Dropout
   - Optimizers
   - Activation Functions


<!-- CONCLUSION -->
## Conclusion

Contrary to expectations, our extensive testing revealed that the base AlexNet model yielded better performance than its optimized counterparts. This highlights the inherent efficiency of AlexNet in handling multi-class image classification tasks.