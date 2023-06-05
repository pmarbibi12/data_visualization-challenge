# data_visualization-challenge
by Pan Marbibi


Files:

Pymaceuticals {dir}:  
--pymaceuticals.ipynb (final submission)  
--pymaceuticals_starter.ipynb  
--.ipynb_checkpoints {dir}  
--data {dir}:  
----Mouse_metadata.csv  
----Study_results.csv  
  
Description:

The main file is pymaceuticals.ipynb

This notebook is used to sort and combine the data from the resources folder.
Using data visualization, this determines the best drug regimen that was used to reduce mice tumors.
drug_stats shows the drug regim statistics -- mean, median, variance, standard deviation, and SEM
numpyDrug shows the same statistics, but using a different method.
Bar charts are made from timepoint_count. One using Pandas method, while the other, using pyplot
Pie charts are made from sex_mice. One using Pandas method, while the other, using pyplot
final_results show the top 4 drug regimens and their results
Using the data in final_results, 4 boxplots are shown
cap_data takes the data from the drug regimen Capomulin, from cleanData
Line charts are used to determine the effectiveness of the Capomulin Drug Regimen
A scatter plot is used to show the relationship between the mice's weight and the average tumor volume of the mice from the Capomulin data.
The correlation coefficient and a linear regression model is shown next using the data from the scatter plot
