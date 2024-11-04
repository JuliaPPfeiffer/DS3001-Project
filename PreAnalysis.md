Research Question: What are the emission levels over time per country? What model provides the most accurate predictions of emission levels? 

1. What is an observation in your study?

Observations in our study are a country's data on multiple environmental measures for one specific year (ranging from 1990 to 2020). 

2. Are you doing supervised or unsupervised learning? Classification or regression?

Since our goal is to predict emissions levels over time per country, we will be conducting a regression by comparing the performance of various linear regression models (supervised learning). After producing our models, we will be able to compare the predictions of emission levels per country to the true values from the original dataset. 

3. How will you prepare the data specifically for your analysis? What models or algorithms do you plan to use in your analysis? How? - Eva

4. How will you know if your approach "works"? What does success mean? - Larissa

We will evaluate our model using regression metrics such as RMSE to measure the error of our predictions on the test data. Success will mean that we have low error and the model is able to accurately predict the total emissions of a country based on data such as the GDP, total population, year, etc.

5. What are weaknesses that you anticipate being an issue? How will you deal with them if they come up? If your approach fails, what might you learn from this unfortunate outcome?

6. How will you communicate or present your results?
   
To effectively communicate our results we will use a combination of visualizations, performance metrics, and tables. As we will mainly be using linear regression, tools such as a regression coefficient table and confusion matrix will be important to explain our models better, allowing us to show what values were the most impactful and how accurate our models are. We can also communicate this data through line plots representing our predicted and actual emission levels for different countries, and bar charts showing the RMSE and R^2 values for our different models. By combining the performance metrics and tables with visualizations of our data, we should be able to accurately communicate our results as well as explain any issues or problems that arise in our models.

