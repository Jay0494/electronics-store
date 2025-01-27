# Electronics-store
Here’s a refined version for your portfolio:  

---

### **Introduction**  
An Indian client operating an electronics store since January 2024 approached me to analyze the store's performance in preparation for strategic sales planning in 2025. The goal was to provide actionable insights using Power BI, ensuring the business is well-positioned for growth. To achieve this, I conducted a thorough data analysis process encompassing extraction, transformation, modeling, and visualization.  

---

### **Problem Statement**  
The client required a comprehensive understanding of their store's sales performance, customer demographics, and satisfaction levels. However, the raw data from the store's database contained issues such as duplicates, inconsistencies in data points, irrelevant columns, and an unstructured format, making it unsuitable for direct analysis. Additionally, actionable insights, such as customer age group segmentation and satisfaction categorization, were not readily available in the dataset.  

---

### **Data Processing**  

#### **1. Data Cleaning and Transformation**  
Using **Power Query in Power BI**, I performed the following steps to clean and standardize the data:  
- **Duplicate Removal:** Identified and eliminated duplicate entries to ensure data accuracy.  
- **Standardization:** Standardized data points such as dates, customer names, and product details for uniformity.  
- **Column Renaming:** Renamed columns for better clarity and alignment with analysis requirements.  
- **Unwanted Columns:** Removed irrelevant columns that did not contribute to the analytical goals.  

#### **2. Data Modeling and DAX Calculations**  
After loading the cleaned data into **Power BI Desktop**, I designed a robust data model by creating relationships between tables for seamless analysis. Key calculations and categorizations were implemented using **DAX (Data Analysis Expressions)**:  
- **Customer Age Grouping:** Utilized the `SWITCH(TRUE())` function to categorize customers into age groups (e.g., 18–25, 26–40, 41–60).  
- **Satisfaction Level Categorization:** Developed calculated columns to segment customers based on satisfaction ratings, enabling deeper insights into customer experience trends.  

These transformations and calculations were integral to creating accurate visualizations and driving actionable insights for the client.  
