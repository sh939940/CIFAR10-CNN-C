# CIFAR-10 Image Classification with CNN (Keras)

This project implements a Convolutional Neural Network (CNN) using **Keras** to classify images from the **CIFAR-10 dataset** into 10 categories 
(airplane, car, bird, cat, deer, dog, frog, horse, ship, truck).

---

## 📌 Project Overview
- Built a deep CNN model with multiple convolutional, pooling, and fully connected layers.
- Applied **Batch Normalization** and **Dropout** to improve training stability and reduce overfitting.
- Used **EarlyStopping** to prevent unnecessary training once validation loss stops improving.
- Evaluated the model on the CIFAR-10 test dataset.

---

## ⚙️ Requirements
Install the following packages before running the notebook:

```bash
pip install keras numpy matplotlib pillow scikit-learn
