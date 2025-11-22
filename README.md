# Spam Detection Classifier

A complete **Django + Machine Learning** project to classify emails as **Spam** or **Not Spam** using an ML model and a simple web interface.

---
## 📸 Output Screenshot
<img width="1365" height="767" alt="Screenshot 2025-11-21 201142" src="https://github.com/user-attachments/assets/14215487-83a6-43c9-883d-c65403304bb8" />

## 🚀 Overview
This project provides a functional spam detection system built with:
- **Django** (backend + UI)
- **Scikit-Learn** (ML model)
- **Emails dataset (emails.csv)** for training

Users can input any email text and get an instant prediction.

---

## 📂 Project Structure
```
spam_detection/
│   manage.py
│   db.sqlite3
│   emails.csv
│
├── spam_detection/        # Django project settings
│     ├── settings.py
│     ├── urls.py
│     └── wsgi.py
│
└── detector/              # Main app
      ├── views.py
      ├── models.py
      ├── forms.py
      ├── templates/
      ├── static/
      └── ml/ (if model and vectorizer stored here)
```

---

## 🛠️ Installation Guide
Follow these steps to run the project locally.

### **1️⃣ Extract the Project ZIP**
Open a terminal inside the project folder:
```
cd spam_detection
```

### **2️⃣ Create a Virtual Environment**
```
python -m venv venv
```

### **Fix PowerShell error (if activation fails)**
```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
```

### **Activate the venv**
```
venv\Scripts\activate
```

### **3️⃣ Install Dependencies**
```
pip install django scikit-learn pandas numpy
```

### **4️⃣ Run Database Migrations**
```
python manage.py migrate
```

### **5️⃣ Start the Django Development Server**
```
python manage.py runserver
```
Then open:
```
http://127.0.0.1:8000/
```

---

## 📊 Dataset
`emails.csv` contains labeled text samples (spam / ham). It is used to train the ML classifier.

---

## 🤖 Machine Learning
The project typically uses:
- **Naive Bayes / Logistic Regression / SVM** for classification
- **CountVectorizer / TF-IDF** for text processing

The trained model is loaded automatically when the app runs.

---

## 🧪 How to Use
1. Visit the home page.
2. Paste any email text.
3. Click **Predict**.
4. The model returns: **Spam** or **Not Spam**.

---

## 🚧 Future Enhancements
- Add REST API support
- UI improvements
- Multiple model support
- Model retraining dashboard

---

## 👤 Developer
**Arik Mukherjee**

### 📬 Contact
Here are my contact and profile links with badges:


[![Email](https://img.shields.io/badge/Email-arikmukherjee3%40gmail.com-red?style=for-the-badge)](mailto:arikmukherjee3@gmail.com)


[![LinkedIn](https://img.shields.io/badge/LinkedIn-Arik%20Mukherjee-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/arikmukherjee)


[![GitHub](https://img.shields.io/badge/GitHub-arikmukherjee-black?style=for-the-badge&logo=github)](https://github.com/arikmukherjee)


[![YouTube](https://img.shields.io/badge/YouTube-Arik%20Mukherjee-red?style=for-the-badge&logo=youtube)](https://www.youtube.com/@arikmukherjee)
