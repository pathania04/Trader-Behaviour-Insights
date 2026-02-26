# 📊 Trader Behaviour Insights — Fear vs Greed Analysis

##  Project Overview

This project analyzes trader behavior using historical trading data combined with the **Fear & Greed Index** to understand how market sentiment impacts trading performance, decision-making, and risk behavior.

The objective is to uncover behavioral patterns, evaluate profitability across different sentiment regimes, and generate data-driven strategy recommendations for improving trading performance.

---

## 🎯 Objectives

* Analyze trader profitability across **Fear vs Greed** market conditions
* Study behavioral changes such as:

  * Position size
  * Trade frequency
  * Long vs Short bias
  * Win rate
* Identify patterns among different trader segments
* Build a predictive model for trade profitability
* Provide actionable strategy recommendations

---

## 📂 Dataset Description

The project uses two datasets:

### 1️⃣ Historical Trading Data

Contains trader activity information:

* Account ID
* Execution Time
* Side (BUY / SELL)
* Size (USD)
* Closed PnL
* Trade Details

### 2️⃣ Fear & Greed Index Data

Market sentiment classification:

* Date
* Fear & Greed Value
* Sentiment Category (Fear, Neutral, Greed, etc.)

---

## ⚙️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

---

## Methodology

The project follows a structured data analytics workflow:

### 1. Data Cleaning & Preprocessing

* Converted timestamps to datetime
* Extracted daily trading features
* Handled missing values and inconsistencies

### 2. Data Integration

* Merged trading dataset with sentiment index using date

### 3. Feature Engineering

Created behavioral metrics such as:

* Daily trader PnL
* Win rate
* Trade frequency
* Average position size
* Long vs Short ratio
* Trader segmentation categories

### 4. Exploratory Data Analysis

Compared performance across sentiment regimes:

* Profitability vs sentiment
* Trade distribution patterns
* Risk behavior changes
* Segment-wise analysis

### 5. Predictive Modeling

A machine learning model was built to predict trader profitability using:

* Market sentiment
* Trade size
* Behavioral metrics

---

## Key Insights

* Trader profitability varies significantly across sentiment conditions.
* Position sizes tend to increase during **Greed** periods.
* Fear periods often show better risk-adjusted opportunities.
* High-frequency traders demonstrate more stable performance.
* Emotional market extremes increase PnL volatility.

---

## Strategy Recommendations

* Reduce position size during extreme greed markets.
* Use contrarian opportunities during fear periods.
* Maintain consistent risk management across sentiment regimes.
* Integrate sentiment indicators into trading systems.

---

## Outputs

The notebook generates multiple visualizations:

* Average PnL by Sentiment
* PnL Distribution
* Long vs Short Ratio
* Trader Segmentation Performance
* Win Rate Analysis



---

