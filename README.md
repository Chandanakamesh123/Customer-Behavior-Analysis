
# Customer Behavior Analysis

## Project Overview
This project analyzes customer transaction and behavioral data to identify customer segments, purchasing patterns, and churn risks. The analysis helps businesses improve customer engagement, retention, and marketing strategies using data-driven insights.

---

## Objective
The main objectives of this project are:

- Perform data cleaning and preprocessing
- Conduct exploratory data analysis (EDA)
- Apply feature engineering techniques
- Segment customers using clustering techniques
- Analyze customer churn risks
- Visualize purchasing patterns and customer behavior
- Provide actionable business recommendations

---

## Dataset
Dataset Source:

https://www.kaggle.com/datasets/bhanupratapbiswas/customer-behavior-analysis

Files Used:
- ecommerce_customer_data_large.csv
- ecommerce_customer_data_custom_ratios.csv

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```text
Customer-Behavior-Analysis/
│
├── data/
│   ├── ecommerce_customer_data_large.csv
│   ├── ecommerce_customer_data_custom_ratios.csv
│   └── processed_customer_behavior.csv
│
├── notebook/
│   └── Customer_Behavior_Analysis.ipynb
│
├── visuals/
│   ├── distribution_plot.png
│   ├── correlation_heatmap.png
│   ├── customer_segmentation.png
│   └── churn_analysis.png
│
├── report/
│   └── Customer_Behavior_Report.pdf
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Features Implemented

### Data Cleaning
- Removed duplicate records
- Handled missing values
- Checked dataset consistency

### Exploratory Data Analysis
- Statistical analysis
- Distribution analysis
- Correlation heatmaps
- Customer behavior visualization

### Feature Engineering
Created important customer behavior metrics such as:
- Frequency
- Monetary value
- Customer segments
- Churn risk labels

### Customer Segmentation
Applied K-Means clustering to group customers into different behavioral segments.

### Churn Analysis
Identified customers with higher churn risks based on purchasing frequency and spending behavior.

---

## Visualizations
The project includes:
- Distribution plots
- Correlation heatmaps
- Customer segmentation scatter plots
- Churn analysis graphs

---

## Business Recommendations

1. Personalized marketing campaigns
2. Loyalty reward programs
3. Re-engagement strategies for inactive customers
4. Product recommendation systems
5. Seasonal promotional campaigns

---

## How to Run the Project

### Step 1 — Clone Repository

```bash
git clone https://github.com/yourusername/Customer-Behavior-Analysis.git
```

### Step 2 — Open Project Folder

```bash
cd Customer-Behavior-Analysis
```

### Step 3 — Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4 — Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:
```text
notebook/Customer_Behavior_Analysis.ipynb
```

---

## Output
The project generates:
- Cleaned dataset
- Customer clusters
- Churn analysis
- Visualizations
- Business insights and recommendations

---

## Conclusion
This project demonstrates how customer analytics and machine learning techniques can help businesses understand customer behavior, improve retention, and optimize marketing strategies through data-driven decision-making.

---

## Author
Chandana
