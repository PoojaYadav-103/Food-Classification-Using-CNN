# 🍽️ Food Classification using EfficientNetB0

A Computer Vision project that classifies food images into **101 categories** using **Transfer Learning with EfficientNetB0**. The trained model is converted into **TensorFlow Lite** format and deployed as an Android application for efficient on-device inference.

---

## ✨ Features

* 📷 Food Image Classification
* 🧠 Transfer Learning using EfficientNetB0
* 🔄 Data Augmentation for improved generalization
* 📱 TensorFlow Lite mobile deployment
* 🍕 Supports classification across 101 food categories

---

## 🛠️ Tech Stack

| Technology         | Usage                |
| ------------------ | -------------------- |
| Python             | Programming Language |
| TensorFlow & Keras | Model Development    |
| EfficientNetB0     | Feature Extraction   |
| TensorFlow Lite    | Mobile Deployment    |
| NumPy              | Numerical Operations |
| Matplotlib         | Visualization        |

---

## 📂 Dataset

| Dataset         | Food-101 |
| --------------- | -------- |
| Categories      | 101      |
| Images          | ~101,000 |
| Training Images | 75,750   |
| Test Images     | 25,250   |

Dataset Source:

https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/

---

## 🏗️ Model Pipeline

```text
Input Image
     │
Resize (224×224)
     │
Data Augmentation
     │
EfficientNetB0
     │
Global Average Pooling
     │
Dense Layer (101 Classes)
     │
Softmax Prediction
```

---

## 📈 Performance

| Metric              | Score      |
| ------------------- | ---------- |
| Training Accuracy   | **90%**    |
| Validation Accuracy | **85.75%** |
| Number of Classes   | **101**    |

---

## 📁 Project Structure

```text
FOOD_CLASSIFICATION_USING_CNN/

├── app/
│   └── FoodClassifier.apk
├── models/
│   ├── model.tflite
│   └── tflite_quant_model.tflite
├── notebook/
│   └── efficientnetb0-training.ipynb
├── report/
│   └── MINI_PROJECT.pdf
├── README.md
└── requirements.txt
```

---

## 🚀 Getting Started

```bash
git clone <repository-url>

pip install -r requirements.txt
```

Open the notebook and run the training pipeline to reproduce the results.

---

## 📱 Mobile Deployment

The trained model is exported as a **TensorFlow Lite (.tflite)** model and integrated into an Android application for lightweight food image classification.

---

## 👥 Team

Developed as part of **Mini Project**
Department of Information Technology, IIEST Shibpur.

* Pooja Yadav
* Aparup Ghosh
* Tarun Srivastava

This repository is maintained by **Pooja Yadav** for academic and portfolio purposes.

---

## 📚 References

* Food-101 Dataset (ETH Zurich)
* TensorFlow Documentation
* Keras Documentation
* EfficientNet Research Paper
