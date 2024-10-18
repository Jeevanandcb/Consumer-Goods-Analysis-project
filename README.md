# Consumer-Goods-Analysis-project

Project Overview and Problem Statement
Atliq Hardware (imaginary company) is one of the leading computer hardware producers in India and well expanded in other countries too. specializes in selling computers and accessories.

The management noticed that they did not get enough insights to make quick and smart data-informed decisions. However, Tony Sharma (Data Analytics Director ) wants to expand their data analytics team by adding several junior data analysts. So he decided to conduct a SQL challenge which will help him understand both tech and soft skills

Now the company wants insights for 10 ad hoc / business requests.

This project is part of the data analytics boot camp at codebasics.

video presentation link - 

Data Structure/ Data Modeling -
![Screenshot 2024-10-13 195520](https://github.com/user-attachments/assets/d31aa2cb-a8b8-4586-92aa-69f72101c127)

The 'gdb023' (atliq_hardware_db) database was provided to me to work on and it includes six main tables:

dim_customer: contains customer-related data
dim_product: contains product-related data
fact_gross_price: contains gross price information for each product
fact_manufacturing_cost: consists of the cost incurred in the production of each product
fact_pre_invoice_deductions: contains pre-invoice deductions information for each product
fact_sales_monthly: contains monthly sales data for each product.
Here is the Data Model that I have created in Power BI for the Visualization part -

ad hoc data model

Tools used -
I used My SQL to answer the questions
and Power BI for visualization
10 Ad-Hoc Requests and Answers:

1. Provide the list of markets in which customer "Atliq Exclusive" operates its business in the APAC region.

![Screenshot 2024-09-29 165527](https://github.com/user-attachments/assets/196570c5-720d-45b0-94eb-440d9b97d3c9)


2. What is the percentage of unique product increase in 2021 vs. 2020? The final output contains these fields, unique_products_2020, unique_products_2021, percentage_chg
 
![Screenshot 2024-10-13 225027](https://github.com/user-attachments/assets/9323c05e-1411-49f0-92d1-98c566e9b9db) 

3. Provide a report with all the unique product counts for each segment and sort them in descending order of product counts. The final output contains 2 fields, segment product_count
  
![Screenshot 2024-09-29 225500](https://github.com/user-attachments/assets/65f741be-e366-4cc7-a344-a25402de7037)


4. Follow-up: Which segment had the most increase in unique products in 2021 vs 2020? The final output contains these fields, segment product_count_2020, product_count_2021, difference

  ![Screenshot 2024-09-30 115101](https://github.com/user-attachments/assets/d55d12e2-738c-411b-9495-80a69fc16cb4)


5. Get the products that have the highest and lowest manufacturing costs. The final output should contain these fields, product_code, product, manufacturing_cost

  ![Screenshot 2024-09-30 135726](https://github.com/user-attachments/assets/9a891bc2-849d-4bab-b173-dc7034926981)


6. Generate a report that contains the top 5 customers who received an average high pre_invoice_discount_pct for the fiscal year 2021 and in the Indian market. The final output contains these fields, customer_code, customer, average_discount_percentage

  ![Screenshot 2024-10-01 105340](https://github.com/user-attachments/assets/fbbf9639-cb66-41a6-a97d-29787fef8d7e)


7. Get the complete report of the Gross sales amount for the customer “Atliq Exclusive” for each month. This analysis helps to get an idea of low and high-performing months and make strategic decisions. The final report contains these columns: Month, Year, Gross sales Amount
for 2020

![Screenshot 2024-10-06 093131](https://github.com/user-attachments/assets/915f60c3-7afd-435e-a3f3-5403ed2e3d07)


8. In which quarter of 2020, got the maximum total_sold_quantity? The final output contains these fields sorted by the total_sold_quantity, --> Quarter, total_sold_quantity

![Screenshot 2024-10-14 132506](https://github.com/user-attachments/assets/d098c8f7-0b2e-467f-9c19-6a6df783a275)


9. Which channel helped to bring more gross sales in the fiscal year 2021 and the percentage of contribution? The final output contains these fields --> channel, gross_sales_mln, percentage

![Screenshot 2024-10-14 133936](https://github.com/user-attachments/assets/b46349a1-dd9a-4bf3-9c3f-9bb0623bda9f)

  

10. Get the Top 3 products in each division that have a high total_sold_quantity in the fiscal_year 2021? The final output contains these fields, division, product_code

![Screenshot 2024-10-14 134044](https://github.com/user-attachments/assets/9f387ed8-63c4-4b40-b746-11aa6c900df6)



===============================================================================================================
