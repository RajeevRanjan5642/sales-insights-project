# Sales Insights Data Analysis Project

## Problem Statement

AtliQ Hardware, a company supplying computer hardware and peripherals to clients such as Surge Stores, Nomad Stores, etc., operates across India with its head office in Delhi and several regional offices.

The Sales Director of AtliQ Hardware faces significant challenges in a dynamically growing market. Tracking sales performance and understanding business growth trends have become increasingly difficult, especially as overall sales have been declining. With regional managers overseeing North India, South India, and Central India, the Sales Director relies on verbal updates from these managers to gain insights into regional sales performance. However, these verbal reports lack concrete data and fail to provide a comprehensive view of the business, leading to frustration and an inability to make informed, data-driven decisions.

To address this issue, the Sales Director needs a simple data visualization tool that can be accessed daily. Such a tool will enable him to visualize sales data clearly, track regional performance, and make informed decisions to drive business growth.

This project aims to develop a sales-related dashboard using Power BI for AtliQ Hardware. By leveraging this technology, the company can make data-driven decisions that will help increase sales and improve overall business performance.

## Project Execution Flow
![Image](https://github.com/user-attachments/assets/ad59f63a-b6a1-4c34-a657-bb443bb31222)

## Data Analysis using MySQL Workbench

Sales Data is available in the form of SQL database dump.

- Importing data into MySQL Workbench.

![Image](https://github.com/user-attachments/assets/42cb1dc1-b4c1-4240-9519-56d7bbefb828)

- Analyze each table in the sales database.

      USE sales;
      SELECT * FROM transactions;
      SELECT * FROM customers;
      SELECT * FROM date;
      SELECT * FROM markets;
      SELECT * FROM products;

- Get the total no. of transactions.

      SELECT COUNT(*) FROM transactions;

- Get the total no. of customers.

      SELECT COUNT(*) FROM customers;

- Get the total no. of products.

      SELECT COUNT(*) FROM products;

- Get the total no. of markets.

      SELECT COUNT(*) FROM markets;

- In which different currencies transactions have been made?

      SELECT DISTINCT currency FROM transactions;      
      
      

  

