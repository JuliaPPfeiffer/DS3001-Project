Dataset Source:

https://www.kaggle.com/datasets/alessandrolobello/agri-food-co2-emission-dataset-forecasting-ml

https://www.kaggle.com/datasets/zgrcemta/world-gdpgdp-gdp-per-capita-and-annual-growths

Our project combines two datasets from kaggle. The first dataset 'Agri-food CO2 emission dataset- Forecasting ML' describes CO2 emissions coming from the agri-food industry in 236 distinct countries from 1990-2020. The variables measured over this time period include emissions from Savanna fires, forest fires, crop residues, rice cultivation, drained organic soils, pesticides manufacturing, food product transportation, net forest conversion, household food consumption, food retail, on-farm electricity, food packaging, agrifood systems waste disposal, food processing, manufactoring fertilizers, Industrial Processes and Product Use (IPPU), manure applied to soil, manure left on pastures, fires on organic soils, fires in humid tropical forests, and on-farm energy use. Other demographic variables in this dataset are rural, urban, and total (male/female) populations. Additionally, total emissions, land covered by forests, and average temperature is recorded for each country. All of the data was taken from the Food and Agriculture Organization of the United States and the Intergovernmental Panel on Climate Change.

The other dataset that we are using is World GDP which measures variables of GDP, GDP growth (annually), GDP per capita, GDP per capita growth (annually), GDP PPP, and GDP PPP per capita on 266 distinct countries over the years of 1960-2020. All of the data comes from the World Bank. 


2. How will these data be useful for studying the phenomenon you're interested in?

3. What are the challenges you've resolved or expect to face in using them?

One challenge we faced was combining the two datasets that we have chosen to analyze. Each dataset contains data (on GDP or agrofood emissions) from the last few decades for different geographical areas. We joined these datasets together by geographical area, 
however, the two datasets have variation in naming for this variable. For example, the agrofood dataset contains data from both 
“China” and “China, mainland” while the GDP dataset does not. The GDP dataset lists certain categoriesunder geographical areas that are not in the agrofood dataset, such as “Fragile and conflict affected situations” or “Least developed countries: UN classification.” Additionally, the agrofood dataset contains data from 1990-2020 while the GDP dataset begins in 1960. These variations required more effort in the data cleaning process when combining the datasets, and we will likely have to leave out certain geographical areas from the GDP dataset. Although the GDP dataset contains more geographical areas, it also contains a large amount of missing data. Because of this, we may not be able to find significant relationships between certain variables or make accurate predictions for geographical areas/years with too much missing data. We partly resolved this issue by dropping variables that had more than 5 missing values for 
GDP. 
