# Global Terrorism
Three Tasks:
* EDA
* Bayesian Inference
* Predict 1993

## Motivation
In the process of maintaining the GTD, the year 1993 has zero recorded instances. Due to the many actors maintaining the dataset, this year has been lost.

The goal is to impute the number of bombing/explosions that occurred in 1993. (Note that there is no answer, in order to test your case)

The structure of your project must include three components: exploratory data analysis, Bayesian inference to examine the difference in incidences across the globe, and a model to impute the missing values.


## Data
The data can be found in the [Global Terrorism Database](https://www.kaggle.com/START-UMD/gtd) kaggle dataset. It also lays out the different features and its descriptions on there.

## Methods
### EDA
Data Visualization:
* Matplotlib
* Seaborn
* Plotly

### Bayesian Inference
Southeast Asia:
* Pymc3

### Predict 1993
Bombings:
* Pymc3
* Linear Regression

## Findings
### EDA
Looking at the graphs we can see that the number of terrorist attacks increased as time increased and when broken into region, it is clear that the Middle East suffered the most in terroist attacks especially post 9/11. 

### Bayesian Inference
In Southeast Asia, we see that the Philippines has suffered the most in terrorist attacks compared to other countries in the area. Especially in the 90s, we see an uptick compared to the other Southeast Asian countries. Then after the turn of the millenia, we see that the Philippines and Thailand have similar trends in the number of attacks and the number of people killed in those attacks. Using hypothesis testing, I wanted to see is there really a significant difference between the Philippines and other countries. The answer was yes, except for Cambodia which may be because there is too little data to be compared with.

### Predict 1993

