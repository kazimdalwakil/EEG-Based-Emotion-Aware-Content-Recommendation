# 🎯 Mood Stabilization Recommendation System using EEG & Content Recommendation

## 📌 Overview

In today's fast-paced digital world, mental health is increasingly affected by the type of content we consume. This project proposes an intelligent system that detects a user’s emotional state using EEG signals and recommends “feel-good” content to stabilize mood.

The system combines **affective computing**, **deep learning**, and **recommendation systems** to build a pipeline that not only understands emotional states but actively improves them.

---

## 🚀 Key Features

* 🧠 Emotion Detection using EEG signals
* 🔍 Feature Extraction:

  * Differential Entropy
  * Wavelet Transform
  * Shannon Entropy
  * Eye Movement Features
* 🤖 Deep Learning Models:

  * Convolutional Neural Network (CNN)
  * Long Short-Term Memory (LSTM)
* 🎯 High Accuracy:

  * CNN achieved **93.01% accuracy**
* 🎬 Content Recommendation:

  * Emotion-based video classification
  * Pearson Correlation for similarity
  * Analytic Hierarchy Process (AHP) for ranking
* 😊 Goal: Gradual Mood Stabilization through curated content

---

## 🗂️ Dataset

* **SEED Dataset**

  * EEG signals
  * Eye movement data
* Used for emotion classification (e.g., positive, negative, neutral)

---

## ⚙️ System Architecture

1. EEG Signal Input
2. Feature Extraction
3. Emotion Classification (CNN / LSTM)
4. Emotion Tagging
5. Content Filtering
6. Recommendation Engine (Pearson + AHP)
7. Mood Stabilization Output

---

## 🧪 Methodology

### 1. Feature Extraction

* Differential Entropy
* Wavelet Transform
* Shannon Entropy
* Eye Movement Features

### 2. Emotion Classification

* CNN (Best performing model)
* LSTM (Temporal analysis)

### 3. Recommendation System

* Text-based Emotion Classification of Videos
* Pearson Correlation for similarity scoring
* AHP for multi-criteria decision making

---

## 📊 Results

| Model | Accuracy       |
| ----- | -------------- |
| CNN   | 93.01%         |
| LSTM  | Lower than CNN |

✅ CNN outperformed LSTM in emotion classification tasks.

---

## 💡 Applications

* Mental health support systems
* Personalized content platforms
* Smart wellness assistants
* Human-computer interaction systems

---

## 🛠️ Tech Stack

* Python
* TensorFlow / Keras / PyTorch
* NumPy, Pandas
* Scikit-learn
* Signal Processing Libraries

---

## 🔮 Future Work

* Real-time EEG integration
* Mobile/Web app deployment
* Reinforcement learning for adaptive recommendations
* Multimodal emotion detection (voice, facial expression)

---

## 👨‍🎓 Authors

* Kazi Md Al Wakil, Nafisa Nawal, Rifai Rahman, Sababa Rahman Meem & Sajid Rashid
* Supervisor: Dr. Md. Golam Rabiul Alam
* Undergraduate Thesis Project

---

## 📜 License

This project is for academic and research purposes.
