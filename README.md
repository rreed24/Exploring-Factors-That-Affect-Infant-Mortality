# Infant Mortality Rate (IMR) in Baltimore
## Background 
Although the US's IMR is decreasing over time, its 5.8 infant deaths in every 1,000 births is still higher compared to other developed countries that average around 3.4 (Kamal et. al, 2019).
The IMR is particularly higher in the observed community statistical areas in Baltimore compared to other cities as in 2015, it averaged at 10.4.  Through SLR, MLR and Cluster Analysis, we analyzed data of to two out of the three leading causes of IMR - premature birth and low birth weight (Baltimore City Health Department). 
Observing this data, we asked: What are the actions that can be taken to reduce/eliminate IMR in different neighborhoods in Baltimore? What are the patterns that can be explored to identify the factors that contribute to this rate?
## Why is this a problem to address?
IMR is an important indicator of a community’s physical health; a higher IMR suggests that the city is lacking in meeting human health needs in sanitation, nutrition, education, medical care, etc. Being that in 2009, Baltimore City had the 4th highest IMR in the nation, it’s necessary to address the actions that need to be taken to reduce this number by exploring the factors that contribute. In order to figure out how health institutions can implement better practices to reduce infant mortality rate in different neighborhoods in Baltimore, we started by asking the following questions:
1. What are the factors correlated to infant mortality rate in different neighborhoods in Baltimore? How significant are the correlations?
2. Are the connections between the factors stable over time?
3. Can we generate geographical patterns from our data? If so, what does it tell us?
## Multiple Linear Regression with Excel
We ran a multi-linear regression analysis on data from 2010 to 2015 and found that the Rsq values stayed almost the same every year. Thus, we concluded that there is a relatively stable relationship between  IMR and other factors.
(insert graph)
While there is a significant correlation between life expectancy and infant mortality rate (p-value equals 0.04 in 2015), percent of births delivered at term is at the margin of statistical significance in terms of its impact on infant mortality rate with p-value equals 0.06 in 2015.
(Insert regression data)
## Cluster Analysis
![91028965_519621872033365_1289219272383397888_n](https://user-images.githubusercontent.com/60996310/77719215-22b3d600-6fbb-11ea-99d3-3ad80dba67b2.png)
<img width="558" alt="Cluster" src="https://user-images.githubusercontent.com/60996310/77718568-9fde4b80-6fb9-11ea-8c5b-3c6f5b3ab8cd.png">

*Group 1 (blue): low teen birth rate, high % of birth at term, high satisfactory birth weight, high prenatal care, low healthy food index, high life expectancy, relatively low infant mortality
Group 2 (orange): average teen birth rate, average % of birth at term, average satisfactory birth weight, average prenatal care, relatively low healthy food index, average life expectancy, relatively high infant mortality
Group 3 (yellow): high teen birth rate, high % of birth at term, average satisfactory birth weight, average prenatal care, high healthy food index, relatively high life expectancy, low infant mortality
Group 4 (green): relatively high teen birth rate, low % of birth at term, low satisfactory birth weight, low prenatal care, relatively low healthy food index, low life expectancy, higher infant mortality*

Baltimore’s IMR mirrors the troubling statistic that neonatal mortalities (infant mortality within the first 28 days) is highest among infants with Black mothers (Kamal et. al, 2019). Although there is a limited number of CSAs within this dataset, the “Black Butterfly” and "White L" can be seen in our cluster analysis.
## Data Interpretation
In our **trendline** data, we saw that IMR gradually decreased (most rapidly from 2013-2015) in the 5 year period as the average percentage of mothers who received prenatal care increased and teen birth rate decreased. We see that increasing availability of healthcare for women expecting and decreasing the number of young mothers may contribute to a lower number of infant deaths.

Our results in the **SLR and MLR** didn’t exactly reflect the literature of what we know about the highest contributing factors in IMR.
Data from the **SLR** indicates that there’s an 13% correlation between the % of babies born with a satisfactory birth weight and IMR and 26% correlation between % of births delivered at term and IMR. This suggests that the IMR in Baltimore is less due to the typical top reasons for infant death and instead because of underlying reasons more specific to the community. 
Data from the **MLR** (x-values: teen birth rate, %born with satisfactory birth weight, % delivered at term, life expectancy) have an average correlation of 37% from 2011-2015 implying that these factors combined are a better predictor for the city’s IMR. Focusing on one of these variables alone would not make a significant change to the rate. 

Results from the **cluster analysis** show that most neighborhoods in the black butterfly are at a disadvantage with higher IMR and with it higher teen pregnancies, lower % of births at term, lower % of births with satisfactory weights. There’s an L-shaped cluster that represents neighborhoods with lower IMR aligning with the white L. These results point to a racial disparity even in infant deaths which should encourage future solutions that focus more to providing care and education for racially-disadvantaged neighborhoods. 
## Solution
B’more for Healthy Babies (BHB) has seen real results with the CSAs they have worked closely with--Upton/Druid Heights, Park Heights, Patterson Park. When looking at the IMR for these three CSAs (listed below), two of the rates have increased since 2011.
(insert chart)
BHB has done a lot in preventing teen pregnancies, but that alone isn’t enough as our data suggests; it's crucial to address all contributing factors. Moving forward, it's important to implement initiatives that provide early prenatal care to women of all races, confirming that expecting mothers are following a healthy lifestyle and are well-informed in infant care. There was a decrease in early prenatal care between 2012-2013; it fluctuated from 62.8% to 47.0% and never reached above 50% again for 2014/2015. Moving forward, we think the best solution is to strengthen initiatives like B’more for Healthy Babies so they have the resources to help prevent all risks of IMR in order to decrease the amount of premature births - one of the leading causes of infant deaths (UCI Health). 

