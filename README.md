# Optimizing-Marketing-Campaign-Performance

## About the Project

This project explores a hypothetical marketing campaign for the launch of *"Classic Men's Jeans,"* aimed at capturing the attention of young men aged 18-24. The company, targeting the mid-range market segment, allocates **$5,000** for a campaign spread across multiple digital channels. The goal is to identify the most effective strategies by focusing on:

- Maximizing **conversion rates**
- Optimizing **ROI**
- Expanding the **customer base**

Using data analytics, this project evaluates different campaign and channel combinations, aiming to provide actionable insights to guide budget allocation and maximize overall campaign performance.

# Table of Contents

1. [About the Data](#about-the-data)
2. [Business Questions Addressed](#business-questions-addressed)
3. [Key Findings & Insights](#key-findings--insights)
   - [1) Identifying Best-Performing Channels](#1-identifying-best-performing-channels)
   - [2) Optimizing Budget Allocation Across High-Performing Campaigns](#2-optimizing-budget-allocation-across-high-performing-campaigns)
   - [3) Identifying the Optimal Customer Segments for Each Campaign](#3-identifying-the-optimal-customer-segments-for-each-campaign)
   - [4) Determining Optimal Campaign Duration for Maximum Conversion Rates](#4-determining-optimal-campaign-duration-for-maximum-conversion-rates)
   - [5) Identifying Optimal Months for Each Selected Campaign](#5-identifying-optimal-months-for-each-selected-campaign)
   - [6) Analyzing the Impact on Net Profit Estimates](#6-analyzing-the-impact-on-net-profit-estimates)
4. [Recommendations](#recommendations)
5. [Conclusion](#conclusion)

## About the Data

The dataset used in this project comprises various marketing campaigns. It includes essential features such as **campaign type**, **target audience**, **conversion rates**, **acquisition costs**, and more. 

For more details, access the dataset on [Kaggle](https://www.kaggle.com/datasets/manishabhatt22/marketing-campaign-performance-dataset).

On top of this, I cleaned the dataset and added features like **total_customers_converted**, **total_amount_spent**, **net_profit**, **campaign_month**, and more. You can explore the detailed data preparation process in this Jupyter notebook [here](https://github.com/AryanJhaveri/Optimizing-Marketing-Campaign-Performance/blob/main/Data_Cleaning%2BFeature_Engineering.ipynb).

## Business Questions Addressed

This project explores the following key business questions:

1. How can budget allocation across high-performing campaigns be optimized to maximize ROI?
2. For each campaign, which customer segment should be targeted to maximize engagement and conversion?
3. What is the optimal campaign duration for each selected marketing channels to maximize conversion rates?
4. What is the ideal month to run each selected campaign, based on historical conversion rates and the optimal campaign duration?
5. How do net profit estimates improve when factoring in customer segments, durations, and timing?

## Key Findings & Insights

### 1) Identifying Best-Performing Channels

Through exploratory data analysis (EDA) on **Impressions**, **CTR**, **Conversion Rate**, **Acquisition Cost**, and **ROI** across all existing channel and campaign type combinations (30 combinations), four top-performing campaigns were selected:

1. **Facebook Email Campaigns**
2. **Instagram Email Campaigns**
3. **Facebook Search Campaigns**
4. **Google Ads Search Campaigns**

These combinations will be prioritized in future marketing strategies to maximize engagement and ROI.

### 2) Optimizing Budget Allocation Across High-Performing Campaigns

To maximize ROI across the top-performing campaigns, this project explores a **data-driven budget allocation** approach. We analyzed historical performance metrics, including **CTR**, **conversion rates**, and **ROI** for each channel and campaign combination. Using these insights, we distributed the marketing budget proportionally to the campaigns with the highest expected return.

The goal was to ensure that each campaign's budget was allocated based on its past performance, thus optimizing resources for the most effective channels.

![image](https://github.com/user-attachments/assets/80573b54-db82-40ff-8dff-14cef5416a51)

The pie chart below illustrates the final budget distribution across the selected high-performing campaigns.

### 3) Identifying the Optimal Customer Segments for Each Campaign

To ensure maximum engagement and conversion for each marketing campaign, this project examines historical data to identify the **most responsive customer segments**. We focused on campaign performance metrics, analyzing which segments achieved the highest **conversion rates** across each marketing channel and campaign type.

By targeting specific customer segments, we aim to enhance the efficiency of each campaign by concentrating on those most likely to engage and convert.

![image](https://github.com/user-attachments/assets/4afd57ba-b44f-4717-a1dd-a7fccf8e068b)

#### Key Insights:
- For the **Facebook Email** campaign, the segments **Tech Enthusiasts** and **Fashionistas** consistently showed the highest conversion rates.
  
- The **Facebook Search** campaign performed best when targeting **Tech Enthusiasts** and **Fashionistas**.

- In the **Google Ads Search** campaign, focusing on **Health & Wellness** and **Fashionistas** yielded the highest conversions.

- **Instagram Email** campaigns were most successful when targeting **Tech Enthusiasts** and **Fashionistas**, making these segments the ideal targets for maximizing engagement.

### 4) Determining Optimal Campaign Duration for Maximum Conversion Rates

By analyzing historical data, we aimed to identify the duration that leads to the highest conversion performance for each campaign type. Understanding the optimal duration allows for effective scheduling and maximization of engagement over the campaign lifecycle.

![image](https://github.com/user-attachments/assets/c4c79156-40f4-4649-961e-000ef56c0899)

#### Key Insights:
- **Facebook Email Campaigns**: The ideal duration is **45 days**, achieving the highest conversion rate.

- **Facebook Search Campaigns**: The best duration is **15 days**, yielding strong engagement.

- **Google Ads Search Campaigns**: An optimal duration of **30 days** results in a conversion rate of **0.14**.

- **Instagram Email Campaigns**: A duration of **15 days** offers a solid conversion rate of **0.147**.

### 5) Identifying Optimal Months for Each Selected Campaign

Understanding the best times to run campaigns helps in scheduling and ensuring maximum engagement from the target audience. By analyzing historical data, we aimed to determine the optimal months for executing each selected campaign based on their ideal durations.

![image](https://github.com/user-attachments/assets/e5c8ba5f-904c-472c-bea2-0abf35bd931e)

#### Key Insights:
- **Facebook Email**: 
  - **Ideal Duration**: 45 days
  - **Selected Days**: 30 days of May and 15 days of June

- **Facebook Search**: 
  - **Ideal Duration**: 15 days
  - **Selected Days**: 15 days in June

- **Google Ads Search**: 
  - **Ideal Duration**: 30 days
  - **Selected Days**: 30 days of September

- **Instagram Email**: 
  - **Ideal Duration**: 15 days
  - **Selected Days**: 15 days in May

### 6) Analyzing the Impact on Net Profit Estimates

This project explored the relationship between customer segments, campaign durations, and timing on net profit estimates. By considering these factors, we aim to identify how strategic adjustments can enhance profitability for the "Classic Men's Jeans" campaign.

| Channel_Campaign      | Estimated_Net_Profit | Estimated_Net_Profit_Optimal |
|-----------------------|-----------------------|-------------------------------|
| Facebook - Email      | $10,091               | $10,753                       |
| Facebook - Search     | $9,821                | $10,080                       |
| Google Ads - Search   | $9,234                | $9,622                        |
| Instagram - Email     | $9,919                | $10,600                       |
| **Total**             | **$39,065**           | **$41,055**                   |


The analysis reveals how varying customer segments and timing impact net profit estimates for each campaign type. Optimal combinations of customer segments, durations, and timing lead to significant improvements in projected net profits, increasing from $39,065 to $41,055, a rise of approximately 5.09%.


For a deeper dive into the analysis and results, check out the Jupyter notebook [here](https://github.com/AryanJhaveri/Optimizing-Marketing-Campaign-Performance/blob/main/Optimizing_Marketing_Campaign_Performance.ipynb).

## Recommendations

1. **Prioritize High-Performing Channels**: Focus on **Instagram Email** and **Facebook Search** campaigns for budget allocation to enhance engagement and conversion rates.

2. **Target Specific Customer Segments**: Tailor campaigns for **Tech Enthusiasts** and **Fashionistas** to optimize conversion potential across multiple channels.

3. **Optimize Campaign Durations**: Implement the identified optimal durations for each campaign to maximize conversion rates and overall effectiveness.

4. **Leverage Seasonal Trends**: Schedule campaigns during peak months identified through historical data analysis to capitalize on increased consumer engagement.

5. **Continuously Monitor Performance**: Regularly analyze campaign performance and adjust strategies based on emerging trends and consumer behavior.

## Conclusion

This project explores the launch of the "Classic Men's Jeans" campaign aimed at men aged 18-24. By analyzing marketing channels, customer segments, and optimal campaign durations, actionable insights were derived to inform budget allocation and enhance profitability. The findings underscore the importance of data-driven strategies in maximizing engagement and conversion rates.

