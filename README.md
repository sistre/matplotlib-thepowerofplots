# matplotlib-thepowerofplots
Matplotlib Homework - The Power of Plots
 by Sean Istre

Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego, specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.

In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. The notebook contained within generates all of the tables and figures needed for the technical report of the study and a top-level summary of the study results.

The notebook accomplishes the following:

1. Checks the data for any mouse ID with duplicate time points and remove any data associated with that mouse ID.

2. Generates a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

3. Generates a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the number of total mice for each treatment regimen throughout the course of the study.

4. Generates a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

5. Calculates the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculates the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

6. Generates a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

7. Generates a line plot of tumor volume vs. time point for mouse s185 (a mouse treated with Capomulin).

8. Generates a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

9. Calculates the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment and plots the linear regression model on top of the scatter plot.

It also contains three observations or inferences that can be made from the data made by myself at the top of notebook.
