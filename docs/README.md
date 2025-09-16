# Documentation

This folder contains project-related diagrams and detailed explanations of the methodology.

## 📌 System Architecture

![System Design](https://github.com/user-attachments/assets/717ced99-d1c1-4afe-899a-df4273eba679)

The architecture describes the **end-to-end flow** of the project:
1. **Data Ingestion & Preprocessing** – Cleaning and transforming employee datasets (handling missing values, encoding categorical variables, normalization).  
2. **Feature Extraction** – Selecting relevant features such as job role, education, training history, and performance scores.  
3. **Model Building** – Training ML models (Decision Tree, Random Forest, SVM, etc.) to classify employee performance.  
4. **Model Training & Evaluation** – Splitting into train/test sets, measuring accuracy, precision, recall, and F1-score.  
5. **Hyperparameter Tuning** – Optimizing the ML models for best results.  
6. **Deployment** – Streamlit app that HR managers can use directly.

## 📌 Project Workflow
- Input: Employee dataset (Excel/CSV format).  
- Processing: Machine Learning pipeline with preprocessing + model training.  
- Output: Predicted employee performance (High, Medium, Low) with option to save results to Excel.![Uploading Streamlit web application.png…]()


- 

This documentation connects the **research report** with the **working code**, so users understand both the technical and practical aspects of the system.
