# Employee Performance Prediction using Machine Learning

A Streamlit-based web application that predicts employee performance using machine learning models (Random Forest).  
The system ingests employee data, preprocesses it, trains a classification model, and provides real-time predictions for performance categories.

---

## 📌 Features
- Upload employee dataset (Excel format).
- Train a machine learning model (Random Forest) with accuracy metrics.
- Interactive web interface built with **Streamlit**.
- Real-time employee performance prediction via form inputs.
- Save predictions back to Excel for tracking and comparison.
- Compare old vs. new employee performance records.

---

## 🏗️ System Architecture
The system includes:
- **Data Ingestion & Preprocessing** (handling missing values, encoding categorical features).
- **Feature Extraction** (performance indicators, demographics, job history).
- **Model Training & Evaluation** (Random Forest, accuracy, precision, recall, F1-score).
- **Deployment** (Streamlit app for HR professionals).

📖 For detailed design, see the [Final Report](docs/final_report.pdf).

---

## ⚙️ System Requirements
- **OS**: Windows 10 / Ubuntu 20.04 / macOS  
- **Processor**: Intel i5 or better  
- **RAM**: Minimum 8 GB (16 GB recommended)  
- **Python**: 3.10 or higher  

---

## 📦 Dependencies
Install dependencies using:

```bash
pip install -r requirements.txt
