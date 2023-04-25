# Covid_Happiness_Emissions
Pandas and Matplotlib data exploration and visualization 

Three datasets 
coviddf= pd.read_csv('https://raw.githubusercontent.com/BriDeWaltCCC/PFDADataSets/main/WHO-COVID-19-global-table-data-31-08-21.csv')
happydf = pd.read_csv('https://raw.githubusercontent.com/BriDeWaltCCC/PFDADataSets/main/world-happiness-report-2021.csv')
emissionsdf = pd.read_csv('https://raw.githubusercontent.com/BriDeWaltCCC/PFDADataSets/main/Methane_final.csv')

Original data
https://www.kaggle.com/datasets/umeshkumar017/who-covid19-data-tabe
https://www.kaggle.com/datasets/ajaypalsinghlo/world-happiness-report-2021
https://www.kaggle.com/datasets/ashishraut64/global-methane-emissions

Tasks
1. corelation between two variable and graph
2. significance of correlation
3. average value by region and graph note the max and min 

Extra 
exploration was performed in the Covid dataset to identify top cases by county and top deaths by country 
since the top values are absolute numbsers new features was created to calculate the death as a % of cases
This new feature provided better insight into 
