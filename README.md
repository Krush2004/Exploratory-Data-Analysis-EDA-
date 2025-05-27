# 🚢 Exploratory Data Analysis (EDA) on Titanic Dataset

## 📌 Objective
To understand the structure and characteristics of the Titanic dataset using descriptive statistics and data visualization techniques.

---

## 🧰 Tools Used
- **Python**
- **Pandas** for data manipulation
- **Matplotlib & Seaborn** for static visualizations
- **Plotly** for interactive visualizations

---

## 📁 Dataset
**Titanic Dataset**  
This dataset contains information about passengers aboard the Titanic and whether they survived.  

📥 [Click here to download the dataset](#) *(Replace with actual link)*

---

## 🧪 EDA Steps

### 1. Summary Statistics
- Displayed data types, missing values, mean, median, standard deviation, etc.
- Identified categorical and numerical columns.

### 2. Univariate Analysis
- **Histograms** to visualize distributions of numeric features like `Age`, `Fare`, etc.
- **Boxplots** to detect outliers and spread of data.

### 3. Bivariate/Multivariate Analysis
- **Pairplot** to view relationships between numeric variables.
- **Correlation Matrix** to detect linear relationships.

### 4. Survival Analysis
- Count plots of `Survived` vs. `Sex` and `Pclass`.
- Fare distribution and its relation to survival.

### 5. Key Inferences
- Females had higher survival rates than males.
- First-class passengers were more likely to survive.
- Younger passengers (especially children) had a survival advantage.
- Passengers who paid higher fares generally had better survival odds.

---

## 📈 Sample Visuals

- 📊 Histograms & Boxplots
- 🔗 Correlation Heatmap
- 🎯 Countplots for survival based on key features
- 📦 Interactive boxplots using Plotly

---

## 🧠 What You'll Learn
- Data cleaning and summary techniques
- Visual exploration with Matplotlib, Seaborn, and Plotly
- Recognizing data patterns, trends, and outliers
- Making feature-level inferences for model preparation

---

## ✅ How to Run
```bash
# Install required libraries
pip install pandas matplotlib seaborn plotly

# Run the EDA script
python eda_titanic.py
