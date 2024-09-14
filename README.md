## Supermarket Sales Analysis

Grocery Stores are a vital part of everyday life, providing us with the food and essentials as we need. Many people utilizes grocery delivery applications to order their products making it easy to shop from home. 

Each transaction made through these applications is recorded in detail creating a valuable dataset. This project looks at data from these transactions to understand how well these stores are performing. 

## Dataset

The dataset is sourced from Kaggle which simulates grocery sales activities within Tamil Nadu state of India.

The dataset includes various columns that provide detailed information about each transaction at the Supermarket.

**Link to the Dataset :** [Supermarket Sales Dataset](https://www.kaggle.com/datasets/mohamedharris/supermart-grocery-sales-retail-analytics-dataset)

## Problem Statement

- To gain insights into Supermarket Sales Performance understanding the patterns and trends in customer behavior, product categories and regional sales.

- This Exploratory Data Analysis (EDA) aims to address the following key questions :

  - **Customer Behavior Analysis :** What are the purchasing patterns of customers based on different categories and sub-categories? How does customer spending vary across cities and states?

  - **Sales Trends :** Are there observable trends in sales over time? How do sales figures fluctuate across different months or seasons?

  - **Discount Impact :** What is the relationship between discounts and sales? How do discounts influence the profit margins across different categories and regions?

  - **Profit Analysis :** What are the profit margins associated with various product categories and sub-categories? How do these margins vary by city and state?

  - **Regional Performance :**  How do sales and profit performance differ across different regions and states? Are there specific regions that contribute more significantly to overall sales and profits?

  - **Category Insights :** What are the most and least popular product categories and sub-categories? How does the popularity of these categories vary by location and over time?

- This analysis will provide a deeper understanding of supermarket sales dynamics revealing trends and patterns that can inform inventory management, promotional strategies and regional marketing efforts.

![Supermarket](https://github.com/user-attachments/assets/25b4d12a-b1ec-4d33-b939-3dfb9bdfdeb4)

## Table of Contents

- [Setting up the Enviroment](#setting-up-the-enviroment)
- [Libraries required for the Project](#libraries-required-for-the-project)
- [Getting started with Repository](#getting-started)
- [Steps involved in the Project](#steps-involved-in-the-project)
- [Conclusion](#conclusion)
- [Link to the Notebook](#link-to-the-notebook)

## Setting up the Enviroment

Jupyter Notebook is required for this project and you can install and set it up in the terminal.

- Install the Notebook
```
pip install notebook
```

- Run the Notebook
```
jupyter notebook
```

## Libraries required for the Project

**Pandas**

- Go to Terminal and run this Code
```
pip install pandas
```

- Go to Jupyter Notebook and run this Code from a Cell
```
!pip install pandas
```

**Matplotlib**

- Go to Terminal and run this Code
```
pip install matplotlib
```

- Go to Jupyter Notebook and run this Code from a Cell
```
!pip install matplotlib
```

**Seaborn**

- Go to Terminal and run this Code
```
pip install seaborn
```

- Go to Jupyter Notebook and run this Code from a Cell
```
!pip install seaborn
```

## Getting Started

- Clone the repository to your local machine using the following command :
```
git clone https://github.com/TheMrityunjayPathak/Super-Market-Sales-Analysis.git
```

## Steps involved in the Project

- **Importing Libraries**

  - Importing Pandas, Matplotlib and Seaborn Libraries
 
- **Reading CSV File**

  - Reading CSV File by using pd.read_csv() function
 
- **Overview of the Dataset**

  - Information about shape and size of the Dataset

  - Columns present in the Dataset

  - Info about the Dataset

- **Handling Null values in the Dataset**

  - This dataset does not contain any Null Values
 
- **Unique values in Each Categorical Column**

  - Unique values in Customer Name Column
 
  - Unique values in Category Column
 
  - Unique values in Sub Category Column
 
  - Unique values in City Column
 
  - Unique values in Region Column
 
- **Changing DataType of Columns**

  - Modifying the DataType of OrderDate column to Pandas DateTime Format

- **Utilizing existing information to create new Columns**

  - Extracting Year, Month and Dates from OrderDate Column
 
  - Extracting Discount Amount from Discount Percent by using Mathematical Formulas
 
- **Statistical Analysis**

  - No. of Products sold in each Category
    ```
    # Count of products sold in each Category
    df["Category"].value_counts()
    ```
    
  - No. of Products sold in each Sub Category
    ```
    # Count of products sold in each Sub Category
    df["Sub Category"].value_counts()
    ```
 
  - No. of Products sold in each City
 
  - No. of Products sold in each Region
 
  - No. of Products sold each Year, Month and Date
 
  - Total sale in each Category
 
  - Total sale in each Sub Category
 
  - Total sale in each Region
 
  - Total sale in each City
 
  - Total sale in each Month
 
  - Total sale in each Year
 
  - Total profit in each Category
 
  - Total profit in each Sub Category
 
  - Total profit in each Region
 
  - Total profit in each City
 
  - Total profit in each Month
 
  - Total profit in each Year
 
  - Customer's with Highest Total Orders
 
  - Most purchased product from each category by Customer's
 
  - Most purchased product from each sub category by Customer's
 
  - Most order placed from different cities by Customer's
 
  - Most order placed from different regions by Customer's
 
  - Most order placed in different months by Customer's
 
  - Most order placed in different years by Customer's
 
  - Total Discount on each Product Category
 
  - Total Discount on each Sub Product Category
 
  - Total Discount in each Region
 
  - Total Discount in each City
 
  - Total Discount in each Month
 
  - Total Discount in each Year
 
  - Customer's with most Discount
 
  - Sale of Different Category Products Year Wise
 
  - Sale of Different Category Products Month Wise
 
  - Sale of Different Category Products Region Wise
 
  - Profit from Different Category Products Year Wise
 
  - Profit from Different Category Products Month Wise
 
  - Profit from Different Category Products Region Wise
 
  - Percent of Total Revenue spend on Discounts

## Conclusion

## Link to the Notebook

[Supermarket Sales Analysis](https://www.kaggle.com/code/themrityunjaypathak/supermarket-sales-analysis)

| [Scroll to Top ⬆️](#supermarket-sales-analysis) |
|:---:|
