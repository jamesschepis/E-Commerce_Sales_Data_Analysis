# **E-Commerce Sales Data Analysis**

Tools Used: 
* Python

Project Type:
* Data Cleaning
* Exploratory Data Analysis
* Data Visualisation

Link to code [here](https://github.com/jamesschepis/E-Commerce_Sales_Data_Analysis/blob/3499d1d7e38322cd73146f348482034edb76d53d/KaggleProject.ipynb)

## **Table of Contents**
1. [Project Background](#project-background)  
2. [⭐ Executive Summary](#executive-summary)  
3. [Insights Deep-Dive](#insights-deep-dive)  
   - [Sales Trends](#sales-trends)  
   - [Product Performance](#product-performance)  
   - [Customer Metrics](#customer-metrics)  
4. [Recommendations](#recommendations)  
5. [Assumptions and Caveats](#assumptions-and-caveats)  

<br>

## **Project Background**
This project focuses on analysing 2022 sales data obtained on Kaggle from an Indian e-commerce platform to uncover actionable insights. By exploring sales trends, product performance, and customer metrics, the analysis aims to provide key metrics and visualisations that inform recommendations to improve performance across sales, product, and marketing teams.

<br>

## **Executive Summary**
This analysis covers ~129,000 records and ₹83 million in total sales across three months in 2022. Sales have declined by ~19% over the last two months, driven by a significant drop in order counts (~22% decrease). While Average Order Value (AOV) is increasing, the decline in order volume is the primary factor contributing to the overall sales downturn.

Key product performance insights include a ~₹4.8 million drop in 'Set' sales, which is impacting total sales the most. Conversely, 'Western Dress' saw a strong ~₹1.5 million sales increase in May. Additionally, B2B customers have a higher AOV (₹698 vs ₹646 for B2C) but currently form a negligible part of total sales.

### Key Recommendations:
1. **Investigate the 22% drop in order counts** to address operational or engagement challenges.
2. **Diversify the product portfolio** to reduce reliance on 'Set' and 'Kurta,' which account for 77% of sales and orders.
3. **Examine the ₹4.8 million decline in 'Set' sales** to identify whether it's product-specific or part of a broader trend.
4. **Capitalize on 'Western Dress' performance** by expanding its offering or increasing marketing efforts.
5. **Target B2B customers** with exclusive promotions to leverage their higher AOV and increase sales.

<br>

## **Insights Deep-Dive**

### **Sales Trends**
- In April observed ₹30 million in sales (~$565K AUD) across ~49,000 orders.
- Sales have declined for 2 consective months by ~19% total.
- While Average Order Value (AOV) is trending upwards, there is a significant decline in order counts, from ~49,000 in April down to ~38,000 in May, which is driving the overall decline in sales.
- Sales (both gross and net) are showing a consistent downward trend.
- Maharashtra, the largest purchasing state, experienced a 21% (~₹1 million) decline in sales over the previous 2 months, while sales across top 10 states are all generally trending downward.

![image](https://github.com/user-attachments/assets/e94d0a88-aaa3-45ca-ac7f-881fc03653e1)
![image](https://github.com/user-attachments/assets/008f295e-5c52-4ab5-969e-a73785f3d843)
![image](https://github.com/user-attachments/assets/d2f3efee-d241-4a36-8031-f7cd02a4d122)


### **Product Performance**
- Two products, 'Set' and 'Kurta,' account for 77% of total sales and orders. Additionally, four out of the nine products offered contribute 98% of total sales and 97% of orders, indicating a highly concentrated product portfolio.
- 'Set', the top-selling product, has seen a significant decline in both sales of ~₹4.8 million and order volumes of ~6,200 since April, which is the primary contributor to the overall sales downturn.
- 'Kurta', the second-best-selling product, experienced a significant drop in May down ~₹1.5 million but showed signs of stabilization in June.
- 'Western Dress', ranked third in sales, saw a notable sales increase of ~₹1.5 million in May. Although it dipped slightly in June, its performance remains ~$1M higher (~32% growth) than its April figures.
- 'Saree' and 'Bottom' products have experienced spikes in returns. However, as these products are among the bottom three performers, this issue is not an immediate priority.
- Other products have exhibited a steady return rate in the range of 0.13 to 0.17.

![image](https://github.com/user-attachments/assets/eeef8bb7-bd1a-4c90-ba46-cc46222bf463)
![image](https://github.com/user-attachments/assets/2c47425a-b29f-46d2-9341-f2ae665620f1)
![image](https://github.com/user-attachments/assets/28539219-ef77-46d3-8279-8cdbb3805a38)

### **Customer Metrics**
- B2B customers have a higher Average Order Value (₹698) compared to B2C customers (₹646), though B2B sales form a negligible portion of total sales (<1%). 

![image](https://github.com/user-attachments/assets/ec5b802d-6fc7-4157-9e02-0c746b2e5198)

<br>

## **Recommendations**
- **Investigate the drop in order counts, which have declined by ~22% from April to May, directly driving the ~₹6 million (~19%) total sales decrease.** Understanding the root cause of this decline will help address operational or engagement-related challenges. Consider analysing economic conditions, marketing strategies, or customer preferences to identify possible causes.
- **Diversify the Product Portfolio**: With 77% of sales and orders concentrated in just two products, **introducing new product lines, particularly accessories, could provide upsell opportunities and reduce dependency on the top-performing items.** Accessories complement existing offerings and could drive incremental sales.
- **Optimize the Existing Product Mix**: Focus marketing and promotional efforts on the underperforming products to **identify whether they have untapped potential or should be phased out in favor of higher-demand items.** This will ensure that resources are allocated effectively to maximize returns.
- **Examine the ₹4.8 million (16%) sales decline and ~6,200 drop in order volumes for 'Set,' the top-selling product.** Determining whether the issue is product-specific or indicative of broader factors is critical for reversing this trend.
- **Analyze the ₹1.5 million sales dip for 'Kurta' in May and its stabilization in June.** This will help determine if the decline was seasonal or influenced by other factors, enabling effective planning for consistent sales.
- **Capitalise on the ~32% sales growth of 'Western Dress' in May by expanding its product line or enhancing marketing campaigns.** This product remains a strong performer and offers an opportunity for further revenue growth if promoted effectively.
- **Expand the B2B customer segment to leverage their higher Average Order Value (₹698 compared to ₹646 for B2C).** Offering exclusive discounts, targeted promotions, or loyalty programs could drive additional sales and diversify revenue streams. 

<br>

## **Assumptions and Caveats**
- **Limited Data Availability**: The analysis is based on data spanning only three months (April, May, and June). This limited timeframe may not capture seasonal trends, long-term patterns, or anomalies that could provide deeper insights.
- **External Factors**: No adjustments were made for external influences such as seasonality, promotions, or economic factors.  
- **Net Revenue Calculations**: Refunds, returns, and cancellations were excluded from net revenue, but handling or restocking fees were not factored in.
- **Restricted Business View**: The analysis was conducted with a partial view of the business. For instance:
  - **Customer Metrics**: The lack of access to customer IDs prevents any detailed analysis of customer behaviour, such as repeat purchase rates, customer segmentation, or churn rates.
  - **Marketing Campaign Insights**: There is minimal to no visibility into marketing campaigns or initiatives, which limits the ability to assess the impact of promotional efforts on sales performance.

These limitations may impact the comprehensiveness of the findings and the precision of the recommendations provided. Further data and access to broader business metrics would enable a more robust and actionable analysis.
 



