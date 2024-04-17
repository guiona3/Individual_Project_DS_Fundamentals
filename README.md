# Individual_Project_DS_Fundamentals

#### Introduction:
On July 1st, 2023, Public Act 23-79 went into effect in Connecticut, legalizing cannabis. Along with this change, a Social Equity Council was formed to determine which communities have historically been the most severely affected by the "war on drugs," so that Connecticut's adult-use cannabis program is equitably developed. The communities can be identified as Disproportionately Impacted Areas." To identify which communities are DIA, data was collected. The overall explanatory variables are as follows: Town(s) (Categorical), Median Household Income (Quantitative), Census Population (Quantitative), Conviction Count (Quantitative), Conviction Rate (Quantitative), and Geometry (Categorical). My goal with this project is to determine:
1. The most influential explanatory variable on conviction rate.
2. Whether there's a significant relationship between poverty and conviction rate.
3. The relationship between an area's population size and conviction rate.

#### Selection of Data:
The data comes from public CT government data and is published by data.ct.gov. I did have to do some cleaning of the data, as there was an error in one of the rows where there may have been some formatting error. There are also some incomplete entries which are excluded from my calculations.

#### Methods:
In order to answer the questions, I used the Python tools ``matplotlib.pyplot`` as ``plt``, ``pandas`` as ``pd``, ``sklearn.linear_model`` as ``LinearRegression``, ``scipy`` for ``stats``, and ``seaborn`` as ``sns`` on JupyterLab.

#### Methods/Results:
I determined with multiple linear regression models that the poverty rate has the highest significance in a model with conviction rate as the response variable. 

In disproportionately impacted areas, there is a statistically significant relationship between poverty and conviction rate, as the $\beta$ coefficient is not close to zero, and the p-value is much smaller than 0.05. 
An area's population size is a poor indicator for predicting the conviction rate, with an $R^2$ value of 0.06495. For every unit increase in the census population, the conviction rate decreases by $-2.216853406310218 \times 10^{-5}$, which is not zero, so there is a fairly insignificant correlation.

