# Covid_Happiness_Emissions
Pandas and Matplotlib data exploration and visualization 

## Three datasets 
* coviddf= pd.read_csv('https://raw.githubusercontent.com/BriDeWaltCCC/PFDADataSets/main/WHO-COVID-19-global-table-data-31-08-21.csv')
* happydf = pd.read_csv('https://raw.githubusercontent.com/BriDeWaltCCC/PFDADataSets/main/world-happiness-report-2021.csv')
* emissionsdf = pd.read_csv('https://raw.githubusercontent.com/BriDeWaltCCC/PFDADataSets/main/Methane_final.csv')

## Original data source 
https://www.kaggle.com/datasets/umeshkumar017/who-covid19-data-tabe
https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2021
https://www.kaggle.com/datasets/ashishraut64/global-methane-emissions

## Task
1. corelation between two variable and graph
2. significance of correlation
3. average value by region and graph note the max and min 

## Extra 
* Exploration was performed in the Covid dataset to identify top number of cases by county and top number deaths by country 
* Since the top values are absolute numbsers new feature was created to calculate the deaths as a % of cases.
* This new feature deaths as a % of cases:  provide context for raw numbers so that rates of death can be compared across countries
