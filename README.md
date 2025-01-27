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

### **Findings: General Overview**  

#### **Customer Demographics**  
- The majority of the customers were **young adults (37.12%)**, followed closely by **middle-aged adults (36.58%)**.  
- **Older adults (21.68%)** and **teenagers (4.62%)** made up smaller portions of the customer base.  
- The **average customer age** was calculated to be **38 years and 7 months**.  

#### **Purchase Channels**  
- A significant proportion of customers, **68.1%**, made their purchases through **online channels**, while **31.9%** purchased offline.  

#### **Customer Satisfaction**  
- The **average satisfaction rating** across all customers was **3 out of 5**, indicating room for improvement in overall customer experience.  

#### **Payment Methods**  
- The most commonly used payment method was **equated monthly installments (21.78%)**, followed by:  
  - **Debit cards (20.96%)**  
  - **Credit cards (19.42%)**  
  - **Cash (18.92%)**  
  - **Unified Payments Interface (18.92%)**  

#### **Regional Distribution**  
- Customers were distributed across major cities in India as follows:  
  - **Hyderabad**: 11.32%  
  - **Chennai**: 11.52%  
  - **Ahmedabad**: 11.30%  
  - **Kolkata**: 11.08%  
  - **Delhi**: 11.22%  
  - **Mumbai**: 11.22%  
  - **Pune**: 11.22%  
  - **Jaipur**: 10.34%  
  - **Bangalore**: 10.78%  

These findings provided valuable insights into the client’s customer base, purchasing patterns, and regional distribution, setting the stage for informed sales strategies in 2025.  
