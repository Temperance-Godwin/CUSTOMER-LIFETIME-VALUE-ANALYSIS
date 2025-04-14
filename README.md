## CUSTOMER LIFETIME VALUE ANALYSIS
![Intro_image](https://github.com/Temperance-Godwin/COHORT-ANALYSIS/blob/main/Intro.png)

## INTRODUCTION.
Customer Lifetime Value (CLV) is a key metric that helps businesses understand the total worth of a customer over the course of their relationship with the company. This notebook provides an analysis of customer acquisition data to evaluate CLV, identify high-value customer acquisition channels, and make data-driven marketing decisions.

## OBJECTIVE
The main goals of this analysis are:
1. To analyze customer acquisition cost and revenue distributions.
2. To compare acquisition costs across different channels.
3. To identify the most and least effective acquisition channels in terms of conversion and revenue generation.
4. To derive actionable insights to optimize marketing investments.
5. To calculate the ROI for each channel.

## DATA SOURCE
UCI Machine Learning Repository. View data [here](https://archive.ics.uci.edu/dataset/352/online+retail)

## LIBRARY USED
1. Pandas- Data loading, manipulation, and analysis (e.g., reading CSV, grouping, calculating metrics)
2. Plotly.graph_objs- Creating custom interactive visualizations
3. Plotly.express- Simplifying high-level interface for interactive visualizations like histograms and bar plots
4. Plotly.io- Configuring default themes/styles for Plotly visualizations

## METHODOLOGY
1. Data Loading and Inspection:
- The dataset (customer_acquisition_data.csv) was loaded and explored to understand its structure and types.
2. Descriptive Statistics and Visualization:
- Histograms were used to visualize the distribution of acquisition costs and revenue.
3. Channel-wise comparison was done to identify high- and low-performing channels.
- Grouped summaries helped to find average costs, conversion rates, and total revenue per channel.
4. Channel Effectiveness Analysis:
- Conversion rates and profitability of each channel were analyzed.
- Channels were ranked based on cost efficiency and revenue generation.

View my code [here](https://github.com/Temperance-Godwin/CUSTOMER-LIFETIME-VALUE-ANALYSIS/blob/main/customer%20lifetime%20value%20analysis.ipynb)

## INSIGHTS
- Distribution Acquisition Cost

  ![IDistribution Acquisition Cost](https://github.com/Temperance-Godwin/CUSTOMER-LIFETIME-VALUE-ANALYSIS/blob/main/Distribution%20of%20Acquisition%20Cost.png)

- Revenue Distribution

   ![IDistribution of Revenue](https://github.com/Temperance-Godwin/CUSTOMER-LIFETIME-VALUE-ANALYSIS/blob/main/Distribution%20of%20Revenue.png)

- Conversion Rate and Costs Across Channels
  
   ![Acquisition Cost](https://github.com/Temperance-Godwin/CUSTOMER-LIFETIME-VALUE-ANALYSIS/blob/main/Conversion%20Rate%20and%20Cost%20by%20Channels.png)

- Return of Investments by Channels
  
   ![ROI Across Channels](https://github.com/Temperance-Godwin/CUSTOMER-LIFETIME-VALUE-ANALYSIS/blob/main/ROI%20by%20Channels.png)

- Revenue Percentages Across Channels
  
  ![Revenue Percentages Across Channels](https://github.com/Temperance-Godwin/CUSTOMER-LIFETIME-VALUE-ANALYSIS/blob/main/Total%20Percentage%20Revenue%20by%20Channels.png)

  
1. Most customers are acquired at relatively low costs. A few channels show significantly higher acquisition costs.
2. Revenue distribution is unevenly, with some channels generating very high returns.
3. Referral and Organic Search channels had the lowest acquisition costs and relatively high revenue, making them the most cost-effective. Paid Ads incurred higher costs with moderate revenue, suggesting potential inefficiency. Social Media had moderate cost but lower revenue, indicating room for optimization.
4. Channels like Social media showed high conversion rates, even if overall revenue wasn’t the highest. Some channels with high traffic showed poor conversion, indicating targeting issues.


## RECOMMENDATIONS
1. **Increase investment in Referral and Organic Search channels, as they generate high revenue with low acquisition cost.**

*How to do it:*
- Offer referral incentives (e.g., discounts or cashback). Use tools like ReferralCandy or Referral Rock to automate tracking.

- Improve keyword targeting in blogs, landing pages, and product descriptions. Create high-value content to drive inbound traffic and optimize website performance (load time, mobile friendliness, metadata).

2. Reduce or reallocate budget from underperforming channels like Paid Ads or Social Media.**

*How to do it:*
- Use campaign data (CTR, CPC, ROAS) to identify low-efficiency ads. Pause or A/B test campaigns with high cost and low conversions.

- Shift ad spend toward channels with proven performance and adjust audience targeting based on customer personas or lookalike audiences.

3. **Increase conversion rates on channels with decent reach but low ROI (e.g., Email Marketing or Social Media).**

*How to do it:*

- Test different CTAs, layouts, and headlines using tools like Unbounce or Google Optimize.

- Use segmentation and behavioral triggers to send relevant, timely emails and re-engage users who clicked but didn’t convert using Google Ads or Meta retargeting.

## LIMITATIONS
While this analysis provides useful insights, there are several limitations to consider:

1. **Lack of Temporal Data:** The dataset does not contain timestamps or transaction dates which makes it impossible to conduct time-based analysis such as: Cohort analysis, Customer retention trends, Purchase frequency or recency. A CLV estimate requires data over time to understand how long customers remain active and how often they generate revenue.

2. **Absence of Customer-Level Purchase History:** The dataset appears to be aggregated at the customer or channel level without detailed purchase logs.  We cannot track repeat purchases or order frequency, calculate average order value per customer,and  apply behavioral or probabilistic CLV models. The current analysis relies only on summary revenue figures, reducing the predictive power of insights.

3. **No Cost Breakdown or Profit Margins:** The dataset includes acquisition costs but not product/service costs or profit margins. We can’t determine true profitability per customer or channel, Gross or net CLV. The analysis may overestimate the value of certain channels by focusing solely on revenue.

![Thank you](https://github.com/Temperance-Godwin/Forbes-world-billionaires-2022/assets/156975460/f6563ba6-1ad6-4d34-a3f3-8e7fbdf654df)

## Thank you for following through.
