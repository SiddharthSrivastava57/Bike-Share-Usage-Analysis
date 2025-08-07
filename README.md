# 🚲 Bike Sharing Usage Analysis

This project analyzes bike-sharing usage data to understand demand patterns and build a regression model to predict the number of bikes rented per hour. The objective is to gain insights from historical data and forecast usage based on features like time, weather, and working days.

---

## 🧰 Tech Stack

- **Python** – Data analysis, feature engineering, modeling
- **Jupyter Notebook** – Interactive coding and exploration
- **Pandas, NumPy** – Data manipulation and processing
- **Matplotlib, Seaborn** – Visualization
- **Scikit-learn** – Machine Learning (Linear Regression, Random Forest, Decision Tree)
- **Tableau** – Visual storytelling and dashboard

---

## 📁 Dataset Overview

The dataset contains hourly data on bike rentals with the following key features:

- `datetime`: Hourly timestamp  
- `season`: Season (1: Spring, 2: Summer, 3: Fall, 4: Winter)  
- `holiday`: Whether the day is a holiday  
- `workingday`: Whether the day is a working day  
- `weather`: Weather condition (1 = Clear, 4 = Severe)  
- `temp`: Normalized temperature  
- `humidity`: Normalized humidity  
- `windspeed`: Normalized wind speed  
- `casual`: Count of casual users  
- `registered`: Count of registered users  
- `count`: Total number of rentals (target variable)  

---

## 🎯 Objective

- Analyze patterns in bike rental usage based on time and weather  
- Build a machine learning model to predict hourly demand  
- Visualize key insights using Tableau  

---

## 🔄 Project Workflow

1. **Data Cleaning & Preprocessing**
   - Extracted time-based features from `datetime`
   - One-hot encoded categorical columns
   - Removed irrelevant columns and outliers

2. **Exploratory Data Analysis (EDA)**
   - Trends by hour, season, weather
   - Comparison of casual vs registered usage
   - Correlation heatmaps and line plots

3. **Model Building**
   - Trained Linear Regression, Decision Tree, and Random Forest
   - Evaluated using RMSE and R² score
   - Selected best model based on prediction accuracy

4. **Visualization**
   - Created Tableau dashboard to show seasonal and hourly trends

---

## 🛠 How to Run

```bash
# Clone the repo
git clone https://github.com/SiddharthSrivastava57/Bike-Share-Usage-Analysis
cd cd Bike-Share-Usage-Analysis

# Create and activate virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the Jupyter Notebook
jupyter notebook
