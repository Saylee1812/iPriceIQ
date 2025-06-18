# 📱 iPriceIQ – Smart iPhone Price Insights & Recommendation Dashboard
iPriceIQ is a smart Streamlit dashboard that analyzes iPhone pricing trends. It predicts sale prices using machine learning and offers top product recommendations. Built with XGBoost, Seaborn, and Plotly for interactive insights.

---

### 📌 Features

* **Interactive Dashboard** built with Streamlit
* **Data Cleaning** and preprocessing of Apple product listings
* **Feature Engineering** including discount computation and engagement scores
* **ML Model** using XGBoost Regressor to predict iPhone prices
* **Top 5 Product Recommendations** based on predicted price, rating, and engagement
* **Rich Visualizations** using Seaborn and Plotly:

  * Price distribution
  * Discount vs Sale Price regression
  * Star Ratings frequency
  * Correlation heatmap
  * Interactive scatter plots

---

### 🧠 Machine Learning

* **Model Used:** XGBoost Regressor
* **Features:**

  * MRP (Maximum Retail Price)
  * Discount Percentage
  * Number of Ratings
  * Number of Reviews
  * Star Rating
  * RAM
* **Target:** Sale Price

---


### 🚀 How to Run

1. **Install dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

2. **Run the Streamlit app:**

   ```bash
   streamlit run apple_dashboard.py
   ```

3. **Explore the Dashboard:**

   * Adjust price range from sidebar
   * View recommended products
   * Explore plots and insights

---


