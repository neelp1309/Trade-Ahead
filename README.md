# Trade-Ahead

## 🧠 Project Overview

This project was developed as part of a Data Science engagement with **Trade&Ahead**, a financial consultancy firm focused on personalized investment strategies. The primary objective of this analysis is to assist investors in **grouping stocks based on financial and market performance indicators** to create a **diversified and resilient portfolio**.

Through **clustering analysis**, we identify stocks with similar financial characteristics and performance patterns, enabling better investment decisions and enhanced portfolio diversification.

---

## 🎯 Objective

The goal of this project is to:
- Analyze financial and market data of companies listed on the **New York Stock Exchange (NYSE)**.
- Group stocks into **clusters based on their financial indicators** such as ROE, P/E ratio, EPS, volatility, and more.
- Provide **actionable insights** that help investors minimize risk and maximize returns through a **diversified investment approach**.

---

## 📂 Dataset Description

The dataset includes stock price information and key financial metrics for publicly traded companies on the NYSE.

### 🔑 Features

| Feature | Description |
|--------|-------------|
| **Ticker Symbol** | Unique identifier for a company's stock |
| **Company** | Company name |
| **GICS Sector** | Economic sector classification |
| **GICS Sub Industry** | Sub-industry classification |
| **Current Price** | Current stock price (USD) |
| **Price Change** | % price change over last 13 weeks |
| **Volatility** | Standard deviation of stock price (13 weeks) |
| **ROE** | Return on equity |
| **Cash Ratio** | Ratio of cash & equivalents to current liabilities |
| **Net Cash Flow** | Cash inflows - outflows (USD) |
| **Net Income** | Revenues - expenses (USD) |
| **Earnings Per Share (EPS)** | Net income per outstanding share (USD) |
| **Estimated Shares Outstanding** | Number of shares held by shareholders |
| **P/E Ratio** | Price-to-earnings ratio |
| **P/B Ratio** | Price-to-book ratio |

---

## 🔍 Methodology

### 1. **Data Preprocessing**
- Handling missing values
- Normalizing numerical data
- Encoding categorical variables

### 2. **Exploratory Data Analysis (EDA)**
- Sector-wise analysis
- Correlation matrix
- Visual inspection of feature distributions

### 3. **Feature Selection & Engineering**
- Selecting relevant features for clustering
- Dimensionality reduction (e.g., PCA for visualization)

### 4. **Clustering Techniques**
- **K-Means Clustering**
- Elbow Method to find optimal number of clusters
- Silhouette Score to validate cluster quality

### 5. **Cluster Profiling**
- Analyzing each cluster's financial characteristics
- Identifying sectors and patterns across clusters

### 6. **Visualization**
- Cluster plots (2D using PCA)
- Sector-wise distribution of clusters
- Heatmaps and boxplots for feature comparison

---

## 📈 Key Insights

- Stocks were successfully grouped into meaningful clusters based on financial performance.
- Certain clusters highlighted **low volatility and strong earnings**, ideal for low-risk investors.
- Others contained **high-growth or undervalued stocks** suited for high-risk, high-reward strategies.
- Sector diversification across clusters helped **reduce portfolio vulnerability** during market downturns.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data manipulation
- **Matplotlib**, **Seaborn**, **Plotly** – Data visualization
- **Scikit-learn** – Clustering and modeling
- **Google Colab** – Analysis environment
