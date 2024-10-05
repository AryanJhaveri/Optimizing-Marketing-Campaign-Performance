# Optimizing Marketing Campaign Performance

## Project Overview

This project examines a hypothetical marketing campaign for the launch of **Classic Men's Jeans**, targeting young men aged 18-24. The campaign, aimed at the mid-range market, has a budget of **$5,000** spread across multiple digital channels. The key objectives are:

- Maximizing **conversion rates**
- Optimizing **ROI**
- Expanding the **customer base**

Using data analytics, the project evaluates various campaign and channel combinations, offering actionable insights to optimize budget allocation and improve overall campaign performance.

## Table of Contents

1. [About the Data](#about-the-data)
2. [Business Questions Addressed](#business-questions-addressed)
3. [Key Findings & Insights](#key-findings--insights)
   - [1) Best-Performing Channels](#1-best-performing-channels)
   - [2) Budget Allocation Optimization](#2-budget-allocation-optimization)
   - [3) Optimal Customer Segments](#3-optimal-customer-segments)
   - [4) Optimal Campaign Duration](#4-optimal-campaign-duration)
   - [5) Best Months for Campaigns](#5-best-months-for-campaigns)
   - [6) Impact on Net Profit Estimates](#6-impact-on-net-profit-estimates)
4. [Recommendations](#recommendations)
5. [Conclusion](#conclusion)

## About the Data

The dataset includes key features such as **campaign type**, **target audience**, **conversion rates**, **acquisition costs**, and more. It was sourced from [Kaggle](https://www.kaggle.com/datasets/manishabhatt22/marketing-campaign-performance-dataset).

Data cleaning and feature engineering added variables like **total_customers_converted**, **total_amount_spent**, and **net_profit**. The data preparation details can be explored in this [Jupyter notebook](https://github.com/AryanJhaveri/Optimizing-Marketing-Campaign-Performance/blob/main/Data_Cleaning%2BFeature_Engineering.ipynb).

## Business Questions Addressed

1. How can budget allocation across high-performing campaigns be optimized to maximize ROI?
2. Which customer segment should be targeted for each campaign to increase engagement and conversions?
3. What is the optimal duration for each campaign to maximize conversion rates?
4. When is the best time to run each campaign for optimal results?
5. How do net profit estimates change when adjusting for customer segments, durations, and timing?

## Key Findings & Insights

### 1) Best-Performing Channels

Exploratory data analysis on metrics like **Impressions**, **CTR**, **Conversion Rate**, **Acquisition Cost**, and **ROI** revealed four top-performing campaign-channel combinations:

- **Facebook Email Campaigns**
- **Instagram Email Campaigns**
- **Facebook Search Campaigns**
- **Google Ads Search Campaigns**

These channels should be prioritized for future marketing strategies to enhance engagement and ROI.

### 2) Budget Allocation Optimization

A data-driven approach was used to distribute the campaign budget based on **CTR**, **conversion rates**, and **ROI**. This approach ensures that the budget is allocated to channels with the highest expected return, thus maximizing resource efficiency.

![Budget Allocation](https://github.com/user-attachments/assets/80573b54-db82-40ff-8dff-14cef5416a51)

### 3) Optimal Customer Segments

Targeting the right customer segments is crucial for maximizing engagement and conversions. Analysis of historical data identified the most responsive segments for each campaign:

- **Facebook Email Campaigns**: Target **Tech Enthusiasts** and **Fashionistas**
- **Facebook Search Campaigns**: Target **Tech Enthusiasts** and **Fashionistas**
- **Google Ads Search Campaigns**: Target **Health & Wellness** and **Fashionistas**
- **Instagram Email Campaigns**: Target **Tech Enthusiasts** and **Fashionistas**

![Customer Segments](https://github.com/user-attachments/assets/4afd57ba-b44f-4717-a1dd-a7fccf8e068b)

### 4) Optimal Campaign Duration

Analyzing historical data helped determine the ideal campaign durations:

| Campaign Channel            | Optimal Duration | Conversion Rate |
|-----------------------------|------------------|-----------------|
| Facebook Email Campaigns     | 45 days          | 0.15            |
| Facebook Search Campaigns    | 15 days          | 0.15            |
| Google Ads Search Campaigns  | 30 days          | 0.14            |
| Instagram Email Campaigns    | 15 days          | 0.147           |

![Campaign Duration](https://github.com/user-attachments/assets/c4c79156-40f4-4649-961e-000ef56c0899)

### 5) Best Months for Campaigns

Analyzing seasonal trends helped identify the best months for running each campaign:

- **Facebook Email**: 45 days across May and June
- **Facebook Search**: 15 days in June
- **Google Ads Search**: 30 days in September
- **Instagram Email**: 15 days in May

![Best Months](https://github.com/user-attachments/assets/e5c8ba5f-904c-472c-bea2-0abf35bd931e)

### 6) Impact on Net Profit Estimates

A combination of customer segments, optimal durations, and timing leads to a **5.09%** increase in net profit, improving from **$39,065** to **$41,055**.

| Channel-Campaign        | Initial Net Profit | Optimized Net Profit |
|-------------------------|--------------------|-----------------------|
| Facebook - Email         | $10,091            | $10,753               |
| Facebook - Search        | $9,821             | $10,080               |
| Google Ads - Search      | $9,234             | $9,622                |
| Instagram - Email        | $9,919             | $10,600               |
| **Total**                | **$39,065**        | **$41,055**           |

For a detailed analysis, refer to the [Jupyter notebook](https://github.com/AryanJhaveri/Optimizing-Marketing-Campaign-Performance/blob/main/Optimizing_Marketing_Campaign_Performance.ipynb).

## Recommendations

1. **Focus on High-Performing Channels**: Prioritize **Instagram Email** and **Facebook Search** campaigns for better engagement and ROI.
2. **Target Specific Segments**: Focus on **Tech Enthusiasts** and **Fashionistas** for higher conversions.
3. **Optimize Campaign Duration**: Use the identified optimal durations to boost campaign effectiveness.
4. **Leverage Seasonal Trends**: Run campaigns during peak months to maximize engagement.
5. **Monitor Performance Regularly**: Adjust strategies based on ongoing data analysis and trends.

## Conclusion

The "Classic Men's Jeans" campaign targeted at men aged 18-24 can achieve greater success through data-driven marketing strategies. By optimizing marketing channels, customer segments, campaign durations, and timing, the project offers actionable insights to improve engagement, conversion rates, and profitability.
