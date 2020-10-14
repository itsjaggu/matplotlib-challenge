# Drug Regimen Research Analysis

This jupyter notebook performs following analysis on the given lab research dataset:

* Removes duplicate records from the data.

* Generates a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generates a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the number of total mice for each treatment regimen throughout the course of the study.

* Generates a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculates the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. 
  
* Calculates the quartiles, IQR, Upper and Lower Boundaries and quantitatively determines if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generates a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot.

* Selects a sample mouse that was treated with Capomulin and generates a line plot of tumor volume vs. time point for that mouse.

* Generates a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculates the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment.