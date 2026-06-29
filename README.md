# 🏦 Bank Statement Analysis System

An AI-powered system for extracting, classifying, and managing financial transactions from PDF bank statements using OCR, Machine Learning, and FastAPI.

## 📌 Project Overview

This project automates the analysis of bank statements by extracting transaction data from PDF files, classifying transactions into financial categories, and allowing users to review and validate results before storing them in a database.

The system also supports a feedback-driven learning workflow, enabling continuous model improvement over time.

---

## 🚀 Features

* Upload PDF bank statements
* Extract transaction data using OCR
* Automatically classify financial transactions
* Review, edit, and validate extracted transactions
* Store validated transactions in a database
* Generate structured JSON outputs
* Continuous model improvement through user feedback
* FastAPI-based REST API integration

---

## 🔄 Workflow

1. User uploads a bank statement PDF.
2. OCR extracts transaction information.
3. Machine Learning model classifies transactions.
4. Results are returned as JSON.
5. User reviews and edits transactions if needed.
6. Validated data is stored in the database.
7. User feedback is used to improve future predictions.

---

## 🧠 Machine Learning Pipeline

* Text preprocessing
* Feature extraction using vectorization
* Transaction classification
* Confidence scoring
* Feedback collection for model retraining

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

## 🛠️ Technologies Used

* Python
* FastAPI
* Machine Learning
* OCR
* PDF Processing
* Pandas
* Scikit-learn
* JSON
* SQL Database
* REST APIs


---

## 🎯 Future Improvements

* Multi-bank support
* Improved OCR accuracy
* Advanced transaction categorization
* Real-time dashboard and analytics
* Automated model retraining pipeline


