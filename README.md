# 🛒 SmartCart Customer Segmentation & Clustering System

An end-to-end unsupervised machine learning project designed to segment retail customers based on demographic attributes, purchasing habits, and product category preferences. This system empowers targeted marketing strategies by grouping customers into distinct behavioral personas.

---

##  Key Features
* **Data Preprocessing & Cleaning:** Handles missing income values via median imputation, cleans outlier birth years, and standardizes feature scales.
* **Feature Engineering:** Aggregates spending across product categories (`MntWines`, `MntMeatProducts`, etc.), total household family sizes, and overall customer lifetime tenures.
* **Unsupervised Clustering:** Implements **K-Means Clustering** backed by exploratory data analysis and distance metric scaling.
* **Actionable Personas:** Translates clusters into business-ready profiles (e.g., High-Value Loyalists, Discount Seekers, Web-Browsing Shoppers).

---

##  Key Findings & Business Insights
After running exploratory data analysis and clustering models on the customer records, several distinct behavioral patterns emerged:

1. **The Income-Spend Divide:** 
   * **High-Income Segments** (top tier) average a total spend of over **$1,260**, heavily concentrating their purchases on premium goods like fine wines and meat products.
   * Conversely, **Low-Income Segments** show an average total spend under **$100**, demonstrating much tighter budget constraints.
2. **Deal Responsiveness & Engagement:** 
   * Mid-income customers rely significantly more on promotional campaigns, registering a higher average count of discount purchases (`NumDealsPurchases`) compared to top earners.
   * High-income customers exhibit lower website visit frequencies but higher conversion rates and larger basket sizes per transaction.

---

## Tech Stack & Libraries
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
├── clustering_model.py          # Main ML pipeline script / Jupyter Notebook
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
```

## ⚙️ Getting Started & Installation

1. **Clone the repository:**

   git clone [https://github.com/Shivam5760/Smart_cart_clustering_system.git](https://github.com/Shivam5760/Smart_cart_clustering_system.git)
   cd Smart_cart_clustering_system
