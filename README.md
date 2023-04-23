# SC1015 Data Science Project: World Happiness Report
## About 
Our Data Science Mini-Project focuses on the Happiness Scores of countries found in the 2019 World Happiness Report along with their respective data of the variables mentioned in the report. In the World Happiness Report, variables affecting a country's happiness levels are mentioned, namely GDP per capita, Social support, Healthy life expectancy, Freedom to make life choices, Generosity and Perceptions of corruption. However, the data associated with these variables are just a measure of the extent to which the citizens perceive these factors affect their happiness levels. Thus, the data alone is insufficent in predicting a country's Happiness Score. Hence, we also looked at datasets of the actual values of each of these variables i.e. Actual GDP per Capita, Social support indicator, Healthy life expectancy (from the Human Development Report), Human Freedom Index, CAF World Giving Index and Trust in government indicator. All these are also data from 2019. 

## Problem Definition
- How can we predict a country's Happiness Score?

## Models Used
1. Linear Regression
2. Random Forest Regression

## Libraries Used
1. Pandas
2. NumPy
3. seaborn
4. Matplotlib
5. country_converter
6. scikit-learn Models (Linear Regression, Random Forest Regressor)
7. scikit-learn SimpleImputer

## Conclusion
- Generosity and Trust in government aren't highly correlated with happiness levels
- Multiple variables shows high correlation with happiness levels
- Linear Regression model does not suit the problem well when a handful of variables are highly correlated with happiness levels
- Random Forest Regression is better suited in such cases
- Possibility of "noise"/confusion due to the model having to take account of less significant variables
- Small dataset makes training diffcult. Thus, accuracy is still hard to minimise 

## References
- https://www.kaggle.com/datasets/synful/world-happiness-report
- https://data.worldbank.org/indicator/NY.GDP.PCAP.CD
- https://data.oecd.org/healthrisk/social-support.htm
- 
- https://www.cato.org/human-freedom-index/2019
- https://www.cafonline.org/docs/default-source/about-us-publications/caf_wgi_10th_edition_report_2712a_web_101019.pdf
- https://data.oecd.org/gga/trust-in-government.htm
- https://pypi.org/project/country-converter/


