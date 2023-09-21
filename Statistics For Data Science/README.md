# Statistics For Data Science
Statistical is the science that studies data.

While statistics are the results of data presented in the form of tables, graphs and so on.

Statistics combines some techniques for drawing a reliable conclusion about a large group (population) by experimenting on a small group (sample) and summarizing the dataset.

## Types of Statistics Concepts
There are two types of statistics.
* ### Descriptive Statistics
Descriptive statistics summarizes/describes the population or sample dataset. It covers the topics : types of data, variables, distribution, central tendency, percentile and quartile, correlation, etc.
      
* ### Inferential Statistics
Inferential statistics is part of statistics that finds reliable inferences of population data from sample data. It covers Confidence Interval, Hypothesis Testing, Level of Significance, Central Limit Theorem, Point Estimator and Estimate, Standard Error, Analysis of Variance (ANOVA), Chi-Square Test, etc.
      

## Probability
Probability and statistics are two related but separate academic disciplines. Statistical analysis often uses probability distributions, and the two topics are often studied together.

## Descriptive Statistics
Descriptive statistics summarizes/describes the population or sample dataset. It covers the topics : types of data, variables, distribution, central tendency, percentile and quartile, correlation, etc.

* Measure of Central Tendency
* Measure of Spread/Dispersion
* Distribution/Skewness
* Correlation

## Outlier dan Anomaly
An outlier is an observation that lies an abnormal distance from other values in a random sample from a population.

An unexpected change within these data patterns, or an event that does not conform to the expected data pattern, is considered an anomaly.

### Outlier
Outliers are important because they can have a large influence on statistics derived from the dataset.

outlier are data that not in range between lower bound and upper bound of data.

to calculate lower bound an upper bound we can use this formula;
* IQR = Q3 - Q1
* LowerBound = Q1 - 1.5*IRQ
* UpperBound = Q3 + 1.5*IRQ

### Outlier Handling
Because outlier have a large influence on statistics derived from the dataset it usually removed if the data used for machine learning and other stuff. 

to do that we can select data that in the range between lower bound and upper bound of data.

### Missing Value Handling
The handling of missing data is very important during the preprocessing of the dataset as many machine learning algorithms do not support missing values.

the handling of this missing values is diffrent based on numerical or categorocal values of the data.

#### Numerical
To handle numerical missing values usually the median of data is used to fill the missing values.

#### Categorical
To handle categorocal missing values usually the mode of data is used to fill the missing values.


## Inferential Statistics - Confidence Intervals
A confidence interval is the mean of your estimate plus and minus the variation in that estimate. This is the range of values you expect your estimate to fall between if you redo your test, within a certain level of confidence.

the notebook contains;
* Take a sample
* Comparing mean
* make a Confidence Intervals.

## Inferential Statistics - hypothesis Testing
Hypothesis testing is a form of statistical inference that uses data from a sample to draw conclusions about a population parameter or a population probability distribution.

### Hypothesis Testing

Paired sampled ttest:- The paired sample testis also called dependent sample t-test. Its an uni variate test that tests for a significant ditference between 2 related variables. 
An example of this is if you where to collect the blood pressure for an individual before and after some treatment, condition, or time point.

HO :- means difference between two sample is 0

H1 :- mean diference between two sample is not 0
