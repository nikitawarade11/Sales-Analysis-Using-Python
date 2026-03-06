# 📊 Sales Data Analysis Project using Python

Libraries used: PANDAS + NUMPY + MATPLOTLIB + SEABORN



![Libarires](https://github.com/nikitawarade11/Sales-Analysis-Using-Python/blob/main/lib.jpg)

---
## 📌 Project Overview

This project focuses on performing **Sales Data Analysis using Python** to extract meaningful insights from raw sales data. The project demonstrates the complete data analysis workflow including **data cleaning, data preprocessing, exploratory data analysis (EDA), filtering, aggregation, and visualization**.

The analysis was performed using **Pandas, NumPy, Matplotlib, and Seaborn** within **Jupyter Notebook**. The primary goal of this project is to transform raw sales data into meaningful business insights that can support **data-driven decision making**.

The project highlights important **data analytics skills such as data manipulation, filtering, aggregation, visualization, and trend analysis**.

---

# 🎯 Objectives of the Project

The key objectives of this project include:

* Cleaning and preparing raw sales data for analysis
* Performing data filtering and transformation using Pandas
* Exploring the dataset to understand patterns and relationships
* Generating visual insights using data visualization techniques
* Identifying trends in product sales and revenue
* Understanding regional and category-wise sales distribution
* Demonstrating the practical use of Python for data analysis

---

# 🛠️ Technologies and Tools Used

| Tool / Library       | Purpose                                     |
| -------------------- | ------------------------------------------- |
| **Python**           | Programming language used for data analysis |
| **Pandas**           | Data cleaning, manipulation, and analysis   |
| **NumPy**            | Numerical computations                      |
| **Matplotlib**       | Data visualization                          |
| **Seaborn**          | Advanced statistical visualizations         |
| **Jupyter Notebook** | Interactive coding environment              |
| **Excel**            | Dataset source                              |

---


### Explanation of Files

**salepro_clean.ipynb**

* Handles data cleaning operations
* Removes duplicates
* Fixes missing values
* Prepares dataset for analysis

**saleproject_PD.ipynb**

* Performs data manipulation using Pandas
* Aggregates and summarizes data
* Applies groupby operations

**Saleproject_filtering.ipynb**

* Applies filtering techniques
* Extracts specific records based on conditions
* Performs conditional analysis

**saleproject_vis.ipynb**

* Generates visualizations
* Displays charts and graphical insights

**Sales_Project_Data.xlsx**

* Cleaned dataset used for final analysis

**Unclean_Sales_Project_Data.xlsx**

* Raw dataset before cleaning

---

# 🔎 Data Cleaning Process

Data cleaning is an important step in the data analysis pipeline. The raw dataset contained inconsistencies and required preprocessing before analysis.

Key cleaning steps included:

* Handling missing values
* Removing duplicate records
* Correcting incorrect data types
* Standardizing column formats
* Ensuring consistency across data fields

These steps improved the **accuracy and reliability of the dataset** for analysis.

---

# 📊 Data Processing and Analysis

After cleaning the dataset, several **data processing techniques** were applied using **Pandas and NumPy**.

Key operations performed:

* Data filtering
* Sorting values
* Aggregation using groupby
* Calculating summary statistics
* Extracting category-wise sales
* Identifying top performing products

Example operations used in the project include:

```python
import pandas as pd
import numpy as np

df = pd.read_excel("Sales_Project_Data.xlsx")

df.head()
df.describe()
df.info()
```

Example grouping operation:

```python
df.groupby("Product")["Sales"].sum()
```

Filtering example:

```python
df[df["Sales"] > 5000]
```

These operations helped uncover meaningful patterns in the dataset.

---

# 📈 Data Visualization

Visualization is essential for understanding patterns in data. This project uses **Matplotlib and Seaborn** to generate insightful charts.

Common visualizations created in the project include:

* Bar Charts
* Line Charts
* Distribution Plots
* Category-wise Sales Charts
* Product Performance Charts

Example visualization code:

```python
import matplotlib.pyplot as plt
import seaborn as sns

sns.barplot(x="Product", y="Sales", data=df)
plt.xticks(rotation=45)
plt.title("Product-wise Sales Analysis")
plt.show()
```
some outputs are shown as follows:



![output1](https://github.com/nikitawarade11/Sales-Analysis-Using-Python/blob/main/output1.png)

![output2](https://github.com/nikitawarade11/Sales-Analysis-Using-Python/blob/main/output2.png)

![output3](https://github.com/nikitawarade11/Sales-Analysis-Using-Python/blob/main/output3.png)

![output4](https://github.com/nikitawarade11/Sales-Analysis-Using-Python/blob/main/output4.png)

![output5](https://github.com/nikitawarade11/Sales-Analysis-Using-Python/blob/main/output5.png)
These visualizations help interpret complex data and communicate insights effectively.

---

# 📊 Key Insights from the Analysis

The project generated several meaningful insights from the dataset:

* Identification of **top-performing products**
* Understanding of **sales distribution across categories**
* Analysis of **sales trends**
* Detection of **high revenue generating segments**
* Comparison of product performance

These insights demonstrate how data analysis can help businesses make **better strategic decisions**.

---

# ▶️ How to Run the Project

Follow these steps to run the project locally:

### Step 1: Clone the Repository

```
git clone https://github.com/yourusername/Sales-Data-Analysis-Project.git
```

### Step 2: Install Required Libraries

```
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 3: Open Jupyter Notebook

```
jupyter notebook
```

### Step 4: Open and Run the Notebooks

Run the notebooks in this order:

1. Data Cleaning Notebook
2. Data Processing Notebook
3. Data Filtering Notebook
4. Data Visualization Notebook

---

# 💡 Skills Demonstrated

This project demonstrates several important **Data Analyst skills**:

* Data Cleaning
* Data Manipulation
* Data Filtering
* Exploratory Data Analysis (EDA)
* Data Visualization
* Business Insight Generation
* Python Programming

---

# 📌 Use Case of the Project

Sales data analysis helps businesses:

* Identify high performing products
* Understand customer demand patterns
* Improve sales strategies
* Monitor revenue performance
* Make data-driven decisions

This project demonstrates how **Python can be used to perform real-world business analytics**.

---

# 👩‍💻 Author

**Nikita Warade**

Aspiring Data Analyst with hands-on experience in:

* Python
* SQL
* Excel
* Power BI
* Data Visualization
* Machine Learning Basics

Passionate about transforming raw data into actionable insights.

---

# ⭐ If you found this project helpful

Please consider giving this repository a **star ⭐ on GitHub**.
