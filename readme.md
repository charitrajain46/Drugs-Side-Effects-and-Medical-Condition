# Drugs, Side Effects and Medical Condition Analysis  
**Domain:** Data Analytics | Data Science  
**Difficulty Level:** Intermediate  

---

## 📌 Project Overview

This project focuses on analyzing drugs, their associated side effects, and the medical conditions they are prescribed for. The goal is to extract meaningful insights from real-world healthcare data using **Python-based data analytics and exploratory data analysis (EDA)** techniques.

The project demonstrates how structured and semi-structured medical data can be cleaned, transformed, analyzed, and visualized to support better understanding of drug usage patterns, risk factors, and patient-related outcomes.

---

## 🎯 Objective

The primary objectives of this project are:

- To analyze relationships between **drugs**, **side effects**, and **medical conditions**
- To identify **frequently prescribed drugs** for various conditions
- To examine **common side effects** and their occurrence frequency
- To study **drug ratings, reviews, and risk indicators**
- To prepare data for further **machine learning and predictive analysis**

---

## 📂 Dataset Description

The dataset contains information about drugs used for treating conditions such as Acne, Cancer, Heart Disease, Diabetes, Pain, and more.  

**Source:**  
- Drugs.com  
- Kaggle public healthcare datasets  

**Total Records:** 2,931  
**Total Features:** 17  

### Key Columns

| Column Name | Description |
|------------|------------|
| `drug_name` | Name of the drug |
| `medical_condition` | Condition the drug is prescribed for |
| `side_effects` | Known side effects |
| `generic_name` | Chemical/generic name |
| `drug_classes` | Drug classification |
| `activity` | Drug popularity/activity percentage |
| `rx_otc` | Prescription or Over-the-counter |
| `pregnancy_category` | FDA pregnancy risk classification |
| `csa` | Controlled Substances Act category |
| `alcohol` | Alcohol interaction indicator |
| `rating` | Average user rating |
| `no_of_reviews` | Number of user reviews |
| `drug_link` | Drug reference URL |
| `medical_condition_url` | Condition reference URL |

---

## 🛠 Tools & Technologies Used

- **Python**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Data preprocessing & scaling
- **Jupyter Notebook**
- **Excel** (optional for inspection)

---

## 🔍 Project Workflow

### 1. Data Loading
- Imported CSV dataset into Pandas DataFrame
- Verified data structure, types, and dimensions

### 2. Data Cleaning
- Handled missing values using:
  - Replacement (`Unknown`, `0`)
  - Dropping unnecessary columns
- Converted percentage strings into numeric format
- Removed duplicates (if any)

### 3. Data Preprocessing
- Label Encoding of categorical variables
- Feature selection for analytics
- Standardization using `StandardScaler`

### 4. Exploratory Data Analysis (EDA)
- Distribution of drug ratings
- Most common medical conditions
- Frequently reported side effects
- Popular drug classes
- Correlation analysis using heatmaps

### 5. Feature Engineering
- Created boolean flags for:
  - Common side effects (Hives, Itching, Breathing issues)
  - Frequent medical conditions (Pain, Acne, Colds & Flu)
  - Major drug classes

### 6. Visualization
- Bar charts for:
  - Side effect occurrences
  - Medical condition frequency
  - Drug class distribution
- Correlation heatmaps

---

## 📊 Key Insights

- **Pain, Colds & Flu, and Acne** are among the most treated conditions
- **Hives and breathing difficulties** are the most frequently reported side effects
- Certain drug classes show higher average ratings
- Alcohol interaction exists in a significant subset of drugs
- Drugs with higher review counts often correlate with moderate-to-high ratings

---

## 📈 Output Files Generated

- `drugs_side_effects_drugs_com_version2.csv`
- `medical_condition_counts.csv`
- `side_effect_counts.csv`
- `drug_classes_counts.csv`

---

## 🚀 Future Enhancements

- Apply **machine learning models** for:
  - Drug recommendation
  - Side effect prediction
- Develop an **interactive dashboard**
- Deploy analysis using **Flask or Streamlit**
- Perform **NLP analysis** on textual side effects
- Integrate external healthcare datasets

---

## 📚 Learning Outcome

This project strengthened practical understanding of:
- Healthcare data analytics
- Real-world data cleaning challenges
- Feature engineering techniques
- Analytical thinking and visualization
- Preparing datasets for ML pipelines

---

## 🔗 Reference

- Drugs.com  
- Kaggle Healthcare Datasets  
- Project Inspiration:  
  https://github.com/dhyutin/Drugs-Side-Effects-and-Medical-Conditions-Analysis

---

## 👤 Author

**Charitra Jain**  
MCA | Aspiring Data Analyst & Data Scientist  
Python | SQL | EDA | Machine Learning  

---

⭐ If you find this project helpful, feel free to star the repository!
