# Regression - predicting life expectancy

This task is focused on regression. You will work with a dataset containing information about life expectancy in different countries. Your goal is to predict the life expectancy based on other available features.

The task should be a training for regression, and testing out of multiple solving paradigms, such as Random Forest, Ridge regression, and KNN.

## Input

You are given a dataset in `data.csv` The dataset contains the following columns:

* Year - Year
* Status - Status of country, either developing or developed
* Life expectancy - Life expectancy of the country - ** column to predict **
* Adult Mortality - Death of adults (Probability, that people, who have 15 years, will die before living for 60 years (per 1 000 people)).
* infant deaths - number of dead infants per 1000 citizens
* Alcohol - How much alcohol is consumed (15+) (in liters of pure alcohol)
* percentage expenditure - Health expenditure as a percentage of Gross Domestic Product (GDP) per capita (%)
* Hepatitis B - Hepatitis B (HepB) immunization coverage among 1-year-old children (%)
* Measles - Number of reported measles cases per 1000 population
* BMI - Average Body Mass Index (BMI) of the entire population
* under-five deaths - Number of deaths of children under five years of age per 1000 population
* Polio - Polio (Pol3) immunization coverage among 1-year-old children (%)
* Total expenditure - Government institutions' health expenditure as a percentage of total government expenditure (%)
* Diphtheria - Coverage of immunization against diphtheria, tetanus, and pertussis (DTP3) among one-year-old children (%)
* HIV/AIDS - Number of deaths per 1000 live births due to HIV/AIDS (0-4 years)
* GDP - Gross Domestic Product per capita (in USD)
* Population - Country's population
* thinness 1-19 years - Proportion of children aged 10-19 years with a Body Mass Index (BMI) less than 2 standard deviations below the median (%)
* thinness 5-9 years - Proportion of children aged 5-9 years with a Body Mass Index (BMI) less than 2 standard deviations below the median (%)
* Income composition of resources - Human Development Index in terms of income composition of resources (index ranging from 0 to 1)
* Schooling - Number of years of schooling (years)


## Output

Load the `evaluation.csv` file and predict the life expectancy for each row. The output should be a CSV file with the following columns:
  
```
Country,Year,Life expectancy
Peru,2012,71.4
Peru,2013,72.6
...
```