# Autolib-electric-car-IP-WEEK-3

##  Question
** ### To investigate a claim about the blue cars from the provided Autolib dataset.

### An example of claim to test would be "Is the number of Bluecars taken in area X different than in area Y? Is it greater in area X than in area Z? Etc”. The selected periods of interest be either weekdays or weekends but not a mix of both. You can also consider postal codes 75015 vs 75017 to some of the areas of interest. 

## **My Hypothesis


### MY Null Hypothesis is that the sum of total number of blue cars are NOT the same in most days of the week.
### My alternative is that the sum of total number of blue cars are the same in most days of the week.


## ***Project Objectives**
### Define the question, the metric for success, the context, experimental design taken and the appropriateness of the available data to answer the given question.
### Find and deal with outliers, anomalies, and missing data within the dataset.
### Plot appropriate univariate and bivariate summaries recording our observations.
### Implement the solution by performing hypothesis testing.
### Challenge our solution by providing insights on how we can make improvements.

### Imports
```
# imports
import numpy as np
import pandas as pd
import pandas_profiling

# Importing Matplotlib
%matplotlib inline
!pip install matplotlib

import pylab

# Import seaborn
import seaborn as sns

from sklearn.linear_model import LinearRegression


# standazing
from sklearn.preprocessing import StandardScaler

from scipy import stats
from scipy.stats import norm
```
# What i was able to do

### Making use of visualizations eg creating
### Bar graphs, pie charts, histograms, scatter plots, Line graphs,heat maps and finding distibutions of the factors.
### Making use of Measures of Dispersion/Variability/Spread


###Finding 
* Mean

* Range

* Quantiles

* Skewness

* Kurtosis

* checking correlations
*Developing a Correlation matrix
Carrying out linear regression
Identifying z test and p value
Drawing a conclusion for your hypothesis accepting or regecting it
*
### Screen shots
![Image of Household sizes](https://github.com/codybaraks/Autolib-electric-car-IP-WEEK-3/blob/master/histo.PNG)
#### PairPlot

![Image of Household sizes](https://github.com/codybaraks/Autolib-electric-car-IP-WEEK-3/blob/master/pie.PNG)
#### PieChart

![Image of Household sizes](https://github.com/codybaraks/Autolib-electric-car-IP-WEEK-3/blob/master/LineGraph.PNG)
#### LineChart

![Image of Household sizes](https://github.com/codybaraks/Autolib-electric-car-IP-WEEK-3/blob/master/scatter.PNG)
#### Scatter Plot

![Image of Household sizes](https://github.com/codybaraks/Autolib-electric-car-IP-WEEK-3/blob/master/heatmap.PNG)
#### Heatmap

![Image of Household sizes](https://github.com/codybaraks/Autolib-electric-car-IP-WEEK-3/blob/master/correlationmatrics.PNG)
#### Correlation Matrix






