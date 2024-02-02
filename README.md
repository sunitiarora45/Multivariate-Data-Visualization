# Multivariate-Data-Visualization

## Introduction

This repository explores Multivariate Data isualization using Walmart's dataset, encompassing 45 locations from 2010 to 2012. The analysis delves into the relationships and patterns among variables like Holidays, Temperature, Fuel Price, Consumer Price Index (CPI), and Unemployment.

## Dataset Description

The dataset facilitates a detailed investigation of retail performance, including weekly sales, store details, dates, and additional metrics like temperature, unemployment rate, and CPI. Key variables include Weekly Sales, Store Information, Date, Additional Metrics, and Holiday Events.

**In this project, I focused on Walmart's dataset, exploring:**

1.	Correlation between Consumer Price Index (CPI), Weekly Sales, and Fuel Price.
2.	Quarterly Growth Rate in Q3’2012 for the top 5 stores
3.	Distribution of Weekly Sales by store during Holiday Events for the top 10 stores
4.	Correlation between CPI and Unemployment from 2010 to 2012.
5.	Exploration of Weekly Sales vs. Temperature during 2010, 2011 and 2012.

#### Figure 1: 3D Scatter Plot of CPI, Weekly Sales, and Fuel Price

![image](https://github.com/sunitiarora45/Multivariate-Data-Visualization/assets/131208092/05710193-2569-4422-907e-014f6e5e8a86)

**Observations:**

●	Displays correlations between CPI, Weekly Sales, and Fuel Price during holiday and non-holiday periods.

●	Data points are color-coded, distinguishing between holiday and non-holiday periods.

**Implications:**

●	Patterns indicate modest fluctuations in key economic indices (fuel prices and CPI) during holiday times.

●	Correlation coefficients quantify the strength and direction of these correlations.

#### Figure 2: Trellis Plot of Quarterly Growth Rate in Q3’2012 for the Top 5 Stores

![image](https://github.com/sunitiarora45/Multivariate-Data-Visualization/assets/131208092/c4c20337-38a4-4d0f-ab3d-0a2f23313b08)

**Key Observations:**

**Maximum Growth:**

●	Store 14: Highest positive growth rate (18.05%).

●	Store 2: Growth rate of 10.70%, and Store 20 at 9.57%.
	
**Minimum Growth:**

●	Store 14: Largest negative growth rate (-18.36%).

●	Store 4: Lowest growth rate (-6.93%), followed by Stores 20, 2, and 13.

**Sales Performance:**

●	Store 20: Highest sales volume in Q3 2012, $2.36 million.

●	Store 4: Lowest sales at $2.03 million, with varying degrees for Stores 13, 2, and 14.

#### Figure 3: TreeMap of Weekly Sales by Store and Holiday Event (Top 10 Stores)

![image](https://github.com/sunitiarora45/Multivariate-Data-Visualization/assets/131208092/d2ac687a-dfb2-4070-8c24-37876aeb2c40)

**Key Insights:**
	
**(i) Top 10 Stores Overall:**

Stores 4, 20, 14, 10, 13, 2, 27, 6, 39, and 1 exhibited exceptional sales performance during holiday events.
	
**(ii) Dominant Holiday Event:**

Thanksgiving emerged as the leading event, generating the highest overall revenues.

**(iii) Thanksgiving Sales Impact:**

Thanksgiving achieved the greatest sales total at $52,039,451.64, highlighting its strategic importance.

**(iv) Store-Specific Success:**

Store 4 stood out as the highest sales performer during holidays, offering insights for focused marketing campaigns.

#### Figure 4: Histogram Distribution Plot (CPI vs. Unemployment - 2010-2012)

![image](https://github.com/sunitiarora45/Multivariate-Data-Visualization/assets/131208092/a02131c7-0d8a-4bcb-ba84-c1143cbc088b)

**(i) Unemployment Intervals and CPI:**

Analysis segments unemployment into 0-5, 6-11, and 12-17 categories for a detailed CPI-Unemployment link.

**(ii) CPI Trends across Unemployment Intervals:**

Average CPI fluctuations within each interval reveal potential trends in consumer pricing concerning varying unemployment rates.

**(iii) Average CPI by Unemployment Interval:**

●	0–5: Baseline consumer costs (137.36).
●	6–11: Rising costs, potential link to increased unemployment (175.62).
●	12-17: Average CPI drops (128.38), indicating a different correlation or economic behavior.

#### Figure 5: Interactive Brushing and Linking Plot (Weekly Sales vs. Temperature)

![image](https://github.com/sunitiarora45/Multivariate-Data-Visualization/assets/131208092/4ad0f223-97f6-4026-aaaf-8968c35a929f)

![image](https://github.com/sunitiarora45/Multivariate-Data-Visualization/assets/131208092/e05846ef-2c54-4906-bfda-d512cedc529a)

**Key Observations:**

**(i) Interactive Histogram:**

Displays Weekly Sales distribution for 2010-2012, incorporating rug plot and bar representation.

**(ii) Brushing and Linking:**

Enables dynamic exploration through interactive connections between scatter plot and histogram.

**(iii) Linked Scatter Plot:**

Depicts Temperature-Weekly Sales relationship with color-coded points by year.

**(iv) Temperature and Sales Relationship:**

Concentration in [40, 80] temperature range suggests increased Weekly Sales during moderate temperatures.










