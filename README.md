# Text Classification for Topic & Readability Analysis 

This project explores two machine learning models to classify website content by topic and readability using a single notebook in Google Colab. It demonstrates how SVM and LSTM models can automate editorial judgments — while also highlighting the ethical risks involved.

---

## 📌 Project Overview

- **Task 1**: Classify paragraphs into 5 topics using an SVM and TF-IDF features  
- **Task 2**: Classify paragraphs as clear or unclear using an LSTM model with both textual and numerical features

---

## 🛠️ Tech Stack

- Google Colab (Python 3)  
- scikit-learn (SVM, metrics, GridSearchCV)  
- Keras (LSTM model, embedding, sequence padding)  
- Pandas, NumPy  

---

## 📂 Files Included

- `Code.ipynb`: Main notebook with both tasks — preprocessing, model building, and evaluation  
- `Dataset.csv`: Input dataset containing text, labels, and extracted features  
- `Report.pdf`: Project report with methodology and analysis

---

## 🚀 How to Use

1. Open `code.ipynb` in [Google Colab](https://colab.research.google.com)  
2. Upload `dataset.csv` to your session when prompted  
3. Run all cells in order to see model training, evaluation, and output

---

## 📈 Results

| Task                     | Model | Accuracy | Baseline | Notes                         |
|--------------------------|-------|----------|----------|-------------------------------|
| Topic Classification     | SVM   | 88%      | 31.9%    | Strong generalisation with TF-IDF  
| Readability Classification | LSTM  | 67.6%    | 51.25%   | Multi-input model outperformed baseline, slight overfitting observed

---

## 💡 Reflections & Ethics

Automating content evaluation introduces risks such as:
- Bias toward specific writing styles  
- Lack of transparency in rejection decisions  
- Over-reliance on models without human oversight  

This project emphasizes the need for **human-in-the-loop systems** in editorial automation.

---

## 🤝 Acknowledgements

Built as part of an MSc coursework module on applied machine learning. Inspired by real-world editorial workflows and the ethical implications of automating content moderation.

---
