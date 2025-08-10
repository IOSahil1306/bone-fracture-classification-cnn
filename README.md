# 🦴 Bone Fracture Classification using Convolutional Neural Networks (CNN)

## 📌 Project Overview
This project implements a Convolutional Neural Network (CNN) to classify **bone X-ray images** as fractured or healthy.  
It uses deep learning to assist in **medical imaging diagnosis**, potentially helping radiologists detect fractures faster and more accurately.

The model is trained on the [Bone Fracture Dataset from Hugging face],[https://huggingface.co/datasets/IOSahil2003/X-ray/tree/main], with preprocessing, augmentation, and CNN architecture tuning for optimal performance.

## 🛠️ Tech Stack
- **Language:** Python 3.x
- **Libraries:** TensorFlow/Keras, NumPy, Matplotlib, OpenCV, Scikit-learn
- **Tools:** Jupyter Notebook, Kaggle, Git/GitHub

---

## 📊 Dataset
- **Source:** Kaggle – Bone Fracture X-ray dataset
- **Size:** ~5000 images (fractured & healthy)
- **Format:** JPEG images, various resolutions
- **Preprocessing:**
  - Image resizing to `224x224`
  - Normalization
  - Augmentation (rotation, zoom, flip)
