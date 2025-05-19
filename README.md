# Crime Pattern Analysis in Montgomery County, Maryland (2020–2024)

This repository contains the full analysis, code, and documentation for a quantitative social science research project exploring spatial and temporal trends in crime across Montgomery County, Maryland, from 2020 to 2024.

##  Research Questions

1. **Do crime rates vary by season and crime type?**
2. **Are violent crimes more geographically concentrated than non-violent crimes?**
3. **Do crime levels differ between weekends and weekdays?**

##  Summary

Using public data from [dataMontgomery](https://data.montgomerycountymd.gov), this project examines patterns in reported crimes across time and space. Statistical tests like the **Kruskal-Wallis H-test**, **Mann-Whitney U test**, and **Gini coefficient** were applied to test hypotheses about seasonal variation, geographic inequality, and temporal trends.

##  Tools & Environment

- **Language**: Python 3.11  
- **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`  
- **Structure**: Follows [Cookiecutter Data Science](https://drivendata.github.io/cookiecutter-data-science/) project layout.


##  Key Results

- **Seasonality**: Some property crimes, like vandalism and larceny, show significant seasonal variation.
- **Geographic Concentration**: Violent crimes are more concentrated than non-violent crimes across zip codes (Gini = 0.5863 vs. 0.5376).
- **Temporal Patterns**: Weekday crime rates are statistically higher than weekend rates (p = 0.0035, Mann-Whitney U test).

##  References

- McDowall et al. (2012) — *Seasonal Cycles in Crime*
- Weisburd et al. (2012) — *The Criminology of Place*
- Andresen (2016) — *Place-Based Crime Analysis*
- Cohn & Rotton (2000) — *Temporal Crime Patterns*




