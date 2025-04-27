# **Project Summary**
This project involved analyzing real-world sales data from Instacart, a leading online grocery platform, with the goal of identifying trends in customer behavior and purchasing habits. Key focus areas included order timing, product popularity, spending patterns, and demographic-based segmentation (e.g., age, region, income, family status).

***Using data-driven insights, I developed actionable recommendations to:***
- Enhance marketing strategies
* Improve customer targeting
+ Increase engagement and sales through personalized promotions

The analysis ultimately supports Instacart's efforts to deliver more relevant, customer-focused experiences.

# **Objective**                     <img src="https://www.pngmart.com/files/23/Instacart-Logo-PNG.png" width="200" />

Conduct an exploratory data analysis of Instacart’s sales data to uncover customer purchasing patterns and generate insights that support strategic customer segmentation and targeted marketing efforts.

# **Key Business & Analytical Questions Addressed**
1. **What the busiest days of the week and hours of the  day are (i.e., the days and times with the most orders) in order to schedule ads at times when there are fewer orders?**

2. **Are there particular times of the day when people spend the most money?**

3. **What are simpler price range groupings for Instacart's wide variety of products that marketing and sales teams can use to better target their efforts?**

4. **Which product departments have the highest frequency of orders?**

5. **What’s the distribution among users in regard to their brand loyalty (i.e., how often do they return to Instacart)?**

6. **What different classifications does the demographic information suggest?  Age? Income? Certain types of goods? Family status?**

# **Datasets Used**
The analysis was conducted using the following key datasets from Instacart's grocery order history:
1. **Customers:**
   Contains demographic and segmentation data such as user ID, region, age group, income level, and household status.
2. **Orders:**
   Includes order-level information such as order ID, customer ID, order sequence, day of the week, hour of day, and days since prior order.
3. **Orders_Products_Prior:**
   A transactional dataset detailing the products purchased in previous customer orders. It captures order-product relationships, including add-to-cart order and reorder status.
4. **Products:**
   Contains product-level information such as product ID, product name, and associated department ID.
5. **Departments:**
   Provides department-level metadata, mapping department IDs to department names (e.g., produce, dairy, bakery).

# **Tools & Technologies Used**
The analysis was conducted using Python within a Jupyter Notebook environment, leveraging a suite of powerful libraries for data manipulation, statistical analysis, and visualization:
- **Pandas:** for efficient data cleaning, manipulation, and exploration
- **NumPy:** for numerical computations and array operations
- **SciPy:** for advanced mathematical and statistical functions
- **Seaborn:** for high-level, aesthetically pleasing statistical data visualizations
- **Matplotlib:** for creating detailed and customizable plots
- **OS:** for handling file and directory operations during data import and export
- **ChatGPT & Other LLMs:** Assisted with structuring project documentation, refining grammar, and enhancing clarity in written content.

# **Process / Methodology**
The analysis was conducted using a systematic data analysis approach to uncover meaningful insights from Instacart's sales data. The methodology involved the following stages:

- **Data Acquisition & Understanding**
  - Utilized open-source Instacart datasets, including customer demographics, order details, product information, and department classifications.
  - Reviewed dataset structures to understand relationships between various entities.
  
- **Data Cleaning & Preprocessing**
  - Identified and dealt with missing values and handled inconsistencies in order timestamps and customer demographics.
  - Merged relevant datasets to establish meaningful connections between orders, products, and customer segments.
  - Standardized categorical variables and optimized data formats for efficient processing.

- **Exploratory Data Analysis (EDA)**
  - Visualized ordering patterns to determine peak shopping days and times.
  - Examined spending behaviors across different product categories.
  - Investigated customer segmentation based on regional, demographic, and loyalty indicators.
  - Conducted summary statistics and correlation analysis to identify trends in purchasing behaviors.

- **Segmentation & Insights Extraction**
  - Grouped products into strategic price ranges for effective marketing targeting.
  - Identified high-value customers based on frequency and spending habits.
  - Assessed patterns in product reordering behaviors to optimize recommendations.
  - Derived actionable insights to support personalized promotions and targeted advertisements.

- **Data Visualization & Reporting**
  - Developed clear and interpretable visualizations using **Seaborn** and **Matplotlib** for presenting key findings.
  - Compiled insights into a structured report, detailing optimization strategies for Instacart's marketing team.

- **Conclusion & Recommendations**
  - Proposed tailored advertising schedules based on peak shopping hours.
  - Suggested personalized promotions to enhance engagement and retention.
  - Provided recommendations for improving product placement and pricing strategies.

- **Key Insights & Visuals**
  See the folders titled: **"Analysis"** for the analysis and **"Sent to Client"** for the report and visuals also included in the analysis folder

- **Conclusion / Recommendations**
   See the folder titled:  **"Sent to Client"** for the conclusion and recommendations

- # **Disclaimer & Resources**
   ## Disclaimer:
   Instacart is a real company that has made its data publicly available for educational and non-commercial use. However, the customer data used in this project is entirely fictitious and was provided as part of CareerFoundry's Data Analytics program for training purposes.
  ## Resources:
  The dataset was sourced from Instacart’s open data repository. Additionally, ChatGPT was used to assist with structuring project documentation, refining grammar, and enhancing clarity in written content.

