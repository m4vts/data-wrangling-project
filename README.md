# What are the relationships between Socioeconomic Status factors and HIV/AIDS infection?
#### A data wrangling project report
#### By project group DW007:
 1. Junye Qu
 2. Megan van den Brink
 3. Onur Mavitas

## Research question
Some research claims that it is possible to observe correlations between wealth, household income, education and HIV prevalence. It is also mentioned that conditions that minorities lacking in certain socioeconomic factors have to deal with create inadequacies for HIV prevention (Pellowski et al., 2013). Socioeconomic status factors (SES) are what makes up a person their status socially and economically. Those factors include but are not limited to income, education, occupation, gender, sexuality, wealth, ethnicity and social class. Therefore, the research question of this project is:
What are the relationships between Socioeconomic Status factors and HIV/AIDS infection?
The project is focused on region, country, wealth, sexuality, availability of healthcare, gender and their correlation to HIV.

## Data sources
[AIDS | UNAIDS](https://aidsinfo.unaids.org) last accessed on : 16-01-2020
- Men who have sex with men
- People who know their status (%)

[World Health organization – HIV/AIDS](http://apps.who.int/gho/data/node.main.617?lang=en) last accessed on : 16-01-2020
- [Number of people (all ages) living with HIV Estimates by country](http://apps.who.int/gho/data/node.main.620?lang=en)
- [Number of new HIV infections Estimates by country](http://apps.who.int/gho/data/node.main.HIVINCIDENCE?lang=en)
- [Number of deaths due to HIV/AIDS Estimates by country](http://apps.who.int/gho/data/node.main.623?lang=en)
 
[The World Bank](https://www.worldbank.org/) last accessed on: 22-01-2020
- [GDP (current US$)](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD)
- [Prevalence of HIV, total (% of population ages 15-49)](https://data.worldbank.org/indicator/SH.DYN.AIDS.ZS)
- [Population](https://data.worldbank.org/indicator/SP.POP.TOTL)
- [Prevalence of HIV, total (% of population ages 15-49)](https://data.worldbank.org/indicator/SH.DYN.AIDS.ZS)
- [GINI index for income Inequality (World Bank estimate)](https://data.worldbank.org/indicator/SI.POV.GINI)
- [Incidence of tuberculosis (per 100,000 people)](https://data.worldbank.org/indicator/SH.TBS.INCD)
- [Unemployment, total (% of total labor force) (modeled ILO estimate)](https://data.worldbank.org/indicator/SL.UEM.TOTL.ZS)  
- [School enrollment, secondary (% gross)](https://data.worldbank.org/indicator/SE.SEC.ENRR)

[OECD| Data|Violence against women](https://data.oecd.org/inequality/violence-against-women.htm%23indicator-chart) last accessed on: 20-01-2020

[Maps - Sexual orientation laws](https://ilga.org/maps-sexual-orientation-laws) last accessed on: 24-01-2020

## Data wrangling methods 
### Data acquisition
For data acquisition multiple research papers were read, analyzed for import factors that have an impact on the odds of acquiring HIV. It was important to know what other data analyses were done on the subject to have an idea of what other types of connections could be discovered. Those same papers documented what datasets or websites were used, out of which reliable sources could be chosen.
Because the websites used were public, from institutions that are deemed trustworthy, and formatted well, it was not needed to use techniques involving JSON, XML or web crawling. Most of the datasets used were in Comma Separated Values format, except for the dataset stating countries their legal stance on same sex marriage.

## Data cleaning
