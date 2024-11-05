# Are We All Advancing?

## Examining Income Gains and Gaps Over Time and Across States

Created by Andrew Baker

### Description

This project seeks to illuminate the complexities of income inequality in the United States by examining income distribution across a wide spectrum of metrics: income percentiles, state-by-state comparisons, and within-state disparities. Through a data-driven analysis, it explores how income levels have evolved over time for various percentiles, adjusting for inflation to reveal the real impacts of economic growth on different segments of the population. Additionally, the project highlights how income inequality persists not only between states but also within states, where top income earners pull further away from those at the median and lower levels.

By exploring demographic patterns within the highest income brackets, the analysis uncovers systemic biases related to race, ethnicity, and gender, shedding light on who benefits most in today’s economic climate. Ultimately, this project underscores the multifaceted nature of income inequality, providing a comprehensive perspective on who is truly “better off” in America, while prompting considerations for more equitable economic policies.

### Final Output
![Project Screenshot](static_final/Are%20We%20Better%20Off_%20FINAL.png)
[View the full project PDF](./static_final/Are%20We%20Better%20Off_%20FINAL.pdf)

### Data Source

https://www.minneapolisfed.org/institute/income-distributions-and-dynamics-in-america/data-center

https://www.data-is-plural.com/archive/2023-10-11-edition/

#### Description
Titled "Income Distributions and Dynamics in America", this set was found through Data is Plural. The goal of this reasearch was to gather more information regarding income disparities, as it includes statistics on "income percentiles, shares, growth rates, persistence, and more for many U.S. demographic groups at national and state levels." This data will be useful for getting income levels at the state level, allowing comparison of how inequality differs by state income tax.

#### Estimates
There are a handful of datasets from this research (pctl_of_inc, prop_share, inc_share, inc_change_distributions, transition_matrix), and has information on general demographics such as person/household level, year, geo_var, for a total of around 10 columns. Moreover, each of the above datasets has their own unique columns relevant to the topic at hand, giving a grand total of around 25 to 30 columns. Lastly, the two larger of these datasets (inc_change_distributions and transition_matrix) contain around 2 million rows.

#### Usage
The main two datasets which were used for this project were pctl_of_inc and prop_share. The former was used for all work regarding percentile analysis, and the latter was used for exploring the demographics of the upper percentiles.

