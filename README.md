# 🩺 Skin Cancer Detection using Deep Learning
This repository contains a complete deep learning workflow for **Skin Cancer Detection** using dermoscopic images. The project focuses on building a CNN-based classifier to support early diagnosis of skin cancer through automated image analysis.

---

## 📌 Project Overview
Skin cancer is one of the most common cancers globally, and timely detection drastically improves treatment success. This project implements a **Convolutional Neural Network (CNN)** trained on high-quality dermoscopic images to classify skin cancer as accurately as possible. The goal is to build a reliable automated detection system using modern deep learning practices.

---

## 🚀 Tech Stack Used
- **Python 3**
- **TensorFlow / Keras**
- **Scikit-Learn**
- **OpenCV**
- **NumPy & Pandas**
- **Matplotlib & Seaborn**
- **Jupyter Notebook / Google Colab**

---

## 📂 Dataset Used — HAM10000
The project uses the **HAM10000 (Human Against Machine with 10000 training images)** dataset, one of the most widely used benchmark datasets for skin cancer classification.  
It includes **10,015 dermoscopic images** across **7 skin cancer classes** such as Melanoma, Basal Cell Carcinoma, etc.

### 👉 Dataset Link 
[https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T]


---

## 🧠 Model Architecture
The CNN architecture includes:
- Convolution + ReLU layers  
- MaxPooling layers  
- Batch Normalization  
- Fully Connected Dense Layers  
- Softmax Output Layer  

Additional Improvements:
- **Data Augmentation**
- **Normalization**
- **EarlyStopping & ModelCheckpoint**
- **Learning Rate Scheduler**

---

## 🔧 How to Run the Project

### 1️⃣ Clone this repository
```bash
git clone https://github.com/SriNithya2512/skin-cancer-detection.git
cd skin-cancer-detection


