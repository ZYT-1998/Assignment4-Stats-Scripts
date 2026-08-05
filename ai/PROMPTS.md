# AI Prompt Log

## Prompt 1: Initial data analysis

Create a Python statistics analysis using brain-size, iris, and wage datasets. Include data inspection, descriptive statistics, hypothesis tests, regression models, visualizations, and short student-level interpretations of the results.

## Prompt 2: Hypothesis testing

Using the brain-size dataset, test whether female and male participants have different VIQ scores. Include an independent-samples t-test and a nonparametric alternative. Also compare FSIQ and PIQ as paired measurements and compare participant weight by gender. Report the test statistic and p-value, and briefly explain what each result means.

## Prompt 3: Regression analysis

Create several regression models using the brain-size dataset. Include a simple linear regression, a regression with a categorical predictor, and a multiple regression predicting VIQ from Gender, MRI_Count, Height, and Weight. Display the model summaries and explain which predictors are statistically significant.

## Prompt 4: Iris and wage analyses

For the iris dataset, create a regression model using species and petal length to predict sepal width. For the wage dataset, compare an additive regression model with a model containing an education-by-sex interaction. Explain whether adding the interaction improves the model and whether the interaction is statistically significant.

## Prompt 5: Statistical extension

Create a separate Python notebook that uses ten thousand bootstrap samples to estimate a ninety-five percent confidence interval for the difference in mean VIQ between female and male participants. Include a graph of the bootstrap distribution and compare the bootstrap result with an independent-samples t-test.

## Follow-up prompt

Revise the notebooks so that all datasets are loaded from the ../examples folder. Keep the analyses divided into clear sections, include the important numerical output, and add brief interpretations without referring to or copying any statistics tutorial.