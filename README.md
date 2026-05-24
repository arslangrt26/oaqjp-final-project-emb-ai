# Emotion Detector (Embeddings-based Emotion AI)

## 📌 Project Overview
Emotion Detector is an AI-powered application that analyzes human emotions from text input using Natural Language Processing (NLP) and Machine Learning techniques.  
The system classifies text into emotions such as **joy, sadness, anger, fear, surprise, disgust, and neutral**, enabling better human-computer interaction.

This project is designed as part of the **oaqjp-final-project-emb-ai** workflow and demonstrates the use of NLP embeddings and emotion classification models in a real-world application.

---

## 🎯 Problem Statement
Machines cannot naturally understand human emotions expressed in text.  
This project aims to bridge this gap by building a model that can automatically detect emotions from text input and return meaningful emotional insights.

---

## 🎯 Objectives
- Build an NLP-based emotion classification system
- Train a machine learning model using text embeddings
- Predict emotions from user input in real time
- Deploy a simple web interface for interaction
- Demonstrate end-to-end AI pipeline (data → model → deployment)

---

## 😊 Emotion Categories
- Joy
- Sadness
- Anger
- Fear
- Surprise
- Disgust
- Neutral

---

## 🧠 Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF / Word Embeddings
- Flask / Streamlit
- HTML, CSS

---

## 🏗️ System Architecture
1. Input Collection (Text)
2. Text Preprocessing (Cleaning, Tokenization)
3. Feature Extraction (TF-IDF / Embeddings)
4. Model Training
5. Emotion Prediction
6. Output Display

---

## 📁 Project Structure
```
emotion-detector/
│
├── data/
├── notebooks/
├── models/
├── static/
├── templates/
├── app.py
├── train.py
├── utils.py
├── requirements.txt
└── README.md
```

---

## 🚀 How to Run

### Clone repo
```
git clone https://github.com/your-username/emotion-detector.git
cd emotion-detector
```

### Install dependencies
```
pip install -r requirements.txt
```

### Run app (Flask)
```
python app.py
```

### Run app (Streamlit)
```
streamlit run app.py
```

---

## 📊 Model Workflow
- Load dataset
- Clean text data
- Convert text into numerical features
- Train ML model
- Evaluate accuracy
- Save model
- Predict emotions in real time

---

## 🌟 Features
- Real-time emotion prediction
- Simple web interface
- Fast ML-based classification
- Easy to extend (speech/image support)
- Lightweight and deployable

---

## 🔮 Future Improvements
- Speech emotion detection
- Facial emotion recognition
- Transformer models (BERT)
- Multi-language support
- API integration

---

## 📌 Use Cases
- Chatbots
- Customer feedback analysis
- Mental health tools
- Social media sentiment analysis

---

## 👨‍💻 Author
Emotion Detector AI Project  
oaqjp-final-project-emb-ai
