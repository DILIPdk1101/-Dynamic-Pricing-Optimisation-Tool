# Dynamic Pricing Optimisation Tool

This project uses machine learning to recommend the optimal selling price of a product that maximises **profit margin**, based on product attributes, stock levels, and discount strategy. Built using **Python** and deployed with **Streamlit**, the tool simulates multiple price points and predicts margin using a trained **Gradient Boosting Regressor**.

---

##  Project Overview

**Goal:** Help businesses make smarter pricing decisions by predicting the selling price that yields the highest margin.

**Scenario:** A retail/manufacturing company wants to analyse SKU-level data (cost, stock, price, discount, etc.) and optimise their pricing strategy using AI/ML.

---

##  Tools & Technologies

- **Python**: Data simulation, model training, and prediction
- **Scikit-learn**: Machine Learning (Gradient Boosting Regressor)
- **Pandas & NumPy**: Data manipulation
- **Matplotlib**: Visualisation
- **Streamlit**: Web app for user interaction
- **Joblib**: Model saving/loading

---

##  Features

- Simulate a range of **selling prices** for a product
- Predict the **profit margin** at each price
- Identify the **optimal price** that maximises margin
- Visualise margin vs. price in an interactive chart
- **Download** simulation results as CSV

---

##  Streamlit App

The app allows users to:
- Input product details (e.g. category, brand, stock, cost)
- Simulate different prices and view predicted margins
- Get a **recommended price** for maximum profit
