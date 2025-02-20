# 📌 Adversarial Robustness & Image Classification using VGG16 

This repository contains a deep learning experiment focused on image classification and adversarial robustness testing using a VGG16-based model. The goal is to classify images into Benign, Malignant, and Normal categories while assessing the model’s vulnerability to adversarial attacks.

# 📁 Project Overview
## 🔹 Key Features
- Image Classification: Trained a VGG16 model for medical image classification.
- Adversarial Robustness Testing: Evaluated the model against adversarial attacks.
- Model Selection & Evaluation: Chose the best model based on validation accuracy.
- Performance Metrics:
    - Clean test set accuracy: ~53.85%
    - Poisoned test set accuracy: 0.00% (complete failure under adversarial conditions).
 

# 🚀 Results & Observations

- The model achieved a moderate accuracy on clean test data.
- The adversarially poisoned test set accuracy dropped to 0%, showing a complete failure against attacks.
- The model misclassified malignant images as benign in adversarial scenarios.
