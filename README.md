# 🧠 Lip Reading with Dual-Input 3D CNN  
**Visual Speech Recognition using Deep Learning**

---

## 📌 Overview
This project implements a deep learning-based lip reading system that recognizes spoken words from silent video sequences. A custom dual-input 3D Convolutional Neural Network (3D CNN) was designed to enhance visual speech recognition accuracy.

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Frameworks & Libraries:** TensorFlow, Keras, OpenCV, NumPy, Scikit-learn  
- **Model:** Dual-Input 3D CNN  
- **Environment:** Google Colab / Jupyter Notebook  

---

## 📁 Dataset
- A custom dataset was curated from publicly available lip reading datasets.
- Each sample consists of 22 consecutive video frames of lip movements representing a single spoken word.

### 📊 Data Distribution
![Data Distribution](https://github.com/user-attachments/assets/344881a5-4d03-4d30-b53d-9f18c025b624)

---

## 🧠 Model Architecture
A dual-path 3D CNN processes two parallel inputs from the same video to capture complementary spatiotemporal features. The outputs are concatenated before being passed to fully connected layers for classification.

![Model Architecture](https://github.com/user-attachments/assets/29277538-5eb8-481d-a20c-8b2b1df5867c)

---

## 📈 Results

### 🔍 Training & Validation Accuracy / Loss
- The model was trained and validated on the custom dataset using categorical cross-entropy loss and accuracy metrics.
- Demonstrated consistent performance and improved generalization.

![Training and Validation Accuracy/Loss](https://github.com/user-attachments/assets/90eedf0b-ab17-4773-8ec9-c88bb2c732c2)

---

## ✅ Key Features
- Dual-input 3D CNN design for richer feature extraction  
- Preprocessing pipeline for frame alignment and normalization  
- Achieved high accuracy and F1 scores on the test set  
- Visualizations for model performance and training dynamics  

---
