# Introduction
For this week's challenge was a part of operation we use to identify sustainable investment strategy by analyzing solar farm data.

## Business Objective
MoonLight Energy Solutions aims to develop a strategic approach to significantly enhance its operational efficiency and sustainability through targeted solar investments. As an Analytics Engineer at MoonLight Energy Solutions, your task is to perform a quick analysis of an environmental measurement provided by the engineering team and translate your observation as a strategy report. Your analysis should focus on identifying key trends and learn valuable insights that will support your data-driven case - your recommendation based on the statistical analysis and EDA.  In particular, your analysis and recommendation must present a strategy focusing on identifying high-potential regions for solar installation that align with the company's long-term sustainability goals. Your report should provide an insight to help realize the overarching objectives of MoonLight Energy Solutions.

## Problem statement
As mentioned above this week's plan is to use exploratory data analysis (EDA) and statistical techniques to identify high-potential regions for solar installation in different countries like Benin, Sierraleon and Togo.

# Techniques used
#### Performed some data understanding and cleaning
The dataset included around 525600 rows and 19 columns
I checked for missing values, only comments where columns with NaN values, so I dropped comments column).
Removing outliers using Z-scores.

#### Exploratory Data Analysis (EDA) key steps:
Summary Statistics: Calculated mean, median, and standard deviation to understand the data distribution.
Time Series Analysis: Explored trends in solar radiation (GHI, DNI, DHI) and temperature by time of day/month.
Wind Analysis: Created wind roses to identify wind speed and direction trends.
Correlation Analysis: Used heatmaps and pair plots to analyze relationships between variables like solar radiation and wind speed.
Histograms: Visualized distributions of GHI, DNI, DHI, and temperature.

#### Statistical Analysis
Discussed how statistical evidence was used to support findings.
like Z-scores to flag anomalies, bubble charts to analyze multivariate relationships.

#### Impact of Cleaning
Analyzed how cleaning events impacted sensor readings (ModA, ModB).

### Visualizations
Tools used (e.g., Matplotlib, Seaborn).
Insights from line charts, bar charts, and scatter matrices.


# Key Findings
#### Seasonal patterns in solar radiation.
#### Influence of relative humidity and temperature on solar performance.
#### Regions with consistent solar potential.
All this findings will be insightful for Moonlight Energy to make a strategic investment.

# Challenges Faced
Limited time or/and limited information on how to complete the challenge. (good explanation but I felt it was kind of vague.)
I overcame this issue by discussing with a friend. 
### helped me learn EDA techniques and CI/CD integration

# In conclusion
The observation will slightly help Moonlight Energy with further analysis with more granular data and machine learning models for predictive analysis for solar investments in regions like Benin, Sierra Leone, and Togo. MoonLight Energy Solutions can target areas with consistent solar potential, aligning with its long-term sustainability goals.

This week's challenge provided me with actionable information also fostered a deeper understanding of how data analysis can drive sustainable energy solutions. The techniques applied here shows the importance of evidence-based recommendations for achieving operational efficiency and sustainability.