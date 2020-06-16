# Analyze-A-B-Test-Results-for-A-New-Webpage


### Objective and key findings
In this project, I used both a/b test and regression model to test whether the e-commerce company should implement the new page, keep the old page, or perhaps run the experiment longer to see which page brings a higher costmer conversion rate. Based on the result, only the coefficient for CA_abpage is statistically significant. Holding all other variables constant, a user from Canada and receives a new page is 1.078 times more likely to convert. This number doesn't provide much pratical significance, unfortunally. The coefficients for other variables are not statistically significant, meaning they have no impact on the user coversion rate.

To sum up, we do not have enough evidence to reject the null hypothesis, and therefore, the company should keep the old page.


### Install

`import pandas as pd` 

`import numpy as np`

`import random`

`import matplotlib.pyplot as plt`

`from scipy import stats`


### Contents

- Part 1:Probability
- Part 2:A/B test
- Part 3:Logistic Regression

