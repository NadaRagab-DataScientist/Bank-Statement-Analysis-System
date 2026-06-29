# 🏦 Bank Statement Analysis System

An AI-powered system for extracting, classifying, and managing financial transactions from PDF bank statements using Machine Learning and FastAPI.

---

## 📌 Project Overview

This project automates the analysis of bank statements by extracting transaction data from PDF files, classifying transactions into financial categories, and allowing users to review and validate results before storing them in a database.

The system supports a feedback-driven learning workflow, enabling continuous model improvement over time.

---

## 🚀 Features

* Upload PDF bank statements
* Extract transaction data from PDF files
* Automatically classify financial transactions
* Review, edit, and validate extracted transactions
* Store validated transactions in a database
* Generate structured JSON outputs
* Continuous model improvement through user feedback
* FastAPI-based REST API integration

---

## 🔄 Workflow

1. User uploads a bank statement PDF.
2. Transaction text is extracted from the PDF.
3. Machine Learning model classifies transactions.
4. Results are returned as JSON.
5. User reviews and edits transactions if needed.
6. Validated data is stored.
7. User feedback is used to improve future predictions.

---

## 🧠 Machine Learning Pipeline

* Text preprocessing
* Feature extraction using vectorization
* Transaction classification
* Confidence scoring
* Feedback collection for model retraining

---

## 🌐 API Endpoints

### POST /predict-pdf/

Upload a PDF bank statement and receive extracted transactions with predicted categories.

### POST /feedback/

Store user-corrected transaction labels for future model improvement.

### POST /train-feedback/

Retrain the machine learning model using collected feedback data.

---

## 🔁 Continuous Learning

The system supports a feedback-driven workflow where users can review and correct transaction classifications. These corrections are stored and later used to retrain the model, enabling continuous performance improvement over time.

---

## 📄 Sample JSON Output

```json
{
  "transactions": [
    {
      "date": "2024-01-15",
      "amount": 5000.00,
      "description": "Salary Transfer",
      "type": "Revenue",
      "category": "Salary"
    }
  ]
}
```

---

## 🛠️ Technologies Used

* Python
* FastAPI
* Scikit-learn
* Pandas
* PyMuPDF
* Machine Learning
* PDF Processing
* REST APIs
* JSON
* Joblib


---

## 📸 Screenshots

### Swagger UI

Add a screenshot of the FastAPI Swagger documentation here.

### Prediction Results

Add a screenshot showing transaction classification results.

---

## 🎯 Future Improvements

* Multi-bank support
* Improved transaction extraction accuracy
* Advanced transaction categorization
* Real-time dashboard and analytics
* Automated model retraining pipeline
* Cloud deployment support

---

## 💡 Business Value

This system helps automate financial transaction processing, reduces manual effort, improves classification consistency, and supports continuous learning through user feedback, making it suitable for FinTech and financial data management applications.
