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

![supermarket](https://github.com/user-attachments/assets/fa04ac7a-0f60-4d41-8626-52d511616635)

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
git clone https://github.com/TheMrityunjayPathak/Supermarket-Sales-Analysis.git
```

## Steps involved in the Project

**Importing Libraries**

  - Importing Pandas, Matplotlib and Seaborn Libraries
 
**Reading CSV File**

  - Reading CSV File by using pd.read_csv() function
 
**Overview of the Dataset**

  - Information about shape and size of the Dataset

  - Columns present in the Dataset

  - Info about the Dataset

**Handling Null values in the Dataset**

  - This dataset does not contain any Null Values
 
**Unique values in Each Categorical Column**

  - Unique values in Customer Name Column
 
  - Unique values in Category Column
 
  - Unique values in Sub Category Column
 
  - Unique values in City Column
 
  - Unique values in Region Column
 
**Changing DataType of Columns**

  - Modifying the DataType of OrderDate column to Pandas DateTime Format

**Utilizing existing information to create new Columns**

  - Extracting Year, Month and Dates from OrderDate Column
 
  - Extracting Discount Amount from Discount Percent by using Mathematical Formulas
 
**Statistical Analysis**

  - No. of Products sold in each Category
    
  - No. of Products sold in each Sub Category
 
  - No. of Products sold in each City
 
  - No. of Products sold in each Region
 
  - No. of Products sold each Year, Month and Date etc.
 
**Data Visualization**

  - No. of Products sold in each Category
  
![download](https://github.com/user-attachments/assets/201f08b8-b5c0-44db-bd8a-d9eb8f82a76e)

  - No. of Products sold in each Sub Category
  
![download](https://github.com/user-attachments/assets/47c85913-0d7c-4bed-961a-62c4846497b3)

  - No. of Products sold in each City
  
![download](https://github.com/user-attachments/assets/0971cebf-5d67-42d6-886d-1aa4cafcd353)

  - No. of Products sold in each Region
  
![download](https://github.com/user-attachments/assets/f4e9ad6c-f9c5-427a-8162-4f027224690e)

  - No. of Products sold each Year

![download](https://github.com/user-attachments/assets/390b92f8-503b-4385-bb75-c58f18db810e)

  - No. of Products sold each Month
    
![download](https://github.com/user-attachments/assets/17c52c47-ab03-406e-967e-94555f553a9e)

  - No. of Products sold each Date

![download](https://github.com/user-attachments/assets/f5349f07-3b08-4133-8b4e-f5d3b5d4483f)

  - Total sales in each Category

![download](https://github.com/user-attachments/assets/a891f53a-093a-41d6-b09f-d27a38691ea8)

  - Total sales in each Sub Category

![download](https://github.com/user-attachments/assets/1a07ab89-3373-44ca-8810-34fc97638766)

  - Total sales in each Region

![download](https://github.com/user-attachments/assets/cd927051-d2db-400c-8d5e-804476163c22)

  - Total sales in each City
  
![download](https://github.com/user-attachments/assets/0bbcafa6-6734-4a84-ac77-d40a108f8b26)

  - Total sales in each Month

![download](https://github.com/user-attachments/assets/0156845d-6dc3-4bb4-9a82-7ac5b1d510ba)

  - Total sales in each Year

![download](https://github.com/user-attachments/assets/844c3c16-9020-4215-b716-7552e05f67fa)

  - Total profit in each Category

![download](https://github.com/user-attachments/assets/57f1bb11-cba0-4075-b76b-8ff7e5bbbfe4)

  - Total profit in each Sub Category
  
![download](https://github.com/user-attachments/assets/70364c48-a0ca-4785-a8db-1b3f2b0845f6)

  - Total profit in each Region

![download](https://github.com/user-attachments/assets/db64f973-16a0-477e-bff5-626182944a5f)

  - Total profit in each City

![download](https://github.com/user-attachments/assets/f3b3794a-3a88-4ef4-8024-830d8ecaacd3)

  - Total profit in each Month
  
![download](https://github.com/user-attachments/assets/d8925469-ae66-4967-aa43-813a5a8e0015)

  - Total profit in each Year

![download](https://github.com/user-attachments/assets/5f063f3d-a5d0-4c25-967f-613bb00cecd9)

  - Customers with Highest Amount of Total Sales

![download](https://github.com/user-attachments/assets/05921566-eadf-4add-9e80-4e1f0fea47a2)

  - Customers with Highest Profit on their Purchase

![download](https://github.com/user-attachments/assets/723fe0a9-420b-4ec7-83c3-52438cb4029a)

  - Total Discount availed by Customers

![download](https://github.com/user-attachments/assets/8dba0aa8-bcb0-420d-8b34-06f59f1f5480)

## Conclusion

- The Exploratory Data Analysis (EDA) of the Supermarket Sales Dataset has provided a comprehensive understanding of the sales dynamics, customer behaviors and regional performance of the supermarket chain.

- This analysis has provided a detailed understanding of various factors influencing supermarket performance.

## Link to the Notebook

[Supermarket Sales Analysis](https://www.kaggle.com/code/themrityunjaypathak/supermarket-sales-analysis)

| [Scroll to Top ⬆️](#supermarket-sales-analysis) |
|:---:|
