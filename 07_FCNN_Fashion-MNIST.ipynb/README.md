👗 Fashion MNIST Classification using FCNN

A fully connected neural network (FCNN) built using TensorFlow & Keras to classify images from the Fashion MNIST dataset into 10 fashion categories like T-shirts, trousers, shoes, and bags.

🚀 Project Overview

This project demonstrates how to build and train a Fully Connected Neural Network (FCNN) for multi-class image classification.
It includes:

🖼️ Data visualization

⚙️ Preprocessing and normalization

🧠 Model architecture (Dense layers + Dropout)

📈 Training with validation split

🔍 Performance evaluation with accuracy & loss graphs

🧵 Dataset Details

Dataset: Fashion MNIST

Images: 28 × 28 grayscale

Classes: 10 categories (Clothing & Footwear)

Samples: 60,000 training + 10,000 testing

🏗️ Model Architecture
Layer Type	Details
Input	28×28 grayscale image
Flatten	Converts 2D image → 1D vector (784)
Dense (256)	Activation = ReLU
Dropout (0.3)	Prevents overfitting
Dense (128)	Activation = ReLU
Dropout (0.3)	Prevents overfitting
Dense (10)	Activation = Softmax
⚙️ Training Configuration

Optimizer: Stochastic Gradient Descent (SGD)

Loss Function: Categorical Crossentropy

Metric: Accuracy

Epochs: 20

Validation Split: 0.2

📊 Results
Metric	Value
🧩 Final Test Accuracy	84.33%
💡 Test Loss	0.42

📈 The model shows smooth convergence and no signs of overfitting.

🖼️ Performance Graphs

(From your Colab output)

Left: Training vs Validation Accuracy

Right: Training vs Validation Loss

💬 Conclusion

✅ The model achieved strong classification accuracy on the Fashion MNIST dataset.
⚙️ It successfully learned visual patterns across multiple fashion categories using a simple FCNN.
✨ Future improvement: Try CNN (Convolutional Neural Network) for higher accuracy.

🧠 Tech Stack

Python 🐍

TensorFlow / Keras 🔥

NumPy & Matplotlib 📊

📂 File Structure
FashionMNIST_FCNN/
│
├── FashionMNIST_FCNN.ipynb       # Jupyter Notebook
├── README.md                     # Project Overview
└── requirements.txt (optional)   # Library dependencies

🤝 Author - Akanksha Mishra 
   G-mail id - akankshamishra13022003@gmail.com

Akanksha Mishra
🎓 Executive Post Graduate in Data Science & AI
📧 mishrakanksha13@gmail.com
