# Matplotlib-Challenge

## Background

Pymaceuticals Inc., is a burgeoning pharmaceutical company based out of San Diego that specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
The company conducted a study and 249 mice were identified with SCC tumor growth, and they were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.

## Analysis

in this challenge a script was created in pandas to generate the following information:
* A summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
* A bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the number of mice per time point for each treatment regimen throughout the course of the study.
* A pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
* The calculated final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 
* The calculated quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.
* Generate a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.
* The calculated correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot a linear regression on the previous scatter plot.

