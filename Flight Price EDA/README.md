# Flight Price Prediction: EDA & Feature Engineering

This project focuses on **cleaning and preparing flight price data** for machine learning model training. The main goal is to transform raw flight data into a high-quality, analysis-ready dataset through comprehensive exploratory data analysis (EDA) and feature engineering.

## 📊 Project Overview

- **Dataset:** Flight ticket prices and related features (airline, source/destination, stops, class, duration, etc.)
- **Objective:** Prepare the data for predictive modeling by handling missing values, extracting and transforming features, and encoding categorical variables.

## 🛠️ Key Steps

1. **Exploratory Data Analysis (EDA):**
   - Inspected data types, missing values, and statistical summaries.
   - Explored feature distributions and relationships.

2. **Feature Engineering:**
   - Extracted date and time components (day, month, year, hour, minute).
   - Created new features such as `Days Left` until departure.
   - Converted categorical features (e.g., Airline, Source, Destination) using OneHotEncoder.
   - Handled missing values and dropped redundant columns.

3. **Data Export:**
   - Saved the cleaned and processed dataset as `flight-price-processed.csv` for model training.

## 🧩 Features in the Cleaned Dataset

- **Airline:** Name of the airline (encoded)
- **Flight:** Flight code
- **Source City / Destination City:** Departure and arrival cities (encoded)
- **Departure/Arrival Time:** Extracted hour and minute
- **Stops:** Number of stops (numerical)
- **Class:** Seat class (Business/Economy)
- **Duration:** Total travel time (hours)
- **Days Left:** Days between booking and journey
- **Price:** Target variable (ticket price)

---

**Author:** [Miskat Ahmmed]  
**Connect:** [LinkedIn](https://www.linkedin.com/in/miskat-ahmmed)

---

💡 This project demonstrates best practices in data cleaning, data wrangling, feature engineering, and preparing real-world data for machine learning.