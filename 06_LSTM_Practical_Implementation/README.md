# 📰 Fake News Detection using LSTM 🚀  

## 🔍 Overview  
This project builds a **Deep Learning model (LSTM)** to detect **Fake vs. Real news** headlines.  
It uses **text preprocessing**, **word embeddings**, and a **Sequential LSTM model** for binary classification.  

---

## 🧠 Key Steps  
- 🧹 **Data Cleaning:** Removed missing values and non-numeric labels.  
- 🔤 **Text Preprocessing:** Tokenization, stopword removal, and stemming.  
- 💬 **Word Embedding:** Used Keras `Embedding` layer with padded sequences.  
- 🔁 **Model Architecture:**  
  - Embedding Layer  
  - LSTM Layer (128 units)  
  - Dense Output (Sigmoid activation)  
- 📊 **Evaluation:** Accuracy, Confusion Matrix & Classification Report.  

---

## ⚙️ Tech Stack  
- 🐍 Python  
- 🧠 TensorFlow / Keras  
- 📈 Scikit-learn  
- 🗂️ Pandas, NumPy, NLTK  

---

## 📦 Dataset  
- Contains ~71k news samples (titles + text + labels).  
- Preprocessed to remove null and invalid entries.  

---

## 🧾 Results  
📉 **Model Accuracy:** ~50% (Baseline LSTM)  
⚡ Can be improved by using Bidirectional LSTM or pretrained embeddings (Word2Vec / GloVe).  

---

## 🌟 Future Enhancements  
- ✅ Implement **Bidirectional LSTM**  
- ✅ Use **Pretrained Embeddings (GloVe)**  
- ✅ Try **Attention Mechanism** for better context understanding  

---

## 💻 How to Run  
```bash
pip install tensorflow pandas numpy scikit-learn nltk
python fake_news_lstm.py
