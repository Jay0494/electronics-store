# Electronics-store Project
---
## Table Of Contents:

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Stakeholder Report](#stakeholder-report)
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

Note: These transformations and calculations were integral to creating accurate visualizations and driving actionable insights for the client.  

### **Findings**  

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

 

#### **Satisfaction by Age Group**  
The analysis revealed distinct satisfaction trends among different age groups:  

- **Young Adults (37.12% of the customer base):**  
  - **Very Dissatisfied:** 7.72%  
  - **Dissatisfied:** 7.64%  
  - **Neutral:** 7.66%  
  - **Satisfied:** 6.72%  
  - **Very Satisfied:** 7.38%  

- **Middle-Aged Adults (36.58% of the customer base):**  
  - **Very Satisfied:** 7.68%  
  - **Satisfied:** 7.00%  
  - **Neutral:** 7.60%  
  - **Dissatisfied:** 7.40%  
  - **Very Dissatisfied:** 6.90%  

- **Older Adults (21.68% of the customer base):**  
  - **Very Satisfied:** 4.52%  
  - **Satisfied:** 4.28%  
  - **Neutral:** 4.32%  
  - **Dissatisfied:** 4.34%  
  - **Very Dissatisfied:** 4.22%  

- **Teenagers (4.62% of the customer base):**  
  - **Very Satisfied:** 0.82%  
  - **Satisfied:** 0.86%  
  - **Neutral:** 0.94%  
  - **Dissatisfied:** 0.94%  
  - **Very Dissatisfied:** 1.06%  

#### **Customer Gender Distribution**  
- **57%** of the customers were **male**, while **43%** were **female**.

### **Product Insights**  

#### **Demand by Product Category**  
- **Entry-Level Laptops:** The most in-demand category, accounting for **35.36%** of total purchases.  
- **Mid-Range Laptops:** Ranked second, with **29.96%** of purchases.  
- **Budget Laptops:** Represented **15.54%** of sales.  
- **Premium Laptops:** Accounted for **14.58%** of purchases.  
- **High-End Laptops:** Had the smallest share at **4.56%**.  

#### **Brand Performance by Category**  

- **Entry-Level Laptops:**  
  - **Lenovo** was the most purchased brand.  
  - **Customer Sentiment:**  
    - **Dissatisfied:** 1.28% of customers.  
    - **Satisfied:** 0.76% of customers (lowest satisfaction level among this category).  

- **Mid-Range Laptops:**  
  - **Lenovo** again dominated purchases in this category.  
  - **Customer Sentiment:** A higher percentage of customers were dissatisfied compared to other brands in this segment.  

- **Budget Laptops:**  
  - **Samsung** was the top-performing brand.  
  - **Customer Sentiment:** A higher percentage of customers reported being satisfied with their purchase.  

- **High-End Laptops:**  
  - **Asus** emerged as the most purchased brand in this category.  
  - **Customer Sentiment:** A significant proportion of customers felt neutral about their purchase.  

- **Premium Laptops:**  
  - **Lenovo** led in sales within this category as well.  
  - **Customer Sentiment:** A higher percentage of customers expressed dissatisfaction compared to other brands in this segment.
 
    ### **Recommendations**  
---

#### **1. Address Customer Dissatisfaction**  
- **Focus on Lenovo Laptops:**  
  - Since Lenovo is the most purchased brand in entry-level, mid-range, and premium laptop categories, addressing dissatisfaction is critical.  
  - Conduct a detailed review of customer feedback to identify specific pain points, such as product quality, after-sales service, or price-to-value perception.  
  - Collaborate with Lenovo to resolve these issues and consider running customer education campaigns (e.g., highlighting key features or support resources).  

- **Entry-Level and Premium Segments:**  
  - With dissatisfaction levels higher in these categories, consider offering extended warranties, attractive exchange offers, or post-purchase support to improve customer sentiment.  

---

#### **2. Leverage High-Satisfaction Brands**  
- **Promote Samsung Laptops in Budget Category:**  
  - Highlight Samsung’s high satisfaction ratings in marketing campaigns to attract more budget-conscious customers.  
  - Offer bundled deals or discounts to further enhance Samsung’s appeal in this category.  

- **Capitalize on Asus for High-End Laptops:**  
  - Customers were largely neutral toward Asus purchases in the high-end category. To boost satisfaction, emphasize exclusive features, premium build quality, and additional perks like premium customer support.  

---

#### **3. Enhance Customer Experience Across Channels**  
- **Online vs. Offline Strategy:**  
  - Since **68.1% of sales occur online**, ensure that the online shopping experience is seamless by optimizing website performance, offering detailed product descriptions, and providing live customer support.  
  - For offline stores, enhance the in-store experience through personalized assistance, demo units, and exclusive in-store promotions to close the gap with online sales.  

- **Satisfaction Improvement:**  
  - With an average satisfaction rate of **3/5**, identify common dissatisfaction drivers and implement strategies to address them, such as improved packaging, faster delivery, or simplified return processes.  

---

#### **4. Targeted Demographic Strategies**  
- **Young and Middle-Aged Adults (73.7% of Customers):**  
  - As the largest customer groups, create tailored marketing campaigns highlighting features relevant to their needs, such as performance, productivity, and value for money.  
  - Offer loyalty programs or exclusive discounts to encourage repeat purchases among these age groups.  

- **Teenagers and Older Adults:**  
  - With smaller market shares and lower satisfaction, engage these groups with more targeted campaigns, such as affordable options for teenagers and easy-to-use models for older adults.  

---

#### **5. Optimize Payment Options**  
- **Promote Equated Monthly Installments and Cashless Payments:**  
  - With **21.78%** of customers choosing equated monthly installments, consider highlighting this payment option in promotional materials to make higher-priced products more accessible.  
  - Encourage cashless payments through debit cards, credit cards, and Unified Payments Interface by offering cashback or discounts for these payment methods.  

---

#### **6. Strengthen Regional Focus**  
- **Regional Sales Optimization:**  
  - Cities such as **Chennai (11.52%)**, **Hyderabad (11.32%)**, and **Ahmedabad (11.30%)** have the highest customer shares.  
  - Enhance marketing efforts in these regions through localized campaigns, regional promotions, or partnerships with local influencers.  

- **Opportunity in Other Cities:**  
  - Focus on cities with slightly lower sales percentages (e.g., Jaipur at **10.34%**) by offering city-specific promotions or targeted advertisements.  

---

#### **7. Diversify Product Offerings**  
- **Expand Demand in High-End and Premium Segments:**  
  - With **high-end laptops only accounting for 4.56%** of total purchases, boost interest by offering exclusive promotions, financing options, or trade-in programs.  
  - Showcase the value of premium and high-end laptops through in-depth reviews, influencer collaborations, or demo events to attract customers.  

- **Strengthen Mid-Range Appeal:**  
  - With **29.96% share**, mid-range laptops are a key driver of revenue. Partner with manufacturers to introduce features like extended warranties or software bundles that enhance value for mid-range buyers.  

---

#### **8. Gender-Specific Engagement**  
- **Target Female Customers (43% of the Customer Base):**  
  - Create marketing campaigns tailored to appeal to female customers, focusing on design, portability, or multi-tasking capabilities.  
  - Offer gender-neutral packaging or promotional events to expand appeal across demographics.


### **Stakeholder Report**  
#### **Subject:** Insights and Recommendations for Optimizing Sales and Customer Satisfaction in 2025  
---
### **Summary**  
As part of our collaboration, I conducted a detailed analysis of your electronics store’s sales data from January 2024. The primary objective was to derive actionable insights and provide data-driven recommendations to optimize sales performance and improve customer satisfaction for 2025. This report summarizes the findings and offers strategic recommendations based on the analysis.  

---

### **Key Insights**  

#### **1. Customer Demographics**  
- **Young Adults (37.12%)** and **Middle-Aged Adults (36.58%)** form the majority of your customer base, with an **average customer age of 38 years and 7 months**.  
- **Teenagers (4.62%)** and **Older Adults (21.68%)** represent smaller but significant segments.  
- **Gender Distribution:** 57% of customers are male, and 43% are female.  

#### **2. Purchase Trends**  
- **Online Sales Dominate:** 68.1% of customers purchased online, while 31.9% purchased offline.  
- **Payment Methods:**  
  - **Equated Monthly Installments (21.78%)** were the most popular payment method, followed by debit cards (20.96%), credit cards (19.42%), cash (18.92%), and Unified Payments Interface (18.92%).  

#### **3. Customer Satisfaction**  
- **Average Satisfaction Rating:** 3 out of 5, indicating room for improvement in customer experience.  
- **Young Adults:** Higher dissatisfaction levels (7.72% very dissatisfied) compared to satisfaction levels (7.38% very satisfied).  
- **Middle-Aged Adults:** Mixed satisfaction, with 7.68% very satisfied and 6.90% very dissatisfied.  
- **Older Adults and Teenagers:** These groups reported lower satisfaction levels overall, suggesting an opportunity to better engage these demographics.  

#### **4. Product Insights**  
- **Demand by Category:**  
  - **Entry-Level Laptops (35.36%)** were the most popular, followed by mid-range laptops (29.96%).  
  - Premium (14.58%), budget (15.54%), and high-end laptops (4.56%) accounted for smaller shares.  
- **Brand Insights:**  
  - **Lenovo:** The most purchased brand across entry-level, mid-range, and premium categories but associated with higher dissatisfaction, particularly in mid-range and premium segments.  
  - **Samsung:** The leading brand in budget laptops, with higher customer satisfaction.  
  - **Asus:** Dominates high-end laptops, but most customers reported neutral feelings about their purchases.  

#### **5. Regional Distribution**  
- Highest customer representation is in **Chennai (11.52%)**, **Hyderabad (11.32%)**, and **Ahmedabad (11.30%)**, followed closely by other major cities.  

---

### **My Recommendations**  

#### **1. Improve Customer Satisfaction**  
- **Lenovo Products:** Work with Lenovo to identify and address customer concerns in entry-level, mid-range, and premium categories. Offer perks like extended warranties or exclusive support services.  
- **Post-Purchase Support:** Implement a robust post-purchase follow-up system to address potential dissatisfaction early and boost loyalty.  

#### **2. Expand High-Performing Brands**  
- **Samsung in Budget Category:** Leverage Samsung’s strong performance by promoting its value proposition to budget-conscious customers. Offer additional deals and bundles to drive sales.  
- **Asus in High-End Category:** Highlight premium features of Asus high-end laptops through targeted marketing, while offering incentives like trade-ins or financing options to boost satisfaction.  

#### **3. Enhance the Online and Offline Experience**  
- **Online:** Invest in optimizing the online shopping experience, ensuring fast loading times, intuitive navigation, and live customer support.  
- **Offline:** Improve the in-store experience with hands-on demos, knowledgeable sales staff, and exclusive in-store promotions.  

#### **4. Target Specific Demographics**  
- **Young and Middle-Aged Adults:** Focus marketing efforts on these groups with personalized campaigns emphasizing features like performance, productivity, and affordability.  
- **Teenagers and Older Adults:** Introduce targeted offerings, such as user-friendly laptops for older adults and affordable options for teenagers.  

#### **5. Strengthen Payment Flexibility**  
- Promote **Equated Monthly Installments** and offer exclusive deals for cashless payments to further incentivize purchases across all categories.  

#### **6. Regional Strategy**  
- Focus on top-performing cities like **Chennai, Hyderabad, and Ahmedabad** by increasing regional promotions and customer engagement campaigns.  
- Expand efforts in slightly underperforming cities (e.g., **Jaipur**) to balance sales distribution.  

#### **7. Drive Sales in Premium and High-End Categories**  
- Use premium marketing campaigns that emphasize quality, performance, and exclusivity.  
- Educate customers on the benefits of investing in premium and high-end laptops through influencer collaborations and demo events.  

#### **8. Increase Female Customer Engagement**  
- Develop marketing campaigns that resonate with female customers, highlighting design, portability, and multitasking capabilities.  

---

### **Conclusion**  
By implementing these recommendations, your business can enhance customer satisfaction, strengthen brand partnerships, and optimize sales performance for 2025. Addressing dissatisfaction in key categories, leveraging high-performing brands, and tailoring strategies to customer demographics and regions will ensure sustained growth and profitability.  

If you have any questions or would like to discuss specific aspects of the recommendations in detail, I would be happy to assist further.  

Sincerely,  
Elijah  
Data Analyst  


