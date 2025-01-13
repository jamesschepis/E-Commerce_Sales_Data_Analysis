# **E-Commerce Sales Data Analysis**

Tools Used: 
* Python

Project Type:
* Data Cleaning
* Exploratory Data Analysis
* Data Visualisation

Link to code:

## **Table of Contents**
1. [Project Background](#project-background)  
2. [Executive Summary](#executive-summary)  
3. [Insights Deep-Dive](#insights-deep-dive)  
   - [Sales Trends](#sales-trends)  
   - [Product Performance](#product-performance)  
   - [Customer Metrics](#customer-metrics)  
4. [Recommendations](#recommendations)  
5. [Assumptions and Caveats](#assumptions-and-caveats)  

<br>

## **Project Background**
This project focuses on analyzing sales data obtained on Kaggle from an e-commerce platform to uncover actionable insights. By exploring customer behavior, product performance, and revenue trends, the analysis aims to provide key metrics and visualizations that inform strategic business decisions.

<br>

## **Executive Summary**
The analysis offers a comprehensive view of e-commerce performance, revealing trends in gross sales, product returns, customer spending, and regional contributions.  

Key highlights include:  
- Gross sales showed a decline of ~$6 million from April to June, with specific cities contributing significantly to this drop.  
- B2B customers tend to have a higher average order value (AOV) compared to B2C customers.  
- Certain products experience disproportionately high return rates, impacting net revenue.  

These findings highlight opportunities for optimizing product offerings, targeting high-value customer segments, and addressing areas with high return or refund rates.

<br>

## **Insights Deep-Dive**

### **Sales Trends**
- In April observed ₹30 million in sales (~$565K AUD) across ~49,000 orders.
- Sales have declined for 2 consective months by ~19% total.
- While Average Order Value (AOV) is trending upwards, there is a significant decline in order counts, from ~49,000 in April down to ~38,000 in May, which is driving the overall decline in sales.
- Sales (both gross and net) are showing a consistent downward trend.
- Maharashtra, the largest purchasing state, experienced a 21% (~₹1 million) decline in sales over the previous 2 months, while sales across top 10 states are all generally trending downward.

### **Product Performance**
- 'Set', the top-selling product, has seen a significant decline in both sales of ~₹4.8 million and order volumes of ~6,200 since April, which is the primary contributor to the overall sales downturn.
- 'Kurta', the second-best-selling product, experienced a significant drop in May down ~₹1.5 million but showed signs of stabilization in June.
- 'Western Dress', ranked third in sales, saw a notable sales increase of ~₹1.5 million in May. Although it dipped slightly in June, its performance remains ~$1M higher (~32% growth) than its April figures.
- 'Saree' and 'Bottom' products have experienced spikes in returns. However, as these products are among the bottom three performers, this issue is not an immediate priority.
- Other products have exhibited a steady return rate in the range of 0.13 to 0.17.

### **Customer Metrics**
- B2B customers have a higher Average Order Value (₹698) compared to B2C customers (₹646), though B2B sales form a negligible portion of total sales. 

<br>

## **Recommendations**
1. Investigate the drop in order counts, as this is directly contributing to the decline in sales, despite the increase in AOV. Understanding the underlying causes could reveal operational or engagement-related challenges that need to be addressed.
2. Examine the decline in 'Set' sales, as this product is the primary driver of the overall sales decrease. A deeper investigation into the cause of this decline could help identify whether it's a product-specific issue or if broader factors are at play.
3. Look into the dip in 'Kurta' sales during May. Understanding whether this dip was seasonal or driven by other factors will be crucial in stabilizing sales moving forward.
4. Capitalize on the positive momentum of 'Western Dress' by considering an expansion of its offering or enhancing its marketing efforts. Given its strong performance in May, this product presents an opportunity for growth, especially if further promoted.
5. Investigate business wide and broader market factors contributing to the downward trend in sales. Consider analyzing economic conditions, marketing strategies, or customer preferences to identify possible causes.
6. Explore strategies such as offering exclusive discounts or loyalty programs to target and expand the B2B customer segment to capitalize on their higher AOV and drive overall sales growth.  

<br>

## **Assumptions and Caveats**
- **Data Quality**: The analysis assumes that the data is accurate and complete. Inconsistencies in data entry (e.g., city names) were corrected during preprocessing.  
- **Timeframe Limitations**: The dataset spans only three months, which may not represent long-term trends.  
- **External Factors**: No adjustments were made for external influences such as seasonality, promotions, or economic factors.  
- **Net Revenue Calculations**: Refunds, returns, and cancellations were excluded from net revenue, but handling or restocking fees were not factored in.
- Limited Data Availability: The analysis is based on data spanning only three months (April, May, and June). This limited timeframe may not capture seasonal trends, long-term patterns, or anomalies that could provide deeper insights.
- Restricted Business View: The analysis was conducted with a partial view of the business. For instance:
  - Customer Metrics: The lack of access to customer IDs prevents any detailed analysis of customer behaviour, such as repeat purchase rates, customer segmentation, or churn rates.
  - Marketing Campaign Insights: There is minimal to no visibility into marketing campaigns or initiatives, which limits the ability to assess the impact of promotional efforts on sales performance.

These limitations may impact the comprehensiveness of the findings and the precision of the recommendations provided. Further data and access to broader business metrics would enable a more robust and actionable analysis.
 



