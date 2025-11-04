# 🎬 Movie Review Sentiment Analysis using LSTM

A beginner-friendly **Deep Learning project** that predicts whether a movie review is **Positive** or **Negative** using an **LSTM (Long Short-Term Memory)** network trained on the **IMDB Movie Reviews Dataset**.

---

## 🧠 Project Overview

This project demonstrates how Natural Language Processing (NLP) can be combined with Deep Learning to understand the **sentiment** behind text reviews.  
Using **Keras** and the **IMDB dataset**, the model learns to classify reviews into positive or negative sentiments.

---

## ⚙️ Features

✅ Built using **TensorFlow/Keras**  
✅ Trained on the official **IMDB dataset**  
✅ Implements **LSTM** for sequence modeling  
✅ Visualizes training & validation performance  
✅ Includes **Confusion Matrix** for evaluation  
✅ Model saved for later prediction  

---

## 📊 Dataset

The project uses the built-in **IMDB dataset** from `keras.datasets.imdb`.

- Total reviews: 50,000  
- Classes:  
  - `1` → Positive  
  - `0` → Negative  
- Vocabulary size: Top 10,000 words  
- Sequence length (after padding): 200  

---
## 📈 Observation:
The model performs well on training data but shows signs of overfitting on validation data (training accuracy much higher than test accuracy).
Adding Dropout layers and using Bidirectional LSTMs can improve generalization.

---
## 👩🏻‍💻Author:
`Debaswini`
---




 
