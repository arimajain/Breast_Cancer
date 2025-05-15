# 🧠 Breast Cancer Classification using CNN (CancerNet)

A deep learning project built with Python and Keras to classify breast cancer histology images as **benign** or **malignant** using a custom Convolutional Neural Network (CNN) called **CancerNet**.

---

## 📌 Objective

To build a breast cancer classifier on the IDC (Invasive Ductal Carcinoma) dataset that can accurately identify histology image patches as **benign** (no cancer) or **malignant** (cancerous).

---

## 🧬 About IDC

**IDC (Invasive Ductal Carcinoma)** is the most common form of breast cancer, accounting for 80% of all diagnoses. It originates in the milk ducts and spreads to surrounding breast tissue. This project uses histopathology images to detect the presence of IDC.

---

## 🗂️ Dataset

- **Name**: IDC_regular dataset  
- **Source**: [Kaggle – Breast Histopathology Images](https://www.kaggle.com/paultimothymooney/breast-histopathology-images)
- **Images**: 277,524 patches of 50x50 pixels  
  - **Negative (Benign)**: 198,738  
  - **Positive (Malignant/IDC)**: 78,786  
- **Slides**: Extracted from 162 whole-slide images  
- **Magnification**: 40x  
- **Disk Space**: Requires at least 3.02 GB

---


# ✅ Project Conclusion

In this project, we successfully built a deep learning-based breast cancer classifier using a Convolutional Neural Network (CNN) architecture named **CancerNet**. Trained on the IDC (Invasive Ductal Carcinoma) histopathology image dataset, the model demonstrated strong performance in distinguishing between benign and malignant tissue samples.

Key takeaways:

- The model was trained on over **277,000** histology image patches and validated using a confusion matrix and performance metrics such as accuracy, precision, recall, and F1-score.
- **CancerNet** was implemented using **Keras** with a **TensorFlow** backend and trained using well-established deep learning techniques.
- The model achieved high classification accuracy, indicating its potential to assist pathologists in early and reliable detection of breast cancer.

This project showcases the power of deep learning in medical imaging and highlights its practical application in supporting diagnostic workflows for breast cancer.
