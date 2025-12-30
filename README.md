# Autism_Disorder_Prediction

🧠 **Autism Disorder Prediction using Machine Learning**

📌 **Project Overview**

Autism Spectrum Disorder (ASD) diagnosis is a complex and time-consuming clinical process that can delay early intervention. This project leverages machine learning techniques, primarily Support Vector Machine (SVM), to predict the likelihood of ASD based on behavioral, demographic, and medical features. The system aims to assist healthcare professionals by providing faster, more accessible, and accurate predictions through a user-friendly web application.

🎯 **Problem Statement**

Early diagnosis of Autism Spectrum Disorder is crucial for effective intervention, but traditional diagnostic methods are time-intensive and resource-heavy.
The objective of this project is to develop a machine learning-based predictive model that:

Identifies ASD risk at an early stage

Reduces diagnostic time

Assists healthcare professionals in decision-making

Maintains ethical and interpretable predictions

💡 **Proposed Solution**

The proposed system uses a Support Vector Machine (SVM) classifier trained on a well-curated ASD dataset. The solution includes:

Data preprocessing and feature selection

Model training with optimized hyperparameters

Performance evaluation using standard metrics

Deployment via a Streamlit-based web interface

This enables healthcare professionals to input patient data and receive ASD predictions in real time.

🛠️ **Technologies Used**

Programming Language: Python

Machine Learning Algorithms:

Support Vector Machine (Primary)

Logistic Regression (Comparison)

Libraries & Frameworks:

NumPy

Pandas

Scikit-learn

Streamlit

Matplotlib

Development Tools:

PyCharm

Google Colab

Deployment: Docker

📊 **Dataset Description**

The dataset is sourced from the UCI Machine Learning Repository and includes the following features:

Social Responsiveness Scale

Age

Speech Delay / Language Disorder

Learning Disorder

Genetic Disorders

Depression

Global Developmental Delay / Intellectual Disability

Social & Behavioral Issues

Anxiety Disorder

Gender

Jaundice at Birth

Family History of ASD

Outcome (Target Variable): ASD / Non-ASD

⚙️ **System Architecture**

Data Collection

Data Preprocessing (Cleaning, Encoding, Normalization)

Feature Selection (EDA, RFE, PCA)

Model Training (SVM with kernel optimization)

Model Evaluation

Web Application Deployment (Streamlit)

✨ **Key Features**

Early autism risk prediction

Accurate classification using SVM

Feature-driven and interpretable predictions

User-friendly web interface

Fast and efficient processing

Ethical and responsible AI usage

Scalable and deployable using Docker

🧪 **Model Evaluation**

The model is evaluated using:

Accuracy

Precision

Recall

F1-score

ROC-AUC

Performance is validated using train-test split and cross-validation techniques.

🖥️ **User Interface**

The application provides:

Secure login and signup

ASD assessment form

Prediction results (Positive / Negative ASD)

Interactive chatbot for user queries

Statistics and visualization dashboard

🚀 **How to Run the Project**

**Clone the repository**

git clone https://github.com/NeelaSaiGautam/Autism_Disorder_Prediction.git

**Navigate to the project directory**

cd Autism

**Install dependencies**

pip install -r requirements.txt

**Run the Streamlit app**

streamlit run app.py

🐳 **Docker Support**

docker pull saigautam155d/autism:autism-chatbot

📈 **Results**

Successful prediction of ASD risk

Improved diagnostic efficiency

High usability for healthcare professionals

Accurate classification on test cases

🔮 **Future Enhancements**

Integration of advanced models (XGBoost, Deep Learning)

Inclusion of genetic and biomarker data

Real-time model updates

Mobile and cross-platform support

Improved explainability using SHAP/LIME

📚 **References**

UCI Machine Learning Repository

IEEE & Procedia Computer Science Research Papers

Autism Spectrum Disorder clinical studies
