# 🖼️ CIFAR-10 Image Classification using CNN

This project builds a **Convolutional Neural Network (CNN)** model to classify images from the CIFAR-10 dataset into 10 categories.

## 📂 Dataset
- **Name:** CIFAR-10  
- **Images:** 60,000 color images (32x32 pixels)  
- **Classes:** airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck  
- **Loaded via:** `tensorflow.keras.datasets.cifar10`

## 🧩 Model Architecture
- Convolutional Layers (feature extraction)  
- MaxPooling Layers (downsampling)  
- Dropout (to prevent overfitting)  
- Fully Connected Dense Layers  
- Softmax Activation (for 10-class output)

## 🧠 Training Details
- Optimizer: Adam  
- Loss Function: Categorical Crossentropy  
- Epochs: XX  
- Batch Size: XX  

## 📈 Results
- Training Accuracy: ~XX%  
- Test Accuracy: ~XX%  
- Observations: Model performs well, with minor confusion between similar classes (e.g., cat vs dog).

## 🧰 Libraries Used
- TensorFlow / Keras  
- NumPy, Matplotlib  
- Seaborn (for visualization)

---

📸 *This project improved my understanding of CNNs and image classification tasks.*
