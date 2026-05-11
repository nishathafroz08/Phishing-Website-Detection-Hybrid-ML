# 🛡️ Phishing Website Detection using Hybrid ML Techniques

A Django-based web application that detects phishing websites using a hybrid combination of Machine Learning algorithms including Random Forest, Support Vector Machine (SVM), and LightGBM.

---

## 📌 Project Overview

Phishing attacks are one of the most common cyber threats today. This project aims to detect phishing websites by analyzing URLs using multiple machine learning models combined in a hybrid approach to improve detection accuracy.

---

## 🛠️ Technologies Used

- **Language:** Python
- **Framework:** Django
- **Machine Learning:** Scikit-learn, LightGBM
- **Feature Extraction:** TF-IDF Vectorizer
- **Dataset:** Benign and Phishing URL datasets
- **Frontend:** HTML, CSS
- **Database:** SQLite

---

## 🤖 ML Models Used

| Model | Description |
|-------|-------------|
| Random Forest (RF) | Ensemble learning method for classification |
| Support Vector Machine (SVM) | Supervised learning for URL classification |
| LightGBM (LGBM) | Gradient boosting framework for fast predictions |
| TF-IDF Vectorizer | Feature extraction from URLs |

---

## 📁 Project Structure

```
Phishing/
├── Dataset/
│   ├── 1.Benign_list_big_final.csv
│   └── 2.online-valid.csv
├── model/
│   ├── rf.txt
│   ├── svm.txt
│   ├── lgbm.txt
│   └── tfidf.txt
├── PhishingDetection/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── PhishingDetectionApp/
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   │   ├── index.html
│   │   ├── Predict.html
│   │   ├── AdminLogin.html
│   │   └── ViewOutput.html
│   └── static/
├── manage.py
├── requirements.txt
└── run.bat
```

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/nishathafroz08/Phishing-Website-Detection-Hybrid-ML.git
cd Phishing-Website-Detection-Hybrid-ML
```

### 2. Create a Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate  # On Windows
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the Application
```bash
python manage.py runserver
```

### 5. Open in Browser
```
http://127.0.0.1:8000/
```

---

## 🚀 Features

- 🔍 Detects phishing URLs in real-time
- 🤖 Hybrid ML model for higher accuracy
- 📊 Admin panel to view prediction results
- 🌐 Simple and clean web interface
- ⚡ Fast predictions using pre-trained models

---

## 📊 Dataset

- **Benign URLs:** `1.Benign_list_big_final.csv`
- **Phishing URLs:** `2.online-valid.csv`

---

## 👩‍💻 Developed By

**Dudekula Nishath Afroz**  
Final Year - B.Tech CSE (AI)  
📧 nishathafroz08@gmail.com  
🔗 [GitHub](https://github.com/nishathafroz08)

---

## 📄 License

This project is developed for academic purposes as part of the Final Year Project.
