## CUSTOMER LIFETIME VALUE ANALYSIS
![Intro_image](https://github.com/Temperance-Godwin/COHORT-ANALYSIS/blob/main/Intro.png)

## INTRODUCTION.
Customer Lifetime Value (CLV) is a key metric that helps businesses understand the total worth of a customer over the course of their relationship with the company. This notebook provides an analysis of customer acquisition data to evaluate CLV, identify high-value customer acquisition channels, and make data-driven marketing decisions.

## OBJECTIVE
The main goals of this analysis are:
1. To analyze customer acquisition cost and revenue distributions.
2. To compare acquisition costs across different marketing channels.
3. To identify the most and least effective acquisition channels in terms of conversion and revenue generation.
4. To derive actionable insights to optimize marketing investments.

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
  ![IDistribution Acquisition Cost]( https://github.com/Temperance-Godwin/CUSTOMER-LIFETIME-VALUE-ANALYSIS/blob/main/Distribution%20Of%20Acquisition%20Cost.png)

- Revenue Distribution
   ![IDistribution of Revenue](https://github.com/Temperance-Godwin/CUSTOMER-LIFETIME-VALUE-ANALYSIS/blob/main/Distribution%20Of%20Revenue.png)


1. Most customers are acquired at relatively low costs. A few channels show significantly higher acquisition costs.
2. Revenue distribution is unevenly, with some channels generating very high returns.
3. Referral and Organic Search channels had the lowest acquisition costs and relatively high revenue, making them the most cost-effective. Paid Ads incurred higher costs with moderate revenue, suggesting potential inefficiency. Social Media had moderate cost but lower revenue, indicating room for optimization.
4. Channels like Email Marketing showed high conversion rates, even if overall revenue wasn’t the highest. Some channels with high traffic showed poor conversion, indicating targeting issues.


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
1. **Data is Limited to Few Continents**: Retention behavior may differ significantly in other markets due to cultural, economic, or seasonal factors.
2. **Temporal Range is Not Fully Defined**: The dataset likely covers a single year. A longer time horizon would provide a more complete view of long-term retention and customer lifetime value.
3. **Lack of Channel Attribution**: The dataset does not include information about how customers were acquired (e.g., paid ads, organic search, referrals). Without this, we cannot determine which marketing channels produce higher-retaining customers.
4. **Revenue Retention is Not Analyzed**: The focus was on user retention. Revenue retention would provide a more nuanced understanding of customer value and help distinguish between low- and high-spending retained users.
5.**No Behavioral or Demographic Segmentation**: All users are treated equally in the analysis. Further segmentation by age, gender, product type, or user behavior could uncover more granular insights.
6. **Returns and Cancellations Excluded but Not Analyzed**: While returns were excluded for data quality, analyzing their frequency and causes could reveal issues affecting customer satisfaction and long-term retention.
7. **No Real-Time or Automated Monitoring**: This is a static analysis. For production use, this should be built into a real-time dashboard or periodic reporting system to monitor cohort performance continuously.
