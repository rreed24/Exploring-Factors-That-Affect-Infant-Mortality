# Infant Mortality Rate (IMR) in Baltimore
## Background 
Although the US's IMR is decreasing over time, its 5.8 infant deaths in every 1,000 births is still higher compared to other developed countries that average around 3.4 (Kamal et. al, 2019).
The IMR is particularly higher in the observed community statistical areas in Baltimore compared to other cities as in 2015, it averaged around 10.4.  Through Simple Linear Regression, Multiple Linear Regression and Cluster Analysis, we were able to analyze data related to the two of the three leading causes of IMR--premature birth and low birth weight (Baltimore City Health Department). 
Observing this data, we asked: What are the actions that can be taken to reduce and eliminate IMR in different neighborhoods in Baltimore? What are the patterns that can be explored to identify the factors that contribute to this rate?
## Why is this a problem to address?
IMR is an important indicator of a community’s physical health; a higher IMR suggests that the city is lacking in meeting human health needs in sanitation, nutrition, education, medical care, etc. Being that in 2009, Baltimore City had the 4th highest IMR in the nation, it’s necessary to address the actions that need to be taken to reduce this number by exploring the factors that contribute. In order to figure out how health institutions can implement better practices to reduce infant mortality rate in different neighborhoods in Baltimore, we started by asking the following questions:
What are the factors correlated to infant mortality rate in different neighborhoods in Baltimore? How significant are the correlations?
Are the connections between the factors stable over time?
Can we generate geographical patterns from our data? If so, what does it tell us?
## Multiple Linear Regression with Excel
We ran a multi-linear regression analysis on data from 2010 to 2015 and found that the Rsq values stayed almost the same every year. Thus, we concluded that there is a relatively stable relationship between  IMR and other factors.
(insert graph)
While there is a significant correlation between life expectancy and infant mortality rate (p-value equals 0.04 in 2015), percent of births delivered at term is at the margin of statistical significance in terms of its impact on infant mortality rate with p-value equals 0.06 in 2015.
(Insert regression data)
## Cluster Analysis
<img width="558" alt="Cluster" src="https://user-images.githubusercontent.com/60996310/77718568-9fde4b80-6fb9-11ea-8c5b-3c6f5b3ab8cd.png">
### Key

Group 1 (blue): low teen birth rate, high % of birth at term, high satisfactory birth weight, high prenatal care, low healthy food index, high life expectancy, relatively low infant mortality
Group 2 (orange): average teen birth rate, average % of birth at term, average satisfactory birth weight, average prenatal care, relatively low healthy food index, average life expectancy, relatively high infant mortality
Group 3 (yellow): high teen birth rate, high % of birth at term, average satisfactory birth weight, average prenatal care, high healthy food index, relatively high life expectancy, low infant mortality
Group 4 (green): relatively high teen birth rate, low % of birth at term, low satisfactory birth weight, low prenatal care, relatively low healthy food index, low life expectancy, higher infant mortality

Baltimore’s IMR mirrors the troubling statistic that neonatal mortalities (infant mortality within the first 28 days) is highest among infants with Black mothers (Kamal et. al, 2019). Although there is a limited number of CSAs within this dataset, the “Black Butterfly” and "White L" can be seen in our cluster analysis.

