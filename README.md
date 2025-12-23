# 🧬 Skin Cancer Classification Using Deep Learning (ISIC Dataset)
## 📌 Project Overview

This project focuses on binary skin cancer classification, distinguishing between benign and malignant skin lesions using dermoscopic images from the ISIC dataset. The goal was to systematically evaluate the performance of multiple Convolutional Neural Network (CNN) architectures and analyze how different image preprocessing techniques impact classification effectiveness.

## 📊 Dataset

Source: International Skin Imaging Collaboration (ISIC)

**https://www.isic-archive.com/**

Classes: Benign, Malignant

Task: Binary image classification

Evaluation Focus: Balanced performance across both classes

## 🔎 Preprocessing Techniques

To enhance feature representation and contrast, the following preprocessing methods were explored:

CLAHE (Contrast Limited Adaptive Histogram Equalization)

Polynomial (x²) Feature Transformation

Standard image normalization and resizing

These techniques were evaluated for their influence on model robustness and class-wise performance.

## 🤖 Models Evaluated

A comparative study was conducted using four widely adopted CNN architectures:

ResNet50

DenseNet121

VGG16

InceptionV3

Each model was trained and evaluated under consistent experimental settings to ensure fair comparison.

## 📈 Evaluation Metrics

Model performance was assessed using:

F1 Score (class-wise)

Accuracy

Precision

Recall

F1-score was emphasized due to its importance in medical classification tasks, where both false positives and false negatives carry significant consequences.

## ✅ Results Summary
Model	Benign F1	Malignant F1
DenseNet121 + CLAHE	0.89	0.89
ResNet50	0.88	0.89
VGG16	0.87	0.87
InceptionV3	Evaluated	Evaluated

DenseNet121 with CLAHE achieved the best balanced performance across both classes

CLAHE consistently improved lesion contrast and feature discriminability

Dense connectivity in DenseNet121 contributed to improved feature reuse and generalization

## 🧠 Key Insights

Preprocessing plays a critical role in medical image classification

DenseNet121 demonstrates superior performance when paired with contrast enhancement

Balanced F1-scores are essential for reliable clinical decision support

Model architecture choice significantly affects class-wise performance

## 🌍 Applications

Computer-aided diagnosis (CAD) systems

Early skin cancer detection

Medical image analysis research

## 🔮 Future Work

Extension to multi-class lesion classification

Integration of explainability techniques (Grad-CAM)

Cross-dataset generalization studies

Lightweight model deployment for clinical use
