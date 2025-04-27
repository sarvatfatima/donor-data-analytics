# 🧠 Donor Data Analytics Project (Python + SQL)

This project showcases a full-stack data analytics workflow on a fictional donor dataset using **Python** and **SQL**. It’s built to demonstrate the skills of a **beginner data analyst** including data cleaning, exploratory data analysis, SQL querying, visual storytelling, and segmentation modeling.

---

## 📦 Dataset Overview

The [dataset](https://www.kaggle.com/datasets/gaurobsaha/customer-relationship-management-dataset) contains records of donors, including:

- Contact information (name, email, phone, city, state, ZIP)
- Donation behavior (total gifts, donation amount, last donation date)
- Engagement metrics (event participation, engagement score)

### Sample Columns:
- `DonorID`
- `FirstName`, `LastName`
- `Email`, `Phone`, `City`, `State`
- `LastDonationDate`, `TotalGifts`, `TotalAmountDonated`
- `EngagementScore`, `EventParticipation`

---

## 🛠️ Tools & Technologies

| Tool            | Use Case                          |
|----------------|------------------------------------|
| Python (Pandas) | Data wrangling, analysis           |
| SQLite          | SQL querying (via Python)          |
| Matplotlib/Seaborn | Visualization                  |
| Jupyter Notebook | Interactive analysis notebook     |
| Plotly (optional) | Interactive maps & plots         |
| Scikit-learn     | Donor segmentation (clustering)   |

---

## 📊 Key Features & Insights

### 🔍 Data Cleaning & Setup
- Parsed and standardized phone numbers, ZIP codes, and dates
- Converted data to SQL and queried using SQLite

### 📈 Exploratory Data Analysis (EDA)
- Top donors by total amount and frequency
- Geographic distribution of donors (by state)
- Email domain analysis
- Donation seasonality and monthly trends
- Event participation impact on donation behavior

### 🧠 Advanced Analytics
- Engagement vs Donation correlation
- Donor churn vs retention analysis
- Clustering using KMeans to group donor personas

### 📍 Visualization Highlights
- Bar charts, scatter plots, pie charts
- Line plots for trend analysis

---
