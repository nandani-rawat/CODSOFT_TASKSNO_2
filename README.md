# 📊 Superstore Sales - Exploratory Data Analysis (Task 2)

## 📌 Description

This project is **Task 2** of my Data Analytics Virtual Internship, focused on performing 
Exploratory Data Analysis (EDA) on the Superstore Sales dataset.

The goal was to clean the raw data, explore relationships between key variables, and 
extract meaningful business insights to support data-driven decision-making.

## 🛠️ Key Steps Performed

- Data cleaning (handled missing values, removed duplicate records)
- Univariate analysis (category-wise distribution using count plots)
- Bivariate analysis (Sales vs Profit scatter plots, category-wise bar charts)
- Correlation analysis using pairplots across all numeric variables
- Aggregated sales and profit insights by product category
- Exported the cleaned dataset for further analysis

## 🧰 Tools & Libraries

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook

## 📈 Key Insights

- The dataset was cleaned successfully by handling missing values and removing duplicate records
- Sales and Profit vary significantly across different product categories and regions
- Some products generate high sales but relatively low profit, indicating lower profit margins
- A few transactions resulted in negative profit, highlighting loss-making sales that need attention
- The Technology category generally performs better in terms of profitability compared to other categories
- Certain regions contribute more to overall sales and profit than others
- The correlation analysis shows that Sales and Profit have a positive relationship, but high sales do not always guarantee high profit
- This Exploratory Data Analysis helped identify important business trends, profitable segments, and areas that require improvement for better decision-making

## 📂 Project Structure

```
superstore-eda-task2/
│
├── README.md
├── Dataset/
│   └── Sample - Superstore.csv           # Original raw dataset
├── Cleaned dataset [Task2]/
│   └── Sample - Superstore[Task2].csv    # Cleaned dataset after EDA
├── Graphs/
│   └── (exported chart images from the analysis)
└── Notebook/
    └── EDA_supersale.ipynb               # Jupyter notebook (EDA code)
```

## ✅ Conclusion

The Exploratory Data Analysis successfully explored the dataset and revealed important 
patterns, relationships, and statistical insights. The analysis provides a better 
understanding of the data and prepares it for further predictive modeling or business analysis.

---

*This project is part of my Data Analytics Virtual Internship journey.*
