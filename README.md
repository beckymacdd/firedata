# firedata
This repository contains all of of the data used within the Thesis "The Inequity of Injury: A Global Comparison of Fire Mortality". 

## Data Description
The file is given in a .csv format, with the following column headers:

| Column Header | Description                                                                                                                         |
|---------------|-------------------------------------------------------------------------------------------------------------------------------------|
| measure       | Measure used - always deaths.                                                                                                       |
| location      | Country considered.                                                                                                                  |
| sex           | Metrics given split according to gender. Valid values are: Male; Female; Both.                                                      |
| age           | Metrics given split according to age. Valid values are: Under 5; 5-14 years; 15-49 years; 50-69 years; 70+ years; Age-standardised. |
| cause         | Cause of death. Valid values are: All causes; Fire, heat and hot substances.                                                        |
| metric        | Details the type of data given. Valid values are: Number; Percent; Rate.                                                            |
| year          | Year of data.                                                                                                                       |
| val           | Value of fire related mortality, based on the metric given.                                                                         |
| upper         | Upper bound estimate of fire related mortality rate.                                                                                |
| lower         | Lower bound estimate of fire related mortality rate.                                                                                |


## Data Sources
Data is taken from the following sources 

| Data                                                      | Source            | Date             |
|-----------------------------------------------------------|-------------------|------------------|
| Mortality due to fire and flames                          | WHO               | Most recent year |
| Mortality due to fire and flames                          | IHME              | 2000-2019        |
| GNI per capita                                            | Worldbank         | 2017             |
| HDI                                                       | Worldbank         | 2017             |
| GII                                                       | Worldbank         | 2017             |
| Gini coefficient                                          | Worldbank         | 2017             |
| % of the population with access  to electricity           | IEA               | 2015             |
| % of the population with  access to clean cooking fuels   | IEA               | 2015             |
| % of the population living in  informal settlements       | Worldbank         | 2018             |
| Life expectancy                                           | WHO               | 2017             |
| Percentage of people that  drank alcohol in the last year | Ourworldindata    | 2018             |
| Annual precipitation                                      | Ourworldindata    | 2017             |
