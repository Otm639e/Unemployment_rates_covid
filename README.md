# Unemployment_rates_covid
A UC Berkeley Project done for For Data 100 Fall 2021

Seeing Covid-19 data and its correlation with Unemployment rates throughout counties in the U.S.

The hypothesis I was testing was whether the unemployment numbers across counties can be explained by the number of cases across counties as well as masking rates across counties. This hypothesis can be confirmed if the R^2 value for the model that predicts unemployment levels from case and masking rates is above 0.6.

The model used was a linear regression model. This was an appropriate model to use because we want to use continuous quantitative variables: case numbers and masking rates, to predict a continuous quantitative variable: the amount of unemployed people in a county. The inputs to the model are case numbers and masking rates in each county, while the output is the amount of unemployed people in a given county.

The result can be seen in the Jupyter Notebook!!
