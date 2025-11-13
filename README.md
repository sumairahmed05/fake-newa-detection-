# 📰 Fake News Detection using ANN (Artificial Neural Network)

This project detects whether a news article is **Fake** or **Real** using **TF-IDF** and an **Artificial Neural Network (ANN)** model built in Python.

---

## 🚀 Overview
Fake news is a major issue in today’s world.  
This project helps classify news articles based on their content using machine learning techniques.

---

## 🧠 Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- TF-IDF Vectorizer  

---

## 📂 Dataset
Dataset used: **fake_or_real_news.csv**

It contains two columns:  
- `text` → News content  
- `label` → Fake / Real  

---

## ⚙️ Steps in Project
1. **Load Dataset**
2. **Data Cleaning**
3. **Text Vectorization** using TF-IDF
4. **Model Building** (ANN)
5. **Model Training & Evaluation**
6. **Testing Custom News**

---

## 🧩 Model Architecture
- Input Layer → TF-IDF features  
- Hidden Layer 1 → Dense(128), Activation = ReLU  
- Hidden Layer 2 → Dense(64), Activation = ReLU  
- Output Layer → Dense(1), Activation = Sigmoid  

**Optimizer:** Adam  
**Loss Function:** Binary Crossentropy  
**Accuracy:** ~90%  

---

## 🧾 Example Code
```python
print(predict_news("Aliens landed on Mars today!"))
print(predict_news("Government launches new health policy."))
