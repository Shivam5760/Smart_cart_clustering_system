# 🛒 SmartCart Customer Segmentation & Clustering System

An end-to-end unsupervised machine learning project designed to segment retail customers based on demographic attributes, purchasing habits, and product category preferences. This system empowers targeted marketing strategies by grouping customers into distinct behavioral personas.

---

##  Key Features
* **Data Preprocessing & Cleaning:** Handles missing income values via median imputation, cleans outlier birth years, and standardizes feature scales.
* **Feature Engineering:** Aggregates spending across product categories (`MntWines`, `MntMeatProducts`, etc.) and calculates total household family sizes and customer tenures.
* **Unsupervised Clustering:** Implements **K-Means Clustering** backed by exploratory data analysis and distance metric scaling.
* **Actionable Personas:** Translates clusters into business-ready profiles (e.g., High-Value Loyalists, Discount Seekers, Web-Browsing Shoppers).

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.x
* **Data Manipulation & Analysis:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (`StandardScaler`, `KMeans`)
* **Visualization:** Matplotlib, Seaborn

---

## 📂 Project Structure
```text
smartcart-clustering/
│
├── smartcart_customers.csv      # Raw customer dataset
├── clustering_model.py          # Main ML pipeline script (preprocessing & K-Means)
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
