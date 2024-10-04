# Name
Andrew Baker

# Description
The goal of this project is to explore the levels of income inequality accross the United States and this issue's relationship to the U.S.'s tax structure. I would like to look at how this inequality has varied in the U.S. as a whole over the past 50-60 years, as well as how these changes align with alterations made to federal income tax levels in hopes of finding evidence of tax cuts leading to a greater tax burden on lower income levels. Moreover, I would also like to look at how income inequality varies state by state and see if varying state/local income tax levels are playing a role this variation.

The motivation of this idea is we have seen an increase in income inequality since the mid to late 20th century without any signs of stopping. During this time, we have also experienced numerous versions of tax cuts, whether for everyone or just those at the top. I would like to look at how income levels evolve as these policies are instituted in hopes of shedding light on how tax policy can drive inequality.

Lastly, if possible, I think it would be interesting to compare the U.S. to other developed countries and their levels of inequality as well as their tax structures.

# Data Sources
## Source 1
### URL
https://www.minneapolisfed.org/institute/income-distributions-and-dynamics-in-america/data-center

https://www.data-is-plural.com/archive/2023-10-11-edition/

### Description
Titled "Income Distributions and Dynamics in America", this set was found through Data is Plural. The goal of this reasearch was to gather more information regarding income disparities, as it includes statistics on "income percentiles, shares, growth rates, persistence, and more for many U.S. demographic groups at national and state levels." This data will be useful for getting income levels at the state level, allowing comparison of how inequality differs by state income tax.

### Estimates
There are a handful of datasets from this research (pctl_of_inc, prop_share, inc_share, inc_change_distributions, transition_matrix), and has information on general demographics such as person/household level, year, geo_var, for a total of around 10 columns. Moreover, each of the above datasets has their own unique columns relevant to the topic at hand, giving a grand total of around 25 to 30 columns. Lastly, the two larger of these datasets (inc_change_distributions and transition_matrix) contain around 2 million rows.

## Source 2
### URL
https://data.grid-database.org/#/select_data

https://www.data-is-plural.com/archive/2022-11-09-edition/

### Description
GRID, or the Global Respository of Income Dynamics provides "individual" (stated on website, but seems to be at the country level) level statistics on income inequality and dynamics. This contains time series data for not only the US but also several other countries, which can be useful if wanting to compare the US to other developed countries. In other words, we can look at how income inequality varies accross these countries as well as their tax systems, similar to the comparison among states.

### Estiamtes
For example, upon downloading all possible data for the U.S., there appears to be one observation/row for each year there is data. Moreover, you can get information on up to 92 different columns, and there are up to 13 countries to collect data for.

## Source 3
### URL
https://www.bea.gov/data/income-saving/personal-income-county-metro-and-other-areas

https://apps.bea.gov/regional/downloadzip.htm

### Description
Titled "Personal Income by County, Metro, and Other Areas", this source contains information regarding the personal income of Americans at a number of different levels. Two example datasets here are "Annual personal income and employment by state" and "Annual personal income by county". This gets us data at a level lower than state, which will get us a more refined sense of where exactly income inequality is worst. Moreove, because of differing local tax levels, we can also try to do a comparison-- similar to the state level-- of local inequalities and how they are affected by differing policies.

### Estimates
For example, the Annual personal income by county data has a dataset for each state, and within this there are statistics for each county regarding income levels and population. There is information like this for each county in the US, and the data covers 1969 to modern day in time series format.

# List of Questions

1) I think I would just like to know if this topic is refined enough for the purposes of this course. Is this something you think is possible in one quarter, or is there instead a way I should exapand this topic?

2) Are there any major data sources that I am missing and should be aware of?