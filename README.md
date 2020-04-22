# ATMS-597-Project-5

Group C: KMSN (Madison, WI)

Group Members: Kevin Gray, Michael Sessa, Rose Miller

Objectives:

Train and test a logistic regression model to predict whether the precipitation is frozen or liquid (rain/snow)
Train and test a decision tree model to predict whether the precipitation is frozen or liquid (rain/snow)
Next, compare both of the models on their performance in relation to the climatology of the location in terms of the Brier skill score.

Data:

Data was downloaded from the ASOS FTP archive: : ftp://ftp.ncdc.noaa.gov/pub/data/asos-fivemin/.

This data was presented in five-minute intervals for many stations. The station data for this project is: KMSN.

Methods:

METAR data was processed and parsed using metpy  to create a dataframe that can be read by pandas as a csv file.



Results:

Logistic Regression: 

Brier Skill Score=0.9398334216972509


Decision Tree: 


Brier Skill Score=0.9546344770308283


References:

https://www.ncdc.noaa.gov/data-access/land-based-station-data/land-based-datasets/automated-surface-observing-system-asos
https://scikit-learn.org/stable/auto_examples/tree/plot_tree_regression.html
https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html
https://scikit-learn.org/stable/modules/generated/sklearn.metrics.brier_score_loss.html
https://unidata.github.io/MetPy/latest/examples/plots/Station_Plot.html 
