# 🧹 Task 1: Data Cleaning & Preprocessing (Titanic Dataset)

## 📌 Objective
This project focuses on learning how to **clean and preprocess raw data** to make it suitable for Machine Learning models. It covers a complete workflow using the Titanic dataset.

---

## 🛠️ Tools & Technologies
- Python 3
- Pandas
- NumPy
- Matplotlib (used for visualization)
- Scikit-learn (used for preprocessing tasks like scaling and encoding)

---

## 📂 Dataset
We use the **Titanic Dataset**, which includes data about passengers aboard the Titanic, such as age, gender, fare, and survival status.  
🔗 [Download Titanic dataset on Kaggle](https://www.kaggle.com/competitions/titanic/data)

---

## ✅ Key Steps Performed

### 1. Import & Explore Dataset
- Loaded the dataset using Pandas
- Explored column data types and checked for missing/null values

### 2. Handle Missing Values
- Filled missing values in `Age` using the **median**
- Filled missing values in `Embarked` using the **mode**
- Dropped `Cabin` column due to excessive missing data

### 3. Encode Categorical Variables
- **Label Encoding** used for the `Sex` column
- **One-Hot Encoding** applied to the `Embarked` column

### 4. Normalize Numerical Features
- Used `MinMaxScaler` to normalize `Age` and `Fare` values to a 0–1 range

### 5. Detect and Remove Outliers
- Plotted **boxplots** using `matplotlib` to visualize outliers
- Removed outliers using the **Interquartile Range (IQR)** method

---

## 🤖 What I Learned

- How to load and explore real-world datasets using Pandas
- Importance and methods of handling missing data
- Various techniques for encoding categorical variables
- When to use **normalization vs. standardization**
- Visualizing and removing outliers to improve data quality
- How preprocessing can significantly affect model performance

---

## 💬 Interview Prep: Key Questions Answered

1. **Types of missing data:**
   - MCAR, MAR, MNAR

2. **Handling categorical variables:**
   - Label Encoding and One-Hot Encoding

3. **Normalization vs Standardization:**
   - Normalization rescales to [0,1]; Standardization uses Z-score

4. **Detecting outliers:**
   - Boxplots, IQR method, Z-score

5. **Why preprocessing is important:**
   - Ensures clean, consistent, and meaningful data for ML algorithms

6. **One-hot vs Label encoding:**
   - One-hot creates binary columns; Label assigns integer values

7. **Handling data imbalance:**
   - Resampling (oversampling, undersampling), SMOTE, class weighting

8. **Effect of preprocessing on model accuracy:**
   - Essential for better generalization, lower bias/variance

---



