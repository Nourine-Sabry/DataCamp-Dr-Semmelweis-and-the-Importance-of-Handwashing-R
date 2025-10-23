
# Dr. Semmelweis & the Importance of Handwashing

![Dr. Ignaz Semmelweis](/drsemmelweis-project/ignaz_semmelweis_1860.jpeg)

Using the Tidyverse to investigate how much did handwashing reduce monthly death rates on average. [Link to DataCamp project](https://app.datacamp.com/learn/projects/dr_semmelweis/guided/R)

## About the dataset

Two datasets have been used in this project:

1. **yearly_deaths_by_clinic.csv:** This dataset contains the number of women giving birth at the two clinics at the Vienna General Hospital between the years 1841 and 1846.
2. **monthly_deaths.csv:** This dataset contains data from 'Clinic 1' of the hospital where most deaths occurred.

## Objectives of the project

- Calculate the proportion of deaths per number of births for each year in yearly and month in monthly.
- Visualise for the yearly proportion of deaths coloured by clinic and the monthly proportion of deaths.
- Add a handwashing_started boolean column to monthly using June 1st, 1847 as the threshold; TRUE should mean that handwashing has started at the clinic.
- Calculate the mean proportion of deaths before and after handwashing from the monthly data.

## Tools used

- Tidyverse

## Acknowledgement

This project is based on the DataCamp project [**"Dr. Semmelweis and the Importance of Handwashing"**](https://app.datacamp.com/learn/projects/dr_semmelweis/guided/R).  
All datasets, instructions, and core project structure were provided by [DataCamp](https://www.datacamp.com/).  
This project was done for personal learning purposes. I do not claim ownership of the original project content.
