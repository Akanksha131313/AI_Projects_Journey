📖 Project Description

This project focuses on building, training, and evaluating a Fully Connected Neural Network (FCNN) to classify images from the Fashion MNIST dataset.
It demonstrates complete post-modelling steps including data preparation, visualization, model training with TensorBoard, evaluation, and model saving/loading verification.
The project highlights the importance of callbacks, accuracy analysis, and TensorBoard visualizations for performance monitoring.

🚀 Objectives

🧩 Load and visualize the Fashion MNIST dataset

🧼 Normalize image data between 0–1

🔢 Convert labels to categorical format for multi-class classification

🧠 Build a Neural Network using TensorFlow and Keras

⚙️ Train the model with callbacks (TensorBoard)

📊 Evaluate model performance and visualize results

💾 Save & Reload the model to verify architecture and parameters

🧩 Model Summary
Layer Type	Activation	Description
Flatten	—	Converts 28×28 images into 1D array
Dense (512)	ReLU 🔥	First hidden layer
Dense (256)	ReLU 🔥	Second hidden layer
Dense (128)	ReLU 🔥	Third hidden layer
Dense (10)	Softmax 🎯	Output layer for 10 categories
📊 Results
Loaded Model Accuracy: 88.36%
Loss: 0.4039


📈 Training Visualization:

Training accuracy increased steadily

Validation accuracy remained stable with slight overfitting

Loss curve indicates smooth learning and convergence

🪶 Conclusion

✅ The FCNN model was successfully trained and evaluated on the Fashion MNIST dataset.
It achieved 88% validation accuracy, showing strong learning performance.
TensorBoard and plotted curves provided clear insights into the model’s learning process.
The model was saved and reloaded successfully, maintaining performance consistency.

📁 Recommended Folder Structure
AI_Projects_Journey/
│
├── 08_Fashion-MNIST_Post-Modelling.ipynb
├── fashion_mnist_model.h5
├── logs/
│   └── fit/
│
├── README.md
└── requirements.txt
