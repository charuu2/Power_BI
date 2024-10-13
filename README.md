# Power_BI

# E-commerce Sales Dashboard

### Dashboard Link : https://app.powerbi.com/links/0xn5bJY5aS?ctid=8d46a076-d093-416d-a57b-8692cde13bf8&pbi_source=linkShare

## Problem Statement

This dashboard helps the e-commerce business gain insights into sales performance and customer satisfaction. It analyzes **sales, quantity, and profit** across categories (Furniture, Office Supplies, Technology), along with **country-wise** and **region-wise** trends. The most profitable countries are the **US and China**, where **108K Office Supplies** products were sold, generating a profit of **$0.52M**. The dashboard also evaluates **order priority** and **shipping modes** to identify areas for improvement in logistics.

With delays noted in Standard Class shipping and varying profits across regions, the company can focus on optimizing delivery efficiency and tailoring sales strategies to enhance profitability and customer satisfaction.


### Steps followed 

Step 1: Load data into Power BI Desktop. The dataset is in a CSV file format containing details like Category, Sales, Quantity, Profit, Country, Region, Order Priority, and Shipping Mode.

Step 2: Open Power Query Editor and, in the View tab under the Data Preview section, enable "Column Distribution," "Column Quality," and "Column Profile" to review the data.

Step 3: Since column profiling is by default done for 1000 rows, select the option to perform "Column Profiling based on the entire dataset."

Step 4: Ensure there are no errors or missing values in key columns. It was noted that no null or error values were found across critical columns like Sales, Quantity, and Profit.

Step 5: Clean the data as required. For columns like Shipping Mode, ensure proper categorization (Same Day, First Class, Second Class, Standard Class) and remove any inconsistencies.

Step 6: In the Report View, under the View tab, apply a theme to enhance the visual aesthetics of the dashboard.

Step 7: Add new visuals to represent sales and profit trends across categories and regions using charts like bar charts and line graphs. Use the ellipses in the Visualizations pane to access additional visual options.

Step 8: Add slicers for key fields such as Category, Order Priority, Country, and Shipping Mode to allow users to filter data interactively.
           
    
 
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.

All these values have been ignored while calculating average rating for each of the parameters mentioned above.

# Snapshot of Dashboard (Power BI Service)

 ![WhatsApp Image 2024-10-13 at 21 45 00](https://github.com/user-attachments/assets/48471e9c-17a8-47eb-a21e-933e107e6ea5)

 
 # Report Snapshot (Power BI DESKTOP)
   ![WhatsApp Image 2024-10-13 at 21 52 57](https://github.com/user-attachments/assets/d40e294b-99fb-45f3-ba04-c95c927b6598)



# Insights
 
 A single page report was created on Power BI Desktop & it was then published to Power BI Service.

Following inferences can be drawn from the dashboard;
### Key Insights from the E-commerce Dashboard:

#### **1. Total Sales, Profit, and Quantity**:  
   - The business achieved a **total profit of $1.47M**, with **178K products** sold and **total sales amounting to $12.64M** across all categories and regions.

#### **2. Most Profitable Categories**:  
   - **Office Supplies** is the leading category, with **108K units sold** and a profit of **$0.52M**, outperforming Furniture and Technology in both sales and profitability.

#### **3. Top Countries for Profit**:  
   - The **US and China** emerged as the most profitable countries, contributing significantly to overall sales and profit.

#### **4. Region-Wise Performance**:  
   - The **Central region** led in sales volume, with **41,762 products** sold, followed by the **South region**. These regions performed the best, highlighting them as strong markets for the business.

#### **5. Order Priority Impact**:  
   - High-priority and critical orders are typically shipped through **Same Day** and **First Class** delivery, ensuring timely fulfillment and higher customer satisfaction.

####  **6. Shipping Mode Efficiency**:  
   - **Standard Class** was the most frequently used shipping mode, accounting for **107,319 products**, though it's linked to delays. In contrast, **Same Day delivery** was used the least, with only **9,230 products**, suggesting that most customers prefer economical shipping options.

#### **7. Sales and Profit Trends**:  
   - **Office Supplies** dominated in most regions, while **Furniture** and **Technology** exhibited mixed performance, suggesting the need for focused marketing and sales strategies in those categories.

#### **8. Average Order Size and Profit Margins**:  
   - Larger order quantities, especially in Office Supplies, contributed to higher profit margins. Encouraging bulk orders in regions with strong demand could enhance profitability further.

These insights underscore the importance of optimizing shipping processes, focusing on high-performing regions like the Central and South, and improving category-specific sales strategies to boost overall growth and profitability.
