# 📊 Credit Card Fraud Detection Using Machine Learning

## 📘 Project Overview
This project focuses on detecting fraudulent credit card transactions using various machine learning algorithms. The dataset contains transactional data from 1,000 customers and 800 merchants between January 2019 and December 2020. The goal is to build and evaluate models that accurately classify transactions as fraudulent or legitimate, enhancing financial security for consumers and institutions.

---

## 🗃️ Data Sources
- Simulated credit card transaction dataset comprising training and testing sets.
- Data features include transaction date/time, amount, merchant category, customer demographics (gender, job, location), and fraud labels.

---

## ⚙️ Methodology

### 1. Data Loading and Integration
- Combined training and testing datasets into one comprehensive dataset for uniform processing.

### 2. Data Preprocessing
- Checked for missing and duplicate values; none found.
- Converted categorical variables using ordinal encoding.
- Scaled numerical features using standardization for improved model performance.
- Addressed class imbalance by under-sampling non-fraud cases and balancing the dataset.

### 3. Exploratory Data Analysis (EDA)
- Analyzed fraud distribution across categories like spending category, gender, state, and job type.
- Visualized transaction amount distributions for fraud vs non-fraud.

### 4. Feature Engineering
- Selected relevant features including transaction amount, category, gender, city, state, job, and date of birth.
- Created encoded numerical representations for categorical variables.

### 5. Model Development and Hyperparameter Tuning
- Applied five supervised machine learning models:
  - Decision Tree Classifier
  - Random Forest Classifier
  - XGBoost Classifier
  - Logistic Regression
  - Neural Network (MLPClassifier and Keras Sequential model)
- Used grid search and randomized search for hyperparameter optimization.

### 6. Model Training and Evaluation
- Split data into training (70%) and testing (30%) sets.
- Evaluated models using accuracy, precision, recall, F1-score, ROC curve, and confusion matrix.
- Compared model performance with and without hyperparameter tuning.

---

## 📈 Key Results
- **XGBoost** achieved the highest accuracy (~97%) with balanced precision and recall for fraud detection.
- **Decision Tree** and **Random Forest** classifiers also showed strong performance with accuracy above 95%.
- Neural networks demonstrated competitive accuracy (~86%) with room for improvement on recall.
- Logistic regression provided reasonable accuracy (~85%) but lower recall for fraud cases.
- Class balancing and feature selection were critical for model performance.

---

## 💡 Practical Implications
- Efficient fraud detection systems protect financial institutions and consumers from monetary losses.
- Machine learning models can process large-scale transactional data effectively, improving fraud identification rates.
- Models like XGBoost offer a robust framework for real-time fraud monitoring.

---

## 🚀 Future Work
- Explore deep learning and hybrid models for enhanced fraud pattern recognition.
- Incorporate additional behavioral and network features to improve detection accuracy.
- Deploy real-time detection pipelines for practical financial fraud prevention applications.

---

