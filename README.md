# Cotton Leaf Disease Detection using Transfer Learning and Traditional Classifiers

This project proposes a hybrid machine learning approach for classifying cotton leaf diseases using deep feature extraction via a pre-trained VGG16 model and classification using traditional algorithms — Random Forest and Support Vector Machine (SVM).

Developed as a capstone project for the B.Tech Computer Science programme at Vellore Institute of Technology, Chennai.

---

## Abstract

Cotton is one of India’s most important cash crops, and early detection of diseases in cotton leaves is vital for maintaining crop quality and yield. This project implements a two-step framework:

1. **Deep Feature Extraction** using VGG16 Convolutional Neural Network (CNN)  
2. **Disease Classification** using Random Forest and Support Vector Machine (SVM)

With over 1500 cotton leaf images across 4 classes (Curl Virus, Fusarium Wilt, Bacterial Blight, and Healthy), the model achieved **98.3% accuracy (RF)** and **99.3% accuracy (SVM)**.

---

## Dataset

- Total images: 1,592  
- Classes:
  - Curl Virus
  - Fusarium Wilt
  - Bacterial Blight
  - Healthy Leaves

Images were resized, normalized, and fed through VGG16 for feature extraction. The final classification was performed using Random Forest and SVM classifiers.

---

## Tools and Libraries

- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy, Pandas
- Spyder IDE

---

## Results

| Classifier     | Accuracy | Precision | F1 Score |
|----------------|----------|-----------|----------|
| Random Forest  | 98.29%   | 98.33%    | 98.29%   |
| SVM            | 99.31%   | 99.31%    | 99.31%   |

Confusion matrices were also generated to evaluate misclassifications.

---



