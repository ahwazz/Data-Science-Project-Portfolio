# Predictive Pathways: Unraveling Customer Purchasing Patterns

## 📌 Project Overview

This project focuses on analyzing customer purchasing behavior to uncover meaningful patterns, preferences, and customer segments.

The project is based on a business case from **Intelligo ID**, where an SME client requires customer data analysis to gain deeper insights into purchasing behavior, product preferences, promotional responses, and online shopping activities.

Using Exploratory Data Analysis (EDA) and Machine Learning, this project aims to identify customer segments that can support better business decision-making and marketing strategies.

## 🎯 Project Objectives

- Understand customer characteristics and purchasing behavior.
- Identify patterns and trends through Exploratory Data Analysis (EDA).
- Discover relevant features for customer segmentation.
- Apply clustering algorithms to group customers based on their purchasing behavior.
- Evaluate clustering results and translate findings into meaningful business insights.

## 📂 Dataset Description

The dataset contains customer information covering personal attributes, product purchases, promotional participation, and online shopping behavior.

The dataset consists of four main categories:

| Category | Features |
|---|---|
| People | ID, Year_Birth, Education, Marital_Status, Income, Kidhome, Teenhome, Dt_Customer, Recency, Complain |
| Products | MntWines, MntFruits, MntMeatProducts, MntFishProducts, MntSweetProducts, MntGoldProds |
| Promotion | NumDealsPurchases, AcceptedCmp1–5, Response |
| Place | NumWebPurchases, NumCatalogPurchases, NumStorePurchases, NumWebVisitsMonth |

**Dataset Source:** [Google Drive – Customer Purchasing Patterns Dataset](https://drive.google.com/drive/folders/1s-V9D7s6VfoMjXJ60TNhMZkh13G8cxKH?usp=drive_link)

## 🔍 Methodology

This project follows the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** framework.

### 1. Business Understanding
- Identify business problems related to customer purchasing behavior.
- Define analytical objectives.
- Determine how customer segmentation can support business decisions.

### 2. Data Understanding
- Explore dataset structure and dimensions.
- Examine data types and statistical summaries.
- Identify missing values, duplicates, and potential outliers.
- Perform Exploratory Data Analysis (EDA).
- Visualize customer demographics and purchasing patterns.

### 3. Data Preparation
- Handle missing values and duplicate records.
- Address outliers where necessary.
- Perform feature selection.
- Transform and scale relevant features for clustering.

### 4. Modeling
- Select relevant customer attributes.
- Apply clustering algorithms for customer segmentation.
- Experiment with different clustering approaches.
- Determine the optimal number of clusters.

### 5. Evaluation
- Evaluate clustering performance.
- Interpret the characteristics of each customer segment.
- Assess whether the resulting clusters address the business objectives.

### 6. Deployment
- Present analytical findings through visualizations.
- Translate customer segments into actionable business recommendations.

## 📊 Expected Business Outcomes

The analysis is intended to provide insights into:

- **Customer Segmentation:** Identifying groups of customers with similar characteristics and purchasing behavior.
- **Product Preferences:** Understanding which product categories attract different customer segments.
- **Promotion Effectiveness:** Examining customer responses to promotional campaigns.
- **Purchasing Channels:** Understanding customer preferences across web, catalog, and physical stores.
- **Marketing Strategy:** Providing data-driven recommendations for more targeted marketing activities.

## 🛠️ Tools & Technologies

*To be updated according to the tools actually used in the project.*

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

## 📁 Project Structure

```text
Predictive-Pathways/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_data_preparation.ipynb
│   └── 04_customer_segmentation.ipynb
│
├── visualizations/
│
└── README.md
```

*Note: This is a suggested repository structure and can be adjusted to match the actual project files.*

## 📌 Project Status

Project documentation and analysis are being developed following the CRISP-DM framework.

---

**Project:** Predictive Pathways: Unraveling Customer Purchasing Patterns  
**Focus:** Customer Analytics | Exploratory Data Analysis | Machine Learning | Customer Segmentation  
**Framework:** CRISP-DM
