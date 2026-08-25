# 🥗 Train a Salad Detector with TFLite Model Maker

A **TensorFlow Lite Object Detection** project that uses **TensorFlow Lite Model Maker** and transfer learning to train a custom model capable of detecting different salad ingredients in images.

This project demonstrates how a custom object detection model can be trained and converted into a lightweight **TensorFlow Lite (.tflite)** model suitable for deployment on mobile and edge devices.

---

## 🚀 Project Overview

The project uses the **Salads dataset** to train an object detection model that identifies food items using bounding boxes.

The model is trained using **EfficientDet-Lite0** through TensorFlow Lite Model Maker.

### 🥗 Supported Classes

* 🥖 Baked Good
* 🧀 Cheese
* 🥗 Salad
* 🦐 Seafood
* 🍅 Tomato

---

## 🧠 How It Works

```text
Salad Dataset
      ↓
Data Loading & Preprocessing
      ↓
Train / Validation / Test Split
      ↓
Transfer Learning
      ↓
EfficientDet-Lite0
      ↓
Object Detection Model
      ↓
TensorFlow Lite Conversion
      ↓
Mobile / Edge Deployment
```

---

## 🛠️ Technologies Used

| Technology            | Purpose                       |
| --------------------- | ----------------------------- |
| 🐍 Python             | Programming Language          |
| 🧠 TensorFlow         | Deep Learning Framework       |
| 📱 TensorFlow Lite    | Lightweight Model Deployment  |
| 🔧 TFLite Model Maker | Model Training & Conversion   |
| 📓 Jupyter Notebook   | Development Environment       |
| 🖼️ Computer Vision   | Image Object Detection        |
| 🔄 Transfer Learning  | Model Training Optimization   |
| ⚡ EfficientDet-Lite0  | Object Detection Architecture |

---

## 📂 Project Structure

```text
Train-a-salad-detector-with-TFLite-Model-Maker/
│
├── Train a salad detector with TFLite Model Maker.ipynb
│
└── README.md
```

---

## 📓 Notebook

The complete implementation is available in the Jupyter Notebook:

👉 **[Train a Salad Detector with TFLite Model Maker](./Train%20a%20salad%20detector%20with%20TFLite%20Model%20Maker.ipynb)**

The notebook covers:

* Installing required libraries
* Loading the Salads dataset
* Preparing training, validation and test data
* Creating an EfficientDet-Lite0 model
* Training using transfer learning
* Evaluating the object detection model
* Exporting the trained model
* Converting the model to TensorFlow Lite
* Testing object detection on images

---

## 📦 Installation

Install the required packages:

```bash
pip install tflite-model-maker
pip install pycocotools
```

Then install the supporting Python libraries:

```bash
pip install tensorflow numpy matplotlib
```

---

## ▶️ Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/hemant2871/Train-a-salad-detector-with-TFLite-Model-Maker.git
```

### 2. Open the project

```bash
cd Train-a-salad-detector-with-TFLite-Model-Maker
```

### 3. Start Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Train a salad detector with TFLite Model Maker.ipynb
```

and execute the notebook cells.

---

## 🎯 Key Concepts Learned

This project helped demonstrate practical experience with:

* Object Detection
* Computer Vision
* Transfer Learning
* TensorFlow Lite
* EfficientDet
* Dataset Preparation
* Bounding Box Detection
* Model Evaluation
* Model Export
* Edge & Mobile AI

---

## 📱 TensorFlow Lite

The trained object detection model can be exported into the **TensorFlow Lite format**, making it suitable for lightweight inference on devices with limited computational resources.

TensorFlow Lite Model Maker simplifies the process of retraining models with custom datasets using transfer learning.

---

## 👨‍💻 Author

**Hemant Sharma**

GitHub: [@hemant2871](https://github.com/hemant2871)

---

## ⭐ Support

If you found this project useful, consider giving the repository a ⭐ on GitHub.
