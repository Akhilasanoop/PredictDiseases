# 🧠 Predict Diseases Using Symptoms (AI-Powered Diagnosis Tool)

This project is an AI-driven disease prediction tool developed by **Akhila**, an educator at **LearnTech IT Academy**. It leverages **natural language processing** and **cosine similarity** to predict diseases based on user-reported symptoms.

## 📌 Overview

- Built using `pandas`, `sklearn`, and a user-friendly `tkinter` GUI.
- Analyzes symptom inputs and predicts the most likely disease.
- Displays predictions with confidence scores.

## 🧪 Key Features

- ✅ Text vectorization using **CountVectorizer**
- ✅ Disease matching using **cosine similarity**
- ✅ Real-time predictions via a **Tkinter GUI**
- ✅ Reads data from a `predicteddiseases.csv` file
- ✅ Cleaned for noisy/malformed input rows

## 📂 Dataset

- Input: `predicteddiseases.csv`
- Columns: `Symptoms`, `Predicted Disease`, `Confidence (%)`

## 🚀 How to Run

1. Install required packages:
   ```bash
   pip install pandas scikit-learn
