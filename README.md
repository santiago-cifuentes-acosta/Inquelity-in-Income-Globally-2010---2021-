**Inquelity-in-Income-Globally-2010---2021-**

How has income inequality changed across development levels and regions from 2010 to 2021? \n
In this project I've analysed how inequality trends in income have varied across the globe, segmenting by hemisphere, continent and Human Development group, as well as written analysis in the README of this repository
Data: https://www.kaggle.com/datasets/iamsouravbanerjee/inequality-in-income-across-the-globe Observations: ~160 countries Years: 2010 - 2021
This project explores how income inequality varies across countries, continents, and Human Development Groups (HDG) between 2010 and 2021.
As a sociologist interested in inequality and development, I use this dataset to practice data analysis, Power BI modelling, and research-style interpretation.
Questions I Wanted to Answer
    • How has global income inequality changed between 2010 and 2021?
    • How do inequality levels differ between Human Development Groups (HDG)?
    • Are there noticeable differences by continent and hemisphere?
    • Is higher HDI Rank associated with lower inequality?
In this report I analyse cross-national patterns of income inequality using UNDP-style indicators for ~160 countries. I built several calculated tables using SUMMARIZE, AVERAGE, COUNTROWS, CALCULATE and ROUND to:
    • Compute global and regional averages over time
    • Aggregate inequality by Human Development Group (HDG) and hemisphere
    • Summarise the number of countries in each HDG by hemisphere I then designed a Power BI page that highlights:
    • Global mean inequality in 2010 and 2021
    • Differences between Northern and Southern hemispheres
    • Trends by continent (2010 vs 2015 vs 2021)
    • The association between HDI Rank (2021) and average inequality (scatter plot)
Tools & Techniques Tools: Power BI, DAX
    • DAX functions used: SUMMARIZE, CALCULATE, AVERAGE, COUNTROWS, ROUND, (and any others) Concepts:
    • Creating calculated tables for aggregated views
    • Building measures for cards and visuals
    • Understanding filter context and row context
    • Basic data modelling in Power BI
Analysis Steps I began the project by cleaning the data using Power Query, removing duplicated rows and fully blank rows. I chose not to eliminate rows that were not fully blank because where a country was missing HDG, it had valuable information regarding its Inequality in Income for all or some of the years between 2010 and 2021, making the row still useful for analysis.
In preparation for visualisation, I created measures and calculated tables, as well as adding a calculated column to the original table which I used for the scatter graph. The latter is called Mean Across All Years and it is the addition of the Inequality indexes from 2010 to 2021 divided by 11. I used this to create the bar chart entitled Avg. Inequality in Income by HDG, which shows a clear negative correlation between Human Development and Inequality.
I used the Inequality in 2021 against the Human Development Index Rank (2021) to create the scatter plot, revealing a weak positive correlation between HDI Rank and Income Inequality. The lower the Rank, the lower the Inequality, but this correlation becomes less obvoius in higher Ranks. This indicates that things other than HDI influence inequality, and that things independent of HDI could be battling (or otherwise preventing) inequality in countries with high Rank and low inequality. This quartile of the graph is dominated by Oceaian, Asian and African countries.
The other two bar charts show the evolution of inequality segregating countries by HDG and contient. These graphs reveal that, while there is a global tendency to reduce inequality across HDGs, when controlling by continent instead this tendency changes for Oceania and Asia, where there was an improvement in 2015 but then a drawback in 2021, and in Europe, where there was a drawback in 2015 and then a new improvement in 2021. Africa and America maintain the decreasing pattern, at least across the three years shown in that graph (2010, 2015, 2021).
Drawbacks of the dataset I found inconvenient that America was only one continent, given that North and South America have vastly different levels of development. Segregation by hemisphere did not resolve this issue, as many nations in the Medium HDG in Central and South America are still in the Northern Hemisphere, such as Venezuela, Belize and Honduras.


