# E-Commerce Sales Data Cleaning & Analysis using Pandas

## Project Overview
This project was created as part of my learning journey in data analytics.  
I worked on cleaning and analyzing raw e-commerce sales data using Python Pandas to understand how real-world data problems are handled and how meaningful insights are extracted from messy data.

The focus of this project is on **data cleaning, basic analysis, and understanding relationships between variables**.


## Project Objectives
- Load and inspect raw e-commerce sales data  
- Identify and handle missing values  
- Fix incorrect data formats (especially dates)  
- Remove duplicate and invalid records  
- Create a new Sales column for analysis  
- Analyze sales based on category and city  
- Understand correlations between numerical variables  

---

## Tools & Technologies Used
- **Python**
- **Pandas**
- **Google Colab**
- **GitHub**



## Dataset Description
The dataset contains e-commerce order information with the following columns:

- `Order_ID` – Unique order identifier  
- `Order_Date` – Date when the order was placed  
- `City` – Customer city  
- `Category` – Product category  
- `Price` – Price of the product  
- `Quantity` – Number of units sold  
- `Discount` – Discount applied  

The dataset intentionally includes common real-world issues such as:
- Missing values  
- Duplicate records  
- Mixed date formats  
- Invalid values like negative price and zero quantity  



## Data Cleaning Steps
The following cleaning steps were performed using Pandas:

- Filled missing values in the Discount column  
- Converted Order_Date to proper datetime format  
- Removed duplicate records  
- Removed invalid rows where:
  - Price was negative  
  - Quantity was zero  

These steps ensured the data was accurate and reliable for analysis.



## Data Analysis Performed
- Created a new `Sales` column (`Price × Quantity`)  
- Calculated total sales  
- Analyzed sales by:
  - Product category  
  - City  
- Performed correlation analysis between:
  - Price
  - Quantity
  - Discount
  - Sales  



## Key Insights
- Electronics category generated higher total sales compared to Clothing.
- I observed that higher quantity orders resulted in higher sales.
- Discounts did not show a strong impact on total sales in this dataset.
- Proper data cleaning was necessary to avoid incorrect analysis.



## Project Structure
Ecommerce-Sales-Analysis-Pandas
│
├── Ecommerce_Sales_Analysis.ipynb
└── README.md


## Conclusion
This project helped me gain hands-on experience with real-world data cleaning and analysis using Pandas.  
It strengthened my understanding of how data analysts prepare raw data before performing analysis and drawing insights.



## Author
**Sushmita**  


 
