# 🐾 Cat vs Dog Classification using VGG16 (Transfer Learning)

## 📘 **Overview**
This project demonstrates how to use **Transfer Learning** with the pre-trained **VGG16** model to classify images of cats and dogs.  
Instead of training from scratch, the convolutional layers of VGG16 are reused for **feature extraction**, while new dense layers are added for classification.

---

## 🎯 **Objectives**
✅ Use VGG16 as a feature extractor (without top layers)  
✅ Resize and preprocess input images (150x150)  
✅ Apply data augmentation for better generalization  
✅ Add and train custom dense layers for classification  
✅ Save and reload the trained model for verification  

---

## 🧠 **Model Summary**
- **Base Model:** VGG16 (ImageNet weights, frozen layers)  
- **Added Layers:** Flatten → Dense(256, ReLU) → Dropout(0.5) → Dense(1, Sigmoid)  
- **Optimizer:** SGD (lr=0.001, momentum=0.9)  
- **Loss Function:** Binary Crossentropy  
- **Metric:** Accuracy  

---

## 📊 **Results**
| Metric | Score |
|:-------|:------:|
| ✅ Accuracy | **90.93%** |
| 📉 Loss | **0.2173** |

> The model achieved **high accuracy** in classifying cat and dog images, confirming the strength of transfer learning.

---

## 💾 **Model Operations**
- ✅ Model trained and validated successfully  
- 💾 Saved as `vgg16_cats_dogs.h5`  
- 🔁 Reloaded and re-evaluated with consistent accuracy  

---

## 🧩 **Technologies Used**
- TensorFlow / Keras  
- TensorFlow Datasets (`cats_vs_dogs`)  
- VGG16 (Pre-trained on ImageNet)  
- Python 3  

---

## 🚀 **Conclusion**
Transfer Learning with **VGG16** provides strong feature extraction capability and leads to high accuracy with limited training data.  
The final model demonstrates excellent performance and reusability.

---

## 📂 **File Name**
`VGG16_Cats_vs_Dogs_TransferLearning.ipynb`

---

### ✨ Author - Akanksha Mishra
