# Matplotlib 

In this repository I showcase what I have learned with Python Matplotlib and apply it to a real-world situation and dataset:

"As a senior data analyst at the company, you've been given access to the complete data from their most recent animal study. In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. You have been tasked by the executive team to generate all of the tables and figures needed for the technical report of the study. The executive team also has asked for a top-level summary of the study results."

## How the Analysis was executed:

* Checked the data for any mouse ID with duplicate time points and removed any data associated with that mouse ID.

* Used the cleaned data for the remaining steps.

* I generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Then I created a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the number of total mice for each treatment regimen throughout the course of the study.

* Next, I generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Continuing on, I calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculating the quartiles and IQR and quantitatively determined if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, a box and whisker plot of the final tumor volume for all four treatment regimens was made and I highlighted any potential outliers in the plot by changing their color and style.

* A mouse was then selected that was treated with Capomulin and generated a line plot of tumor volume vs. time point for that mouse.

* A scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen followed.

* The correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment were calculated. Then I plotted the linear regression model on top of the previous scatter plot.

### Copyright

Trilogy Education Services © 2020. All Rights Reserved.
