# Sales Analysis Using Excel


### Project Overview
This project involved collecting and analyzing sales data from multiple regions, markets, and stores. The dataset comprised 30800 records. The primary objective was to generate insights into revenue, units sold, and transaction categories across different time periods. The analysis emphasized identifying revenue trends, evaluating sales performance by region, and calculating essential metrics such as average revenue per region, region by units sold, top 10 stores by revenue, revenue by month, etc.


### Project Significance
This project is crucial for businesses aiming to improve sales strategies and optimize revenue. By analyzing sales data across various regions, markets, and stores, it provides valuable insights into revenue trends, units sold, and transaction categories.

Understanding these trends enables decision-makers to anticipate market demands and adjust strategies effectively. Evaluating sales performance by region highlights areas of strength and opportunities for improvement, while calculating key metrics—such as average revenue per region and top stores by revenue—focuses resources on high-performing segments.

Additionally, analyzing monthly revenue helps businesses plan for seasonal fluctuations. Overall, this project fosters a data-driven approach, supporting strategic planning and enhancing competitiveness in the marketplace.


### Data Sources/ Data Generation

Sales Data: The primary dataset used for this analysis is the "sales_data.csv" file, containing detailed datapoints which include but not limited to sales made by the company across differnet region, market and store with detailed information on units sold and revenue. The dataset was generated from different region, markets and stores.


### Data Structure

The sales dataset employed for this analysis was structured (dataset was in a tabular form). 


### Data Description

The dataset contained the essential datapoints:

- Region: The geographical area or division where the store operated
- Market: The specific place, system, or environment where buyers and sellers interact to exchange goods, services, or financial assets within a region.
- Store: A retail establishment where goods and services are sold directly to consumers from which the sales data was collected.
- Trade Date: The specific date on which a transaction involving the buying or selling was made.
- Fiscal Period: The fiscal quarter the trade was made.
- Model: The product model being sold.
- Line of Business (LOB): The category that defines a particular type of product or service offered.
- Day: The day of the week the transaction was made.
- Revenue: The total monetary value generated from the sale.
- Units Sold: The number of units sold for a given transaction.


### Tools Used
- Microsoft Excel [Download Here](https://www.microsoft.com)
  The dataset was ingested, transformed, visualized, analysed and presented
1) For Data Cleaning: The sales dataset was cleaned to ensure duplicates were removed and ensured all columns were properly
2) For Data Analysis: The dataset was analyzed using Microsoft Excel, statistical measures and techniques were deployed over the dataset
3) For Data Visualization: Charts and graphs were deployed to summarize the dataset such as pivot tables, bar charts etc

### Data Cleaning and Preparation
The initial phase of the data leaning and preparations performed the following actions;

1) Data loading and inspection
2) Handling missing variables
3) Data cleaning and formatting


### Exploratory Data Analysis
EDA involves exploring the Dataset

1) What is the sum of revenue by region?
2) What is the sum of units sold by region?
3) What is the top 10 stores by revenue?
4) What is the bottom 5 stores by units sold?
5) What is the top 5 markets by revenue?
6) What is the line of business by average units sold and revenue?
7) What is the average revenue by region?

### Functions Used
```
Autosum: Sum, Average, MAX, MIN
Logical Functions: IFS, Switch
```

### Data Visualization

#### 1. Revenue by Region
##### Pivot Table: 
![Screenshot 2024-10-30 111111](https://github.com/user-attachments/assets/17241d2a-930f-46bf-b2b1-5ae9c94ff06b)
![Screenshot 2024-10-30 111954](https://github.com/user-attachments/assets/fe97071f-4324-4da3-b8af-37d7b108a442



##### Filtered Pivot Table (Year 2014)
![Screenshot 2024-10-30 113006](https://github.com/user-attachments/assets/4147045e-dc97-497d-a5b1-89f492c187b3)



##### Filtered Chart (Year 2014)
![Screenshot 2024-10-30 112617](https://github.com/user-attachments/assets/606272cb-37ba-4663-a3d4-47bb35b1847e)



##### Filtered Pivot Table (Year 2015)
![Screenshot 2024-10-30 114031](https://github.com/user-attachments/assets/ff6b936e-1a66-4454-9c1b-7f5e8e93f0a0)



##### Filtered Chart (Year 2015)
![Screenshot 2024-10-30 112646](https://github.com/user-attachments/assets/084555fd-d77f-4999-be8a-8f2b0210b8ec)



#### Units Sold by Region
##### Pivot Table:
![Screenshot 2024-10-30 111147](https://github.com/user-attachments/assets/6ac5a7fb-6f57-4861-a978-44a7557360a5)
![Screenshot 2024-10-30 111840](https://github.com/user-attachments/assets/8236265d-8c69-4f3c-805a-0a17b4e8242c)


##### Filtered Pivot Table (Year 2014)
![Screenshot 2024-10-30 113014](https://github.com/user-attachments/assets/8aa348d5-037b-41a0-9c7e-211cc90a4e54)



##### Filtered Chart (2014
![Screenshot 2024-10-30 112742](https://github.com/user-attachments/assets/827f8916-e00d-4cf6-a2fe-d0f420b65391)


##### Filtered Pivot Table (Year 2015)
![Screenshot 2024-10-30 114043](https://github.com/user-attachments/assets/b01d4b41-4779-42a6-b016-014d1ab4afca)


##### Filtered Chart (2015)
![Screenshot 2024-10-30 112757](https://github.com/user-attachments/assets/fac1974a-19e6-439b-a647-d0335ce1923e)

#### Top 10 Stores by Revenue
##### Pivot Table:
<img width="184" alt="image" src="https://github.com/user-attachments/assets/5fe09fbe-43f0-429b-b298-1caa89be52cc">


#### Bottom 5 Stores by Units Sold
##### Pivot Table:
<img width="203" alt="image" src="https://github.com/user-attachments/assets/6a41e23f-d7e1-453c-9ee5-02add044b167">

This showed that Boki has only 2 units sold in 2 years while 4 units were sold in Kwali in 20. A lot of factors could be affecting the sales in those stores which include insurgency, lack of sophiticated machineries, unskilled staffs, remote location and products do not get to those areas as fast as possible or lack of warehouses to store the products. Invesrigation has to be done to ascertain the low sales in those areas to know the intervention plan to put in place

#### Top 5 Markets by Revenue
##### Pivot Table:
<img width="172" alt="image" src="https://github.com/user-attachments/assets/ba0b1f19-7d5a-49f5-ad73-8a26844a27de">


#### Line of Business by Average Units Sold and Revenue
##### Pivot Table:
<img width="315" alt="image" src="https://github.com/user-attachments/assets/c4e8c13c-c857-45ed-a00f-95de26af2c10">



