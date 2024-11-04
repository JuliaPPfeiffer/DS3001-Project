Research Question: What are the emission levels over time per country? What model provides the most accurate predictions of emission levels? 

1. What is an observation in your study?

Observations in our study are a country's data on multiple environmental measures for one specific year (ranging from 1990 to 2020). 

2. Are you doing supervised or unsupervised learning? Classification or regression?

Since our goal is to predict emissions levels over time per country, we will be conducting a regression by comparing the performance of various linear regression models (supervised learning). After producing our models, we will be able to compare the predictions of emission levels per country to the true values from the original dataset. 

3. How will you prepare the data specifically for your analysis? What models or algorithms do you plan to use in your analysis? How? - Eva

For our analysis, we will construct a pipeline to ensure consistent data manipulation throughout the process. This pipeline will also enable us to perform feature engineering and decide on any additional variables we might want to include. We’ll address missing values here as well, determining the best approach to fill them in, as there are quite a few. We plan to try several models but will focus primarily on linear regression, as it aligns with what we learned in class. We'll begin by testing simple linear regression models to examine how individual features correlate with emissions. From there, we’ll move to multiple linear regression and focus on tuning hyperparameters. We’ll then explore polynomial regression, which can detect non-linear relationships in the data. If these approaches don’t yield good results, we may consider models not covered in class or reassess the quality and suitability of the data.

4. How will you know if your approach "works"? What does success mean? - Larissa

We will evaluate our model using regression metrics such as RMSE to measure the error of our predictions on the test data. Success will mean that we have low error and the model is able to accurately predict the total emissions of a country based on data such as the GDP, total population, year, etc.

5. What are weaknesses that you anticipate being an issue? How will you deal with them if they come up? If your approach fails, what might you learn from this unfortunate outcome?

6. How will you communicate or present your results?
   
To effectively communicate our results we will use a combination of visualizations, performance metrics, and tables. As we will mainly be using linear regression, tools such as a regression coefficient table and confusion matrix will be important to explain our models better, allowing us to show what values were the most impactful and how accurate our models are. We can also communicate this data through line plots representing our predicted and actual emission levels for different countries, and bar charts showing the RMSE and R^2 values for our different models. By combining the performance metrics and tables with visualizations of our data, we should be able to accurately communicate our results as well as explain any issues or problems that arise in our models.

