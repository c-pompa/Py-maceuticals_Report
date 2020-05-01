# Pymaceuticals_Report
Generate all of the tables and figures needed for the technical report of the study. The executive team requests a top-level summary of the study results.

### Tools and Methods
* Matplotlib & pyplot
* SciPy & Stats & Pearsonr (Coefficient & Regression)
* Numpy
* Pandas
* Python

## Description

Pymaceuticals Inc., a burgeoning pharmaceutical company based out of California. Pymaceuticals specializes in anti-cancer pharmaceuticals. Pymaceuticals began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

As a Data Analyst, I will need to complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. The Executive team has requested all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results.


## Observations

1. Drug Regimens 'Ramicane', 'Capomulin', 'Infubinol' and 'Placebo' had the most total mice left after Timepoint 45. 

2. Drug Regimens 'Ramicane' and 'Capomulin' both had much lower tumor size than 'Infubinol' and 'Placebo'. 'Ramicane' and 'Capomulin' were ~20 mm3 lower than 'Infubinol' and 'Placebo'. 

3. I found it interesting that the Placebo has more mice after Timepoint 45 over 6 other Drug Regimens. Also, The correlation between Mouse Weight(g) and Average Tumor Size for Mice on 'Capomulin' Drug Regimen factors to 0.84. A good coorelation to the issue.

### Report Includes: 

* Checking data for duplicate mice and remove any data associated with that mouse ID.

* Generating a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generating a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot`.  Represents the number of mice per time point for each treatment regimen throughout the course of the study.

* Generating a line plot of time point versus tumor volume for a single mouse treated with Capomulin.

* Generating a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculating the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
