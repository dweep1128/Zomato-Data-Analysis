# 🍽️ Zomato Data Analysis: Decoding Customer Preferences

![Python](https://img.shields.io/badge/Python-3.8%2B-blue) ![Library](https://img.shields.io/badge/Library-Pandas%20|%20Seaborn-orange) ![Status](https://img.shields.io/badge/Status-Completed-green)

## 📋 Project Overview
This project analyzes Zomato restaurant data to understand the factors affecting restaurant success. By examining variables like **online ordering**, **table booking**, and **approximate cost**, the analysis provides actionable insights into customer behavior and market gaps.

The goal was not just to clean data, but to answer: *"What separates a high-rated restaurant from a failing one?"*

## 🔍 Key Insights (The "Researcher" Findings)
After rigorous EDA and statistical analysis, the following patterns emerged:

* **The "Online" Edge:** Restaurants offering **Online Ordering** showed a statistically higher average rating compared to those that don't. This suggests accessibility is a key driver of customer satisfaction.
* **Dining Dominance:** While delivery is popular, **Dining Out** restaurants received the maximum number of votes, indicating that customers are more engaged (and critical) when visiting in person.
* **The "Safe Zone" Rating:** The majority of restaurants cluster between a rating of **3.5 and 4.0**. Breaking past the 4.0 barrier requires significant differentiation (e.g., Table Booking features).
* **Cost Dynamics:** The average approximate cost for two people is around **₹300**, identifying the "mass market" pricing sweet spot.

## 🛠️ Technical Approach

### 1. Data Cleaning & Optimization
* **Vectorization:** Utilized `NumPy` to handle data cleaning (e.g., converting '4.1/5' to float, removing commas from cost) to avoid slow loops.
* **Handling Nulls:** rigorously treated missing values in critical columns like `rate` and `phone` to ensure statistical integrity.

### 2. Exploratory Data Analysis (EDA)
* **Univariate Analysis:** Analyzed the distribution of costs and ratings to find the market standard.
* **Bivariate Analysis:** Correlated `Online Order` availability with `Rate` to test the hypothesis that digital presence boosts brand value.


## 🚀 How to Run
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/Zomato-Analysis.git](https://github.com/yourusername/Zomato-Analysis.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3.  **Run the Notebook:**
    Open `zomato.ipynb` in Jupyter Lab to explore the interactive analysis.

## 📬 Contact
* **Developer:** Dweep Shishodia
* **Role:** Data Science Undergraduate @ IIT Madras
