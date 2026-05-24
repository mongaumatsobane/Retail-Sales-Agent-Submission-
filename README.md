Retail Sales Data Agent

Project Objective
Built a Retail Sales Data Agent on Databricks using Genie Spaces 
to help store managers and staff ask plain-language questions 
about retail sales performance and receive accurate data-backed answers.

Tools Used
- Databricks (Genie Spaces)
- SQL Editor
- Data Ingestion
- GitHub

Dataset Overview
- Table name: retail_sales_data
- 1,000 transactions from January 2023 to January 2024
- 9 columns: transaction_id, date, customer_id, gender, age, 
  product_category, quantity, price_per_unit, total_amount
- 3 product categories: Electronics, Clothing, Beauty
- Total revenue: $456,000

Steps Followed
1. Uploaded retail sales CSV using Data Ingestion
2. Reviewed dataset columns and summary statistics using SQL
3. Created and prepared retail_sales_data table with descriptions
4. Built Retail Sales Insights Agent using Genie Spaces
5. Wrote original agent instructions
6. Tested agent with 10 business questions
7. Validated 3 answers using SQL queries
8. Compiled Word document write-up
9. Pushed all files to public GitHub repository

Agent Instructions
1. Only use data from the retail_sales_data table
2. The table contains specific columns, provide answers relating to those columns
3. Provide answers for the date range only
4. The only applicable gender is Male and Female
5. Age under 18 should be Null
6. Help staff members understand how stock performs
7. Provide answers and calculations for revenue or amount made
8. If answer is unclear refer to store manager or technical manager

Sample Questions Tested
1. What is the total amount made between January and March 2023?
2. Which product was bought the most?
3. How much did the most bought product make?
4. How much did beauty products make?
5. Name all beauty products
6. Which products do male customers buy the most?
7. Which age group buys the most?
8. Which product should be restocked often?
9. What is the average made per each product category?
10. Which products are bought more by females?

Key Insights
- Total 2023 revenue: $456,000
- Electronics was the top revenue category at $156,905
- Female customers outspent male customers ($232,840 vs $223,160)
- May was the strongest month ($53,150)
- September was the weakest month ($23,620)
- The 45-54 age group spent the most at $97,235

Conclusion
Data Agent successfully created and provides accurate results. Validity of answers and instructions tested using SQL. 

Repository Contents
- Word document write-up
- PDF also uploaded as backup for the word document 
- retail_sales_dataset.csv
- README.md
