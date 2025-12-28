# Uber Data Analysis – Data Science Project

## 📌 Project Overview
This project analyzes Uber trip data to identify demand patterns, peak hours, and usage trends using data science techniques. The goal is to help Uber improve driver allocation, pricing strategies, and customer experience.

## 🎯 Business Problem
Uber experiences fluctuating demand throughout the day. Without accurate demand prediction, this leads to longer passenger wait times, inefficient surge pricing, and poor driver utilization.

## 📊 Dataset
- Source: Public Uber Trip Dataset (NYC)
- Data includes trip timestamps, location coordinates, and trip counts
- Raw data contained missing values and inconsistent timestamps

## 🧹 Data Cleaning
- Removed duplicate records
- Handled missing values
- Converted DateTime into structured format
- Extracted time-based variables

## 🔍 Exploratory Data Analysis
- Identified peak hours (8–10 AM, 5–8 PM)
- Higher demand observed on weekdays
- Friday evenings showed increased trip volume

## ⚙️ Feature Engineering
- Hour of day
- Day of week
- Month
- Peak hour indicator

## 🤖 Modeling
- Models tested: GLM and Random Forest
- Final model: Random Forest
- Evaluation metric: RMSE

## 📈 Results
Random Forest captured non-linear demand patterns effectively and performed better than baseline models.

## 💡 Business Recommendations
1. Increase driver availability during peak hours
2. Apply smarter surge pricing during high-demand periods
3. Use demand forecasting for operational planning

## 🛠 Tools & Libraries
- R
- tidyverse
- ggplot2
- lubridate
- caret
- randomForest

## 👥 Team Collaboration
This project was completed collaboratively. Each team member contributed code and commits to the repository.

## 📂 Repository Structure
