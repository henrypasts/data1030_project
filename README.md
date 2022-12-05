# DATA1030 Final Project

requirements
python==3.10
numpy==1.22.4
matplotlib==3.5.2
sklearn==1.1.1
pandas==1.4.2
xgboost==1.5.1
shap==0.40.0
ta==0.10.2
yfinance==0.1.75


The question I was trying to answer in this repository is whether we can accurately and profitably predict the direction of the next day's price for the S&P 500 using previous price values and various technical analysis indicators.

A description of the indicators added can be found in src/indicator_description.ipynb and how they were optimized can be found in src/indicator_optimization.ipynb. 

In src, there are other miscellaneous .ipynb files that were used to compile the data which is stored in data/S&P500 Data.xlsx. 

The results of the project can be found in results/results.ipynb, which includes the machine learning pipeline, the optimization of the indicators using GridSearchCV and various other figures that were used to explain the results found in report/report.pdf. 

Figures can be found in the figures folder. 

For more details on the project and its results, please refer to the report in report/report.pdf.




