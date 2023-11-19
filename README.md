# DS4002Project3

## Contents
This repository contains the contents to replicate our project concerning measuring the Consumer Price Index (CPI). 

Hypothesis: The correlation analysis between an economy-wide stock index, a tech index, and the Consumer Price Index (CPI) will reveal a weaker relationship between the tech index and the CPI compared to the economy-wide index, suggesting that the CPI is an inadequate measure of inflation in accounting for technological advancements' impact on pricing.

Research Question: Is the CPI a good measure of inflation when accounting for technological advancement?

Executive Summary: 
This research project investigates the relationship between an economy-wide stock index, a tech index, and the Consumer Price Index (CPI). We will use statistical and machine learning methods to test the association between the CPI and indices. Our results will quantify how much of the CPI can be explained by solely the economy-wide stock index and the impact of technology on the CPI.

# SRC
## Installing/Building the Code
Ensure the data and required packages are imported and loaded into the working directory before running the code.

## Usage of Code
Both jupyter notebooks EDA_01.ipynb anad EDA_02.ipynb create exploratory plots 


# DATA
The data on the CPI can be accessed from the St.Louis Fed website. The S&P data  and VGT data can be accessed through Yahoo Finance. For each dataset, ensure the time period January 1st, 2010 to August 1, 2023, and the frequency is monthly. 

**Data Dictionary**
| Feature Name  | Description |
| ------------- | ------------- |
| Date  | Date recorded for stock price or CPI |
| Close_SNP  | Closing price of the S&P 500 |
| Close_VGT  | Vanguard Information Technology Index |****

# FIGURES

| Image  | Description |
| ------------- | ------------- |
| snp_cpi_prophet_forecast.png  | This shows the forecast of the CPI with SNP as a predictor |
| snp_vgt_cpi_prophet_forecast.png  | This shows the forecast of the CPI with SNP and VGT as a predictor|
| stock_cpi_overtime_standardized.png  | This shows a plot of the SNP, VGT, and CPI overtime with standardized values. |
| stock_cpi_overtime_standardized.png  | This shows a plot of the SNP, VGT, and CPI overtime with unstandardized values. |


# REFERENCES
L. Nakamura, "Measuring Inflation In A High-Tech Age," ResearchGate. [Online]. Available: https://www.researchgate.net/profile/Leonard-Nakamura/publication/5051632_Measuring_Inflation_In_A_High-Tech_Age/links/09e41506cc85d7f4c8000000/Measuring-Inflation-In-A-High-Tech-Age.pdf.

M. Reinsdorf and P. Schreyer, "Measuring consumer inflation in a digital economy," in Handbook of National Accounting: Use of Microdata to Improve the Quality of Economic Statistics, J. R. S. Agency, Ed. Cambridge, MA: Academic Press, 2020, pp. 375-396. [Online]. Available: https://doi.org/10.1016/B978-0-12-817596-5.00015-9.

