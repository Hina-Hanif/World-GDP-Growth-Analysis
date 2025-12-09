# 📊 **Global GDP Exploration – Exploratory Data Analysis (EDA)**

## 🌍 Project Overview

This project performs an in-depth **Exploratory Data Analysis (EDA)** on global GDP growth data.
The dataset contains:

* **Entity** (Country / Region)
* **Code** (Country code)
* **Year**
* **GDP_Obs** (Observed GDP growth %)

The goal is to understand **global GDP trends**, detect **patterns**, visualize **economic fluctuations**, and derive **meaningful insights** useful for policymakers, economists, and researchers.

---

## 📁 **Dataset Description**

| Column      | Description                    |
| ----------- | ------------------------------ |
| **Entity**  | Name of country/region         |
| **Code**    | 3-letter country code          |
| **Year**    | Year (1980 – 2030)             |
| **GDP_Obs** | Observed GDP growth percentage |

Dataset size: **9,620+ rows**

---

## 🧼 **Data Cleaning & Preprocessing**

The following steps were performed:

* Removed missing values
* Checked for duplicates
* Fixed inconsistent country names
* Remove useless columns
* Set correct data types
* Handled outliers using visualization
* Sorted dataset by Year

---

## 🎨 **EDA Visualizations**

This project includes several **beautiful and colorful graphs** to study GDP patterns:

### 🔹 1. Distribution of GDP Growth

* Histogram + KDE
* Boxplot
* Violin plot

### 🔹 2. Country-wise GDP Trends

* Line plots
* Multiple time-series comparison

### 🔹 3. Year-wise Global GDP Trends

* Yearly aggregated line chart
* Rolling average trend

### 🔹 4. Top & Bottom Performing Countries

* Bar charts / Lollipop charts

### 🔹 5. Outlier Detection

* Scatter plot
* Boxplot per region

---

## 📷 **Selected Graph Outputs**

Below are some key visualizations from the project:


```
![GDP Trend](../plots/time_series_sample_entities.png)
![Median GDP](../plots/heatmap_entity_decade.png)
![Country Comparison](../plots/highlight_trend.png)
![Top Countries](../plots/small_multiples_top12.png)
```

---

## 📌 **Key Insights**

* Global GDP shows strong fluctuations around major events (financial crises, pandemics, etc.)
* Some countries maintain high and stable growth (e.g., China, India).
* Some regions show long-term decline.
* Extreme outliers represent recessions or extraordinary booms.

---

## 🛠️ **Technologies Used**

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Plotly 
* Jupyter Notebook

---

## 📘 **How to Run the Project**

```bash
pip install pandas matplotlib seaborn plotly numpy
jupyter notebook
```

Open the notebook and run all cells.

---

## 🎯 **Conclusion**

This project reveals important economic patterns across the world.
It also demonstrates practical data analysis skills including:

* Data cleaning
* Feature understanding
* Visualization
* Insight extraction

This EDA can serve as a foundation for future **forecasting using machine learning models**.

---

## ⭐ **If you like this project…**

Give it a **star ⭐ on GitHub** — it motivates me to create more amazing data projects!

---

## Author 
Hina Hanif
