# Transfer Learning

This project implements a binary image classifier for cats and dogs using **transfer learning**. It includes both **feature extraction** and **fine-tuning** approaches using a pre-trained CNN.

---

## 🧠 Transfer Learning Overview

### 🔹 Feature Extraction  
In this approach, the convolutional base of the pre-trained model is frozen, and only the newly added classifier layers are trained.

- Faster training
- Lower risk of overfitting
- Fewer trainable parameters

---

### 🔹 Fine-Tuning  
In fine-tuning, the top layers of the pre-trained model are unfrozen and retrained alongside the classifier head.

- Higher accuracy potential
- Requires more computing and tuning

---

## 📁 Dataset

- **Source:** Kaggle Dogs vs. Cats  


