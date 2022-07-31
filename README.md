# GDP-Life-Expectancy-Relationship

In this simple project, my goal was answer whether or not there is a relationship between life expectancy (in years) and GDP. 

In the dataset, I was provided data containing the Life Expectancy (at birth in years) and GDP (in trillions USD) for 6 countries between 2000 and 2015.

The 6 countries included in the sample are:
    1) Chile
    2) China
    3) Germany
    4) Mexico
    5) USA
    6) Zimbabwe 

The data was originally mined from the World Health Organisation (WHO) & the World Bank and then provided in a pre-cleaned dataset titled 'all_data.csv' which I downloaded from Codecademy as part of my 'Portfolio Project' task. 


-- Results & Conclusions --

Upon performing EDA on the dataset in Python, I can conclude that within the 6 sampled countries, there is an extremely strong positive linear relationship between Life Expectancy and GDP. This conclusion is not only reinforced by the scatterplot visuals produced in Matplotlib but by calculating the Pearson Correlation Coefficient (PCC) for each country. 

The PCC (r) measures the strength of a linear relationship between two quantitative features of a dataset, with values close to 1 indicating an extremely strong positive linear relationship. The PCC for each country was > 0.900, highlighting an almost perfect positive linear relationship between life expectancy and GDP. 


-- Issues & Improvements -- 

Although the data and logical thinking would suggest a strong positive linear relationship between Life Expectancy & GDP, we have only taken data into account from 6 countries. In order to reinforce our conclusion, we must increase our sample size to determine whether this relationship still holds for all additional entities we sample. 
