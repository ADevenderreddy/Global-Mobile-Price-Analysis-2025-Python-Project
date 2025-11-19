# 📊 **Mobile Market Analysis 2025**

### *A Data-Driven Study on How Smartphone Specifications Influence User Ratings*

---

## 🎯 **Goal**

The objective of this project is to analyze global smartphone specifications, pricing, and user ratings to identify which features significantly impact customer satisfaction.
This analysis provides **insights and recommendations for manufacturers, marketers, and buyers**.

---

## 🔎 **Overview of the Project**

This project explores:

* 📊 Rating distribution across brands and price segments
* 🔋 Effect of battery capacity on ratings
* 💾 Impact of RAM, storage, and charging speed
* 💰 Price vs. rating sweet spots for mid-range and premium devices
* 🌟 Actionable recommendations based on data insights

The analysis includes visualizations, crosstabs, boxplots, and feature comparisons.

---

## 🛠️ **Technologies Used**

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Jupyter Notebook**

---

## 📥 **Dataset**

Dataset: **Global Mobile Prices 2025 Extended**
Contains specifications such as price, RAM, storage, camera, battery, charging wattage, OS, processor, rating, and release month.

---

## 🧹 **Data Preparation**

* Loaded dataset and checked for missing values
* Created **price ranges** and **rating ranges** using binning
* Dropped unused columns to structure the data
* Conducted summary statistics and exploratory analysis

No missing values were found.

---

## 📊 **Analysis Highlights**

### 1️⃣ **Distribution Analysis**

* Count of phones across price ranges
* Rating distribution across different rating segments
* Crosstab: **Price Range vs Rating Range**

### 2️⃣ **Brand Analysis**

* Stacked bar charts showing rating distribution per brand
* Helpful to compare user satisfaction across manufacturers

### 3️⃣ **Feature vs Price & Ratings**

Boxplots used to compare:

* 🔋 Battery
* 💾 RAM
* 🗄️ Storage
* ⚡ Charging watt
* 📸 Camera MP
* 🖥️ Display size

Against both:

* **Price Range**
* **Rating Range**

### 4️⃣ **4G vs 5G Support**

* Crosstab + stacked bar charts comparing 5G support with price and rating categories.

### 5️⃣ **Time-Based Trends**

* Release month vs number of phones released
* Shows seasonal release patterns by price segment

### 6️⃣ **Combined Rating vs Price Analysis**

Normalized crosstab to understand:

* Which price segments get the highest ratings
* What customers expect in each price category

---

## 🔍 **Key Insights**

### ⭐ **Major Findings**

* Most phones have ratings between **3.5 – 4.5**.
* Phones priced **$700–$900** tend to receive **higher ratings**.
* Battery capacity below **4500 mAh** is linked to lower ratings.
* RAM **< 8 GB** and storage **< 256 GB** lead to reduced user satisfaction.
* Charging speed **≥ 45W** improves overall ratings.
* 5G phones dominate premium price brackets and higher rating segments.

---

## 🧾 **Conclusion**

This analysis reveals that **battery life, RAM, storage, and charging speed** strongly influence smartphone ratings.
Mid-range devices consistently offer the best balance between **performance and user satisfaction**, making them a key target for manufacturers.

The project provides actionable insights to:

* Smartphone manufacturers
* Marketing teams
* Retail pricing strategists
* Tech reviewers and analysts

---

## 📂 **Project Structure**

```
├── Global_Mobile_Prices_2025_Extended.csv
├── analysis.ipynb
└── README.md
```
