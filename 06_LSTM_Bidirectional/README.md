# 📰 Fake News Detection using Bidirectional LSTM 🚀  

## 🔍 Overview  
This project builds a **Fake News Detection Model** using a **Bidirectional LSTM (BiLSTM)** network — enabling the model to learn from both **past and future word context** for improved accuracy.  
With deep text understanding, the model achieved an impressive **🔥 86% accuracy** on the dataset.  

---

## 🧠 Key Highlights  
- 🧹 **Data Cleaning:** Handled NaN values and removed invalid label entries.  
- 🔤 **Text Preprocessing:** Tokenization, stopword removal, stemming & padding for uniform input.  
- 💬 **Embedding Layer:** Converts text into dense vectors before feeding into BiLSTM.  
- 🔁 **Model Architecture:**  
  - Embedding Layer  
  - **Bidirectional LSTM (128 units)** for dual-context learning  
  - Dense + Sigmoid output for binary classification  
- 📊 **Evaluation Metrics:** Accuracy, Confusion Matrix, and Classification Report  

---

## ⚙️ Tech Stack  
- 🐍 **Python**  
- 🧠 **TensorFlow / Keras**  
- 📈 **Scikit-learn**  
- 🗂️ **Pandas**, **NumPy**, **NLTK**

---

## 📦 Dataset  
- 📰 **Dataset Size:** ~71K news samples (title, text, label)  
- 🔧 Cleaned to remove missing and noisy data  
- 🎯 Labels: 1 → Fake | 0 → Real  

---

## 📊 Results  
| Metric | Value |
|:-------:|:------:|
| 🧠 Model | **Bidirectional LSTM** |
| 🎯 Accuracy | **86%** |
| ⚡ Loss | Decreased steadily without NaN issues |
| 💡 Insight | Capturing bidirectional context significantly boosted performance |

---

## 🌟 Future Enhancements  
- 🧩 Add **Attention Mechanism** for deeper interpretability  
- 💡 Try **Pretrained Embeddings (GloVe / Word2Vec)**  
- 🔁 Experiment with **Stacked BiLSTM** layers  
- 🤖 Explore **Transformer-based models (BERT, RoBERTa)**  

---

## 💻 How to Run  
```bash
pip install tensorflow pandas numpy scikit-learn nltk
python fake_news_bilstm.py
