# 💳 Credit Card Approval Prediction
### A SmartBridge AI & Machine Learning Project

## 🌐 Live Demo

**🚀 Live Application**

https://ai-ml-smartbridge-project-credit-card.onrender.com

**🎥 Project Demonstration Video**

https://1drv.ms/v/c/8d731e612a2edf97/IQAno4bKHUHtQaQBMu40016QATOaVeT9UYeq7gDljflPtQo?e=RdYDP3

**📂 GitHub Repository**

https://github.com/Muni-GM/Credit-Card-Approval-Prediction

---

# 📖 Project Overview

Credit Card Approval Prediction is an AI-powered web application developed as part of the **SmartBridge AI & Machine Learning Internship**. The system predicts whether a customer's credit card application is likely to be approved based on financial and personal details.

The application uses a trained **Random Forest Classifier** to analyze applicant information and instantly predicts approval status with a confidence score through a modern, responsive web interface.

The project demonstrates the practical implementation of Machine Learning in the banking and financial sector by automating credit card eligibility prediction.

---

# 🎯 Features

- 💳 Predict Credit Card Approval in real time
- 🤖 Machine Learning powered by Random Forest Classifier
- 📊 Displays prediction confidence score
- 🌐 Interactive and responsive web interface
- ⚡ Instant prediction results
- ✔ Client-side and server-side validation
- 🔄 Automatic model training if model files are unavailable
- 📂 REST API developed using Flask
- ☁ Ready for deployment on Render

---

# 📊 Input Parameters

The prediction model uses the following applicant information:

- Gender
- Age
- Annual Income
- Total Debt
- Marital Status
- Bank Customer Status
- Employment Status
- Years Employed
- Previous Credit Default
- Credit Score
- Industry Type
- Citizenship Status

---

# 📈 Prediction Output

The application displays:

- ✅ Credit Card Approved
- ❌ Credit Card Not Approved
- 📊 Confidence Percentage
- 💬 User-friendly prediction message

---

# 🖼 Application Walkthrough

## 🏠 Home Page

The application provides a clean dashboard where users can enter applicant details.

Features include:

- Professional UI
- Responsive Design
- Easy Data Entry
- Real-time Validation

---

## 📝 Applicant Details Form

Users provide:

- Personal Information
- Financial Information
- Employment Information
- Credit Information
- Industry Details
- Citizenship Status

---

## 🤖 Prediction Engine

The backend processes the user inputs using the trained Machine Learning model.

Workflow:

Applicant Details

↓

Data Validation

↓

Feature Encoding

↓

Random Forest Prediction

↓

Confidence Calculation

↓

Display Final Result

---

## 📊 Prediction Result

After clicking **Check Eligibility**, the application displays:

- Approval Status
- Confidence Percentage
- Success or Rejection Message
- Visual Result Indicators

---

# 📂 Project Structure

```
Credit-Card-Approval-Prediction/
│
├── app.py
├── clean_dataset.csv
├── requirements.txt
├── README.md
│
├── models/
│   ├── card_model.joblib
│   ├── encoders.joblib
│   └── feature_cols.joblib
│
├── templates/
│   └── index.html
│
├── static/
│   ├── style.css
│   └── script.js
│
├── Brainstorming & Ideation/
├── Requirement Analysis/
├── Project Design/
├── Project Planning/
├── Project Development/
├── Project Testing/
├── Project Documentation/
└── Project Demonstration/
```

---

# 🛠 Technology Stack

## Programming Language

- Python 3.12

## Backend

- Flask

## Frontend

- HTML5
- CSS3
- JavaScript

## Machine Learning

- Scikit-learn
- Random Forest Classifier

## Libraries

- Pandas
- NumPy
- Joblib
- Gunicorn

## Deployment

- Render

---

# 🤖 Machine Learning Model

## Algorithm Used

Random Forest Classifier

The model was trained using applicant demographic and financial information to classify applications into:

- Approved
- Not Approved

The trained model is automatically saved as:

```
models/card_model.joblib
```

along with

```
encoders.joblib

feature_cols.joblib
```

for future predictions.

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/Muni-GM/Credit-Card-Approval-Prediction.git

cd Credit-Card-Approval-Prediction
```

---

## Create Virtual Environment

### Windows

```bash
python -m venv venv

venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# ▶ Run the Application

```bash
python app.py
```

Open

```
http://127.0.0.1:5000
```

---

# 🌐 Deploy on Render

This project is configured for deployment on Render.

## Steps

1. Push the project to GitHub.

2. Create a new Web Service in Render.

3. Connect your GitHub repository.

4. Build Command

```bash
pip install -r requirements.txt
```

5. Start Command

```bash
gunicorn app:app
```

6. Deploy the application.

---

# 📡 API Endpoint

## POST

```
/predict
```

Example Response

```json
{
  "approved": true,
  "confidence": 96.4
}
```

---

# 📦 Requirements

```
Flask
Gunicorn
NumPy
Pandas
Scikit-learn
Joblib
XGBoost
```

---

# 🧪 Testing

Run locally

```bash
python app.py
```

Open the browser and test the application using different applicant details.

---

# 🔒 Security

The application includes:

- Client-side validation
- Server-side validation
- Safe categorical encoding
- JSON request validation
- Error handling
- Secure Machine Learning inference

---

# 📈 Future Improvements

- User Authentication
- Prediction History Dashboard
- Loan Eligibility Prediction
- Explainable AI using SHAP
- Model Comparison Dashboard
- Docker Container Support
- Cloud Database Integration
- REST API Documentation
- Mobile Application
- Admin Dashboard

---

# 📚 Learning Outcomes

Through this project we learned:

- Machine Learning Model Development
- Data Preprocessing
- Feature Engineering
- Flask Web Development
- REST API Development
- Frontend Integration
- Model Deployment using Render
- GitHub Version Control
- End-to-End AI Application Development

---

# 👨‍💻 Project Team

Developed as part of the

**SmartBridge AI & Machine Learning Internship**

### Team Members

- Muni Shashank Reddy

(Add other members if applicable)

---

# 🎓 Organization

SmartBridge

AI & Machine Learning Internship

---

# 📄 License

This project is developed for educational and academic purposes only.

---

# ⭐ Support

If you found this project useful,

⭐ Star this repository

🍴 Fork the repository

📢 Share it with others

---

# 🔗 Project Links

## 🚀 Live Application

https://ai-ml-smartbridge-project-credit-card.onrender.com

## 📂 GitHub Repository

https://github.com/Muni-GM/Credit-Card-Approval-Prediction

## 🎥 Project Demonstration Video

https://1drv.ms/v/c/8d731e612a2edf97/IQAno4bKHUHtQaQBMu40016QATOaVeT9UYeq7gDljflPtQo?e=RdYDP3
