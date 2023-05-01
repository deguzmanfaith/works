Works

# Project Title: Global GDP Disparities: Analyzing & Visualizing Country-Level Data

I. Introduction 

The objective of this study is to identify the distribution of GDP per capita per country through visualization.

II. Data Collection and Preparation

Our data is sourced from Kaggle, covering the countries, Rank, ID, continent, population, IMF report, U.N. report, and GDP per capita.
The data was retrieved using SQL queries and exported it into CSV files for further analysis. 
The data was also visualized through Microsoft Excel, considering its small-sized workable quantity of rows.

III. Descriptive Analysis

We start by presenting summary statistics for GDP per capita, such as maximum, minimum, mean.

To highlight the countries with the highest and lowest GDP per capita, we presented the data using funnel charts to show the progressive reduction of data in the highest and lowest category.

![HighestGDP_country](https://user-images.githubusercontent.com/132285025/235494048-4a5a8e44-bc41-4820-9fe8-a715b817d4fe.png)

![LowestGDP_country](https://user-images.githubusercontent.com/132285025/235494960-f1c01746-f590-41da-915b-ea3e7195b523.png)

We also used a bar chart to identify the average GDP per capita in each continent. The data tells us that Europe has the highest GDP per capita value, while Africa has the lowest. 

![AVG(GDP:continet)](https://user-images.githubusercontent.com/132285025/235496164-0c13915f-2a2c-4ffb-913d-be0619e909e3.png)

We also identified which country's GDP per capita is performing closest to the mean. 

![Uruguay](https://user-images.githubusercontent.com/132285025/235496638-ed158e0e-176b-435c-b6de-4bdd529a03d7.png)

To explore the relationship between the consistencies of IMF and U.N. reports, we used a scatter plot to visualize discrepancies of the reports by both organizations. The large gap suggests there are some outliers in the IMF variable.

![IMF:un](https://user-images.githubusercontent.com/132285025/235499658-ee4d9a01-8356-4210-afb7-cb49de574b03.png)

We also looked at the gap between the country with the highest GDP and the lowest GDP. As seen in this stacked bar, we can see a huge gap between the two countries. 

![GapViz](https://user-images.githubusercontent.com/132285025/235503518-5f1a7b8d-aec1-42bc-86b5-223418c32a6b.png)

IV. Conclusion

The top five countries with the highest GDP per capita have a wide range of values, with a maximum of 178196.57 and a minimum of 278.43. This suggests that there are significant differences in economic performance among countries.

The country with a GDP per capita, Uruguay, is closest to the mean value indicating that it is a typical performer in terms of economic development. We can take a deep dive for thorough insights into common characteristics or policies and even the culture and livelihood of citizens that contribute to economic growth.

The inconsistency between IMF and UN values for some countries' GDP per capita implies a need for further investigation of data sources and methods. It could also indicate potential errors or limitations in the data that should be taken into account when drawing conclusions.

The large gap between the highest and lowest GDP per capita values indicate a significant inequality in economic development and wealth distribution among countries. This highlights the need for interventions to promote economic growth and reduce disparities.

Overall, the analysis provides a starting point for understanding the economic performance of countries and identifying potential factors that contribute to or hinder economic growth. However, further analysis and interpretation are necessary to draw more conclusive insights and implications for policy and decision-making.

V. References
Srihari. (2023). <i>Country_GDP</i> [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/5336511
