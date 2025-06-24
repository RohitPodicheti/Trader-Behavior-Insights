# Trader-Behavior-Insights
# 📊 Bitcoin Market Sentiment vs Trader Performance

This project explores the relationship between **Bitcoin market sentiment** (Fear/Greed Index) and **trader profitability** using real-world trading data. It combines exploratory data analysis and machine learning to uncover how emotion-driven market phases influence trading outcomes.

---

## 📁 Datasets Used

1. **Bitcoin Fear & Greed Index**
   - Columns: `date`, `classification`, `value`
   - Represents daily market sentiment (e.g., Fear, Greed)

2. **Historical Trade Data**
   - Columns: `Timestamp IST`, `Side`, `Closed PnL`, `Size USD`, `Execution Price`, `Start Position`, etc.
   - Contains trade-level data from a crypto exchange (Hyperliquid)

---

## 🧠 Project Goals

- Understand how market sentiment impacts trading outcomes
- Identify behavioral patterns (e.g., side preference, risk levels)
- Build a model to **predict if a trade will be profitable**

---

## 🛠️ Process Overview

### 1. Data Cleaning & Preprocessing
- Parsed and converted timestamp fields
- Merged sentiment with trade data by date
- Handled missing values, encoded categorical variables

### 2. Exploratory Data Analysis (EDA)
- Analyzed trade profitability across sentiment phases
- Visualized distribution of trade size, PnL, and behavior by sentiment
- Key Insight: Trades were **more profitable on Greed days**

### 3. Classification Modeling
- Trained a **Logistic Regression** model to predict trade profitability
- Input Features: Trade side, sentiment, size, price, position
- Output: Binary classification (profitable or not)

---

## 🔍 Key Insights

- **Greed days** correlated with higher trade profitability
- **Trade side** and **market sentiment** were strong predictors of outcomes
- Even during Fear phases, certain behaviors (e.g., lower size + sell-side) reduced losses

---

## 🧪 Tools & Technologies

- **Python**, **Pandas**, **Seaborn**, **Scikit-learn**, **Matplotlib**
- Logistic Regression (classification model)
- Jupyter Notebook for analysis

---

## 📈 Future Work

- Try other models like Random Forest or XGBoost
- Incorporate live sentiment feeds (via APIs)
- Create a real-time prediction dashboard using Streamlit or Flask

---

## 🤝 Author

**Rohit Podicheti**  
https://www.linkedin.com/in/rohit-podicheti-361628325/

---

## 📌 Repo Structure

