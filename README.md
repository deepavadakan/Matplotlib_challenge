# Matplotlib_challenge


# Pymaceuticals Inc Study

---

A study was done on 249 mice identified with SCC tumor growth. The mice were treated with a variety of drug regimens over a course of 45 days. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. The following report summarizes the analysis of the data resulting from this study.

* 1. **Summary Statistics Table** consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

<img src="../Images/summary_statistics_table.png" width="400">

* 2. **Bar Chart** that shows the number of total mice for each treatment regimen throughout the course of the study.

<img src="../Images/mice_bar_chart.png" width="400">

* 3. **Pie Chart** using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.

<img src="../Images/mice_pie_chart.png" width="400">

* 4. **Box and whisker Chart** of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot.

<img src="../Images/drug_comparison.png" width="400">

* 5. Generate a line Chart for a single mouse of tumor volume vs. time point for that mouse, that was treated with Capomulin.

<img src="../Images/mouse_b128.png" width="400">

* 6. **Scatter chart** of mouse weight versus average tumor volume for the Capomulin treatment regimen. Calculate the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot

<img src="../Images/correlation.png" width="400">

---

## Observation and Insights

* 1. Each drug had sample sizes of over 150 mice. This is a sufficient sample size to detect the effect of the drugs on the tumor volume.

<img src="../Images/mice_bar_chart.png" width="400">

* 2. There was an almost equal distribution of male and female mice. The results of the study since there was an almost equal disribution of male and female mice.

<img src="../Images/mice_pie_chart.png" width="400">

* 3. Capomulin was effective in reducing the volume of the tumor over the 45 day period. Ramicane was also equally effective, with Ramicane doing a slightly better job on average. Both drugs, reduced the tumor volume by almost the same amount. In comparison, Infuubinol and Ceftamin increased the tumor volume rather than reducing it. It would be interesting to continue the experiment to see if Capomulin and Ramicane would reduce the tumor volume and get rid of it entirely over time.
<img src="../Images/drug_comparison.png" width="400">


* 4. There is a definite correlation between the mouse weight and the average tumor volume. Researchers will have to consider the weight of the mice and make sure that it is the same across the sample size to ensure that the results reflect the effect of the drug alone.
<img src="../Images/correlation.png" width="400">
