# 🔠 **Word Embedding Techniques using Keras**

## 📘 **Project Description**
...>This project demonstrates **Word Embedding Techniques** using the **Keras Embedding Layer**.  
...>It covers steps from **One-Hot Encoding → Padding → Word Embedding Representation**,  showing how words are converted into dense numerical vectors that capture meaning.

---

## 🚀 **Steps Covered**
1️⃣ **Sentence Tokenization** — Converting sentences into words  
2️⃣ **One-Hot Encoding** — Assigning unique numbers to words  
3️⃣ **Padding Sequences** — Making all sentences of equal length  
4️⃣ **Word Embedding Layer** — Mapping words to dense 10-dimensional vectors  
5️⃣ **Prediction & Output** — Generating vector representation for each word  

---

## 🧠 **Key Parameters**
- 🧩 `voc_size = 500` → Total unique words  
- 📏 `sent_length = 8` → Fixed input length after padding  
- 📊 `embedding_dim = 10` → Size of each word vector  
- ⚙️ `optimizer = 'adam'` and `loss = 'mse'`

---

## 📈 **Sample Output**
```
Layer (type)           Output Shape        Param #
-------------------------------------------------
embedding (Embedding)  (None, 8, 10)       5,000
-------------------------------------------------
Total params: 5,000 (19.53 KB)
Trainable params: 5,000 (19.53 KB)
Non-trainable params: 0 (0.00 B)
```

---

## 🎯 **Result**
Each word is represented as a dense 10-dimensional vector,  
allowing the model to understand **semantic relationships** between words.

---

## 🧰 **Libraries Used**
- 🐍 Python  
- 💫 TensorFlow / Keras  
- 🔢 NumPy  

---

## ✨ **Author**
👩‍💻 *Akanksha Mishra*  
“Exploring NLP step-by-step — from tokens to meaning!”

