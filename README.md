# Market Basket Analysis and Recommendation System for Retail Grocery Data

This project focuses on performing Market Basket Analysis using a retail grocery dataset. It utilizes association rule mining techniques to uncover relationships between items and build a recommendation system.

---

## 📂 Project Overview

Market Basket Analysis is a data mining technique used to understand customer purchasing behaviors. This project applies the **Apriori algorithm** and **association rules** to analyze transactions, identify frequent itemsets, and provide product recommendations.

---

## 🛠️ Features

- **Data Cleaning**: Handles missing values and removes duplicates.
- **Exploratory Data Analysis**: Visualizes top purchased items.
- **Transaction Encoding**: Transforms data into a binary format suitable for association rule mining.
- **Frequent Itemsets Mining**: Identifies combinations of items frequently purchased together.
- **Association Rule Generation**: Creates rules with metrics such as support, confidence, and lift.
- **Product Recommendation System**: Recommends items based on user-specified products.

---

## 🗂️ Dataset

- **Name**: Groceries Dataset
- **Description**: A collection of transaction records from a retail grocery store.
- **Format**: CSV file with fields like `Member_number` (customer ID) and `itemDescription` (products purchased).
- **Source**: Provided with the project.

---

## 📊 Steps in the Project

1. **Import Libraries**: Load essential Python libraries for data analysis and mining.
2. **Load and Clean Data**:
   - Check and handle missing values.
   - Identify and remove duplicate records.
3. **Exploratory Data Analysis**:
   - Visualize the top 10 purchased items using bar charts.
   - ![download](https://github.com/user-attachments/assets/e9c89c3f-fd80-4070-8c7c-5e8c32ff8587)
4. **Data Transformation**:
   - Convert transaction data into a binary matrix (purchased: 1, not purchased: 0).
5. **Frequent Itemsets Mining**:
   - Apply the Apriori algorithm to find itemsets with a minimum support threshold.
6. **Generate Association Rules**:
   - Derive rules with metrics like confidence and lift.
7. **Build a Recommendation System**:
   - Recommend items based on antecedents and lift scores.

---

## 📈 Outputs

- **Top Purchased Items**: Visual representation of popular products.
- **Frequent Itemsets**: Insights into commonly bought item combinations.
- **Association Rules**: Actionable rules for marketing strategies.
- **Recommendations**: A list of suggested products for a given item.

---

## 🧑‍💻 Technologies Used

- **Python**: For data manipulation, analysis, and visualization.
- **Libraries**:
  - `pandas` and `numpy` for data processing.
  - `mlxtend` for Apriori and association rules.
  - `matplotlib` for visualizations.

---
