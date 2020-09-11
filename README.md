# matplotlib_challenge
Matplotlib Homework - The Power of Plots
## Background
As a senior data analyst at Pymaceuticals Inc., I was given access to the data from their most recent animal study. This included 249 mice identified with SCC tumor growth that would go through a
45 day treatment with different drug regimens. This study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens.  I generated all of the tables and figures needed for the technical report of the study.

## Analysis
1) Checked for duplicating data
2) Cleaned data
3) Generated a summary statistics table (mean, median, variance, standard deviation, and SEM)
4) Generated a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot`
5) Generated a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot`
6) Generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers
7) generated a line plot of tumor volume vs. time point
8) Generated a scatter plot of mouse weight versus average tumor volume
9) Calculated the correlation coefficient and linear regression model


### Observation 

My observation for the bar chart, Total Number of Mice Per Treatment, is the Drug Regimens, Capomulin and Ramicane were used as treatment the most with the mice. Propriva was shown to be used the least in treatment. However, all treatments counted were above 120.

The line plots were observed showing the tumor volume for a Capomulin treated mouse is decreasing steadliy over time. The progression of time allows the tumor volume to decrease.

The scatter plot allows for the observation that the increase of weight is correlated to the increase of the tumor volume.