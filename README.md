## Supermarket Sales Analysis
- Grocery Stores are a vital part of everyday life, providing us with foods and essentials as we need.
- People often uses grocery delivery applications to order products, making it easy to shop from home.
- Each transaction made through these applications are recorded in detail, creating a valuable dataset.
- This project looks at a same data of a supermarket transactions to understand how well it's performing.

<hr>

## Dataset
- The dataset is sourced from Kaggle which simulates grocery sales within Tamil Nadu state of India.
- The dataset includes columns that provide detailed information about each transaction at the Supermarket.
- **Link to the Dataset :** [Supermarket Sales Dataset](https://www.kaggle.com/datasets/mohamedharris/supermart-grocery-sales-retail-analytics-dataset)

<hr>

## Problem Statement
- To analyze Supermarket Sales data, identifying key factors for improving profitability and operational efficiency.

<hr>

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

<hr>

## Libraries required for the Project
**NumPy**
- Go to the terminal and run this code
```
pip install numpy
```
**Pandas**
- Go to the terminal and run this code
```
pip install pandas
```
**Matplotlib**
- Go to the terminal and run this code
```
pip install matplotlib
```
**Seaborn**
- Go to the terminal and run this code
```
pip install seaborn
```

<hr>

## Getting Started
- Clone this repository to your local machine by using the following command :
```bash
git clone https://github.com/TheMrityunjayPathak/Supermarket-Sales-Analysis.git
```

<hr>

## Steps involved in the Project

**Importing Libraries**
- Importing necessary libraries like numpy, pandas, matplotlib and seaborn.
 
**Reading CSV File**
- Reading CSV file by using pd.read_csv() method.
 
**Overview of the Dataset**
- Information about shape and size of the dataset.
- Types of column present in the dataset (numerical, categorical, text).
- Detailed info about the dataset using df.info() method.

**Handling Null values in the Dataset**
- This dataset does not contain any null values.
 
**Unique values in aach Categorical Column**
- Unique customer names in the data.
- Unique product categories in the data.
- Unique product sub-categories in the data.
- Unique cities in the data.
- Unique regions in the data.
 
**Changing DataType of Columns**
- Modifying the datatype of order_date column to pandas datetime format.

**Utilizing existing information to create new Columns**
- Extracting year, month and dates from order_date column.
- Extracting discount_amount from discount percent column by using mathematical formulas.
 
**Statistical Analysis**
- No. of products sold in each category.
- No. of products sold in each sub category.
- No. of products sold in each city.
- No. of products sold in each region.
- No. of products sold each year, month and date.
 
**Data Visualization**

- No. of products sold in each category.
  
![download](https://github.com/user-attachments/assets/201f08b8-b5c0-44db-bd8a-d9eb8f82a76e)

- No. of products sold in each sub category.
  
![download](https://github.com/user-attachments/assets/47c85913-0d7c-4bed-961a-62c4846497b3)

- No. of products sold in each city.
  
![download](https://github.com/user-attachments/assets/0971cebf-5d67-42d6-886d-1aa4cafcd353)

- No. of products sold in each region.
  
![download](https://github.com/user-attachments/assets/f4e9ad6c-f9c5-427a-8162-4f027224690e)

- No. of products sold each year.

![download](https://github.com/user-attachments/assets/390b92f8-503b-4385-bb75-c58f18db810e)

- No. of products sold each month.
    
![download](https://github.com/user-attachments/assets/17c52c47-ab03-406e-967e-94555f553a9e)

- No. of products sold each date.

![download](https://github.com/user-attachments/assets/f5349f07-3b08-4133-8b4e-f5d3b5d4483f)

- Total sales in each category.

![download](https://github.com/user-attachments/assets/a891f53a-093a-41d6-b09f-d27a38691ea8)

- Total sales in each sub category.

![download](https://github.com/user-attachments/assets/1a07ab89-3373-44ca-8810-34fc97638766)

- Total sales in each region.

![download](https://github.com/user-attachments/assets/cd927051-d2db-400c-8d5e-804476163c22)

- Total sales in each city.
  
![download](https://github.com/user-attachments/assets/0bbcafa6-6734-4a84-ac77-d40a108f8b26)

- Total sales in each month.

![download](https://github.com/user-attachments/assets/0156845d-6dc3-4bb4-9a82-7ac5b1d510ba)

- Total sales in each year.

![download](https://github.com/user-attachments/assets/844c3c16-9020-4215-b716-7552e05f67fa)

- Total profit in each category.

![download](https://github.com/user-attachments/assets/57f1bb11-cba0-4075-b76b-8ff7e5bbbfe4)

- Total profit in each sub category.
  
![download](https://github.com/user-attachments/assets/70364c48-a0ca-4785-a8db-1b3f2b0845f6)

- Total profit in each region.

![download](https://github.com/user-attachments/assets/db64f973-16a0-477e-bff5-626182944a5f)

- Total profit in each city.

![download](https://github.com/user-attachments/assets/f3b3794a-3a88-4ef4-8024-830d8ecaacd3)

- Total profit in each month.
  
![download](https://github.com/user-attachments/assets/d8925469-ae66-4967-aa43-813a5a8e0015)

- Total profit in each year.

![download](https://github.com/user-attachments/assets/5f063f3d-a5d0-4c25-967f-613bb00cecd9)

- Customers with highest amount of total sales.

![download](https://github.com/user-attachments/assets/05921566-eadf-4add-9e80-4e1f0fea47a2)

- Customers with highest profit on their purchase.

![download](https://github.com/user-attachments/assets/723fe0a9-420b-4ec7-83c3-52438cb4029a)

- Total discount availed by customers.

![download](https://github.com/user-attachments/assets/8dba0aa8-bcb0-420d-8b34-06f59f1f5480)

<hr>

## Conclusion
Analyzed purchasing patterns of 9,000+ customers of a Supermarket.
- More than 15% of the products sold were Snacks.
    - Shows that Snacks are a convenient choice and a major source of revenue.
- More than 32% of total sales came from the West region of the Supermarket.
    - Suggests that West region is a strong performing area as compared to others.
- Health and Soft drinks were the most profitable sub-categories in Beverages.
    - Shows that both type of drink options perform well among customers.
- November was the most profitable month contributing about 15% of the total annual profits.
    - Makes it an ideal time for running promotions and special offers.

<div align='left'>
  
**[`^        Scroll to Top       ^`](#supermarket-sales-analysis)**

</div>
