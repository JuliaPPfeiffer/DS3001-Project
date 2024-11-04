Research Question: What are the emission levels over time per country? What model provides the most accurate predictions of emission levels? 

1. What is an observation in your study?

Observations in our study are a country's data on multiple environmental measures for one specific year (ranging from 1990 to 2020). 

2. Are you doing supervised or unsupervised learning? Classification or regression?

Since our goal is to predict emissions levels over time per country, we will be conducting a regression by comparing the performance of various linear regression models (supervised learning). After producing our models, we will be able to compare the predictions of emission levels per country to the true values from the original dataset. 

3. How will you prepare the data specifically for your analysis? What models or algorithms do you plan to use in your analysis? How?

For our analysis, we will construct a pipeline to ensure consistent data manipulation throughout the process. This pipeline will also enable us to perform feature engineering and decide on any additional variables we might want to include. We’ll address missing values here as well, determining the best approach to fill them in, as there are quite a few. We plan to try several models but will focus primarily on linear regression, as it aligns with what we learned in class. We'll begin by testing simple linear regression models to examine how individual features correlate with emissions. From there, we’ll move to multiple linear regression and focus on tuning hyperparameters. We’ll then explore polynomial regression, which can detect non-linear relationships in the data. If these approaches don’t yield good results, we may consider models not covered in class or reassess the quality and suitability of the data.

4. How will you know if your approach "works"? What does success mean?

We will evaluate our model using regression metrics such as RMSE to measure the error of our predictions on the test data. Success will mean that we have low error and the model is able to accurately predict the total emissions of a country based on data such as the GDP, total population, year, etc.

5. What are weaknesses that you anticipate being an issue? How will you deal with them if they come up? If your approach fails, what might you learn from this unfortunate outcome?

While building our models and doing our early data analysis, we noticed a few spots that may become an issue. One of the main areas that could become an issue is the data availability in the dataset. While the data that we are using is quite large, contains many variables, and spans many years, some variables are notably more complete (have less Na's) that others. We will need to take this into account when doing our regression modeling, and be conscious of how this could skew results. To deal with this, we may opt to not include certain variables in our model building if the data avaiability is sizeably less than other variables that are mostly complete. This could results in limiting our study to a cartain range of years where data is more available, or removing a variable where the dataset is not large enough. If there is an important variable that has a large number of missing values, we could also work to fill in these missing values, and the pipeline we develop would include this process if nesccesary. Another problem we could run into would be if our model does not reflect what emissions trends tell us is happening in reality (if our origional goal fails). If this is the case, we can include other types of models like polynomial regression to see if there are any non linear relationships occuring and adjust accordingly. We can learn from this process that modeling is difficult and even step one, finding complete data that matches your stufy perfectly, can be difficult. However, we are optimistic that even if our aproach fails, we could investigate other modeling processes not covered in class to create a better model for our research question. 

6. How will you communicate or present your results?
   
To effectively communicate our results we will use a combination of visualizations, performance metrics, and tables. As we will mainly be using linear regression, tools such as a regression coefficient table and confusion matrix will be important to explain our models better, allowing us to show what values were the most impactful and how accurate our models are. We can also communicate this data through line plots representing our predicted and actual emission levels for different countries, and bar charts showing the RMSE and R^2 values for our different models. By combining the performance metrics and tables with visualizations of our data, we should be able to accurately communicate our results as well as explain any issues or problems that arise in our models.

