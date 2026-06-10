# 🍎 Fruit Classifier — Deep Learning Project
---
A deep learning project that classifies 10 types of fruits using CNNs and Transfer Learning!
Built while studying Chapter 14 of *Hands-On Machine Learning* by Aurélien Géron 📖✨
the dataset is from: https://www.kaggle.com/datasets/karimabdulnabi/fruit-classification10-class
---

## 🍓 What fruits can it recognize?
Apple 🍎 | Orange 🍊 | Avocado 🥑 | Kiwi 🥝 | Mango 🥭  
Pineapple 🍍 | Strawberry 🍓 | Banana 🍌 | Cherry 🍒 | Watermelon 🍉

---

## 🌱 Project Journey — 4 Stages

### Stage 1 — CNN from Scratch
Built a custom Convolutional Neural Network from scratch!
- Learned about Conv2D, filters, kernel size, MaxPooling, and Dropout
- Result: **64% training accuracy / 46% validation accuracy**

### Stage 2 — Data Augmentation
Added random flips, rotations, and contrast changes to fight overfitting!
- The model now sees new variations of each image every epoch
- Result: reduced overfitting gap 🎯

### Stage 3 — Transfer Learning 🚀
Used MobileNetV2 pretrained on 1.2 million ImageNet images!
- Froze the base model and only trained the final layers
- Result: **98% training accuracy / 70% validation accuracy**

### Stage 4 — Fine Tuning
Unfroze the top 30 layers of MobileNetV2 and let them adapt to our fruits!
- Used a tiny learning rate (1e-5) to avoid destroying pretrained weights
- Pushed accuracy even further 🍉

---


