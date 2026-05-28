# AI-Powered Fraud Detection for E-Commerce

An AI-based system designed to detect suspicious and potentially fake products in e-commerce platforms using a combination of deep learning, machine learning, NLP, and computer vision techniques.

The project analyzes product descriptions, images, seller behavior, pricing patterns, and customer reviews to generate a final fraud detection decision.

---

# Project Overview

Online marketplaces contain thousands of products uploaded daily, making it difficult to manually identify misleading or fraudulent listings.

This project builds a complete AI pipeline that combines:
- NLP
- Computer Vision
- Machine Learning
- Explainable AI

to improve fraud detection reliability in e-commerce platforms.

The final system is deployed using Streamlit for interactive product analysis.

---

# Features

- Product fraud detection system
- NLP-based description analysis
- Product image classification
- Seller credibility analysis
- Fake review detection
- Price anomaly detection
- Explainable AI using SHAP
- Interactive Streamlit dashboard

---

# Technologies Used

## Programming & Frameworks
- Python
- Streamlit
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy

## Deep Learning & NLP
- LSTM
- Transformer Models
- CNN
- EfficientNetB0
- Naive Bayes

## Visualization & Explainability
- Matplotlib
- SHAP

---

# Models Used

## 1. Product Description Analysis
Two NLP approaches were implemented:
- LSTM
- Transformer-based classification

The models analyze product titles and descriptions to identify suspicious wording patterns.

---

## 2. Product Image Classification
Image classification was implemented using:
- CNN
- EfficientNetB0 (Transfer Learning)

EfficientNetB0 achieved better generalization and performance.

---

## 3. Seller Credibility Analysis
A Random Forest model was trained using:
- Seller rating
- Number of reviews
- Product rating
- Discount percentage

to identify suspicious seller behavior.

---

## 4. Customer Review Analysis
Naive Bayes was used to detect misleading and repetitive review patterns.

---

## 5. Price Fraud Detection
A separate model was implemented to detect unrealistic pricing and fake discounts.

---

## 6. Fusion Decision System
Predictions from all models are combined into one final fraud detection decision.

---

# Explainable AI

SHAP was integrated to improve model interpretability and explain prediction results.

This helps users understand:
- Which features affected predictions
- Why a product was classified as trusted or suspicious

---

# Streamlit Application

The project includes an interactive Streamlit application where users can:
- Upload product information
- Analyze product images
- Predict fraudulent products
- View prediction explanations

---

# Dataset & Data Collection

The dataset was collected using web scraping techniques from e-commerce platforms.

Collected data includes:
- Product titles
- Product descriptions
- Product images
- Seller information
- Ratings and reviews
- Pricing details

Data preprocessing and manual labeling were applied before training the models.

---

# Project Structure

```bash
├── DL_Project.ipynb
├── Scraping code.ipynb
├── Streamlit/
├── data/
├── README.md
```

---

# Installation

## Clone the repository

```bash
git clone https://github.com/loaymagdy38/AI-Powered-Fraud-Detection-for-E-Commerce.git
```

## Navigate to the project

```bash
cd AI-Powered-Fraud-Detection-for-E-Commerce
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Run Streamlit App

```bash
streamlit run app.py
```

---

# Future Improvements

- Deploy the system on cloud platforms
- Improve real-time fraud detection
- Expand dataset size
- Improve review analysis using transformers
- Integrate browser extension support

---

# Author

## Loay Magdy

AI & Machine Learning Enthusiast

GitHub:
https://github.com/loaymagdy38
