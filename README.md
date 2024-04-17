# Individual_Project_DS_Fundamentals

 
Questions:

1. What variable has the biggest impact on the conviction rate in Connecticut?
2. Of the disproportionately impacted areas, is there a significant relationship between poverty and conviction rate?
3. How does an area's population size relate to its conviction rate?

Importance:
On July 1st, 2023, Public Act 23-79 went into effect in Connecticut, legalizing cannabis. Along with this change, a Social Equity Council was formed to determine which communities have historically been the most severely affected by the "war on drugs," so that Connecticut's adult-use cannabis program is equitably developed. The communities can be identified as Disproportionately Impacted Areas." To identify which communities are DIA, data was collected. The overall explanatory variables are as follows: Town(s) (Categorical), Median Household Income (Quantitative), Census Population (Quantitative), Conviction Count (Quantitative), Conviction Rate (Quantitative), and Geometry (Categorical). My goal with this project is to determine:
1. The most influential explanatory variable on conviction rate.
2. Whether there's a significant relationship between poverty and conviction rate.
3. The relationship between an area's population size and its conviction rate.

The data comes from public CT government data and is published by data.ct.gov. I did have to do a little bit of cleaning of the data, as there was an error in one of the rows where there may have been some kind of formatting error. There are also some incomplete entries which are excluded from my calculations.

In order to answer the questions, I used ``matplotlib.pyplot`` as ``plt``, ``pandas`` as ``pd``, ``sklearn.linear_model`` as ``LinearRegression``, ``scipy`` for ``stats``, and ``seaborn`` as ``sns``.

