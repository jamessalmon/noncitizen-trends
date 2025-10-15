# noncitizen-trends
##**Analysis of non-citizen population changes in major U.S. cities, 2018–2023**
*A data-driven analysis of immigration trends in U.S. metro areas using R, ggplot2, and Census ACS data.*


This project uses R Markdown and visualization tools such as ggplot2 to analyze how the proportion of non-citizens living in the United States’ largest metropolitan areas has changed from 2018 to 2023.

The goal of this project is to evaluate whether public and media narratives about rising “illegal immigration” align with actual demographic trends reflected in Census and ACS data. By examining city-level shifts in non-citizen populations, this analysis seeks to provide a data-driven perspective on immigration patterns and their geographic distribution.

##**Methods:**

Data sourced from the American Community Survey (ACS).

Cleaned, joined, and visualized using R, tidyverse, and ggplot2.

Focused on the 100 largest U.S. metro areas, comparing non-citizen shares over time.

##**Key Questions:**

Have non-citizen populations actually increased in major U.S. cities since 2018?

Do data trends reflect or contradict the intensity of recent media narratives around immigration?

How do these patterns vary across different regions or city sizes?

##**Results & Findings:**

The analysis reveals a far more nuanced picture of immigration than what is often portrayed in public discourse or media rhetoric. While non-citizens remain a significant and growing part of the population in many U.S. metro areas, the actual scale of this growth is modest.

Across the 100 largest U.S. metropolitan areas, the average increase in the non-citizen population share from 2018 to 2023 was only +0.19 percentage points, with even the most dramatic local increases remaining below +2 percentage points. This contrasts sharply with the perception of a nationwide surge in “illegal immigration.”

Regional trends provide deeper insight:

Western cities (e.g., in California and Oregon) often saw declines in non-citizen populations, likely linked to high living costs and shifting labor markets.

Southern metro areas, particularly in Florida, experienced moderate growth, reflecting cultural and economic factors such as established Latin American communities and demand for labor in hospitality, construction, and agriculture.

Texas, despite being part of the South, appeared to diverge from this trend, potentially due to stricter immigration enforcement policies.

Overall, these findings exemplify how media narratives can often exaggerate immigration trends and make clear that localized, data-driven policy descisions need to be made, rather than sweeping ideological rhetoric.

##**Technologies:**

R, R Markdown

tidyverse, ggplot2, dplyr

ACS data (2018–2023)

US Geological Survey

simplemaps.com

##**Reproducibility:**
To reproduce this analysis, open `PROJECT.Rmd` in RStudio and ensure the following packages are installed:
`tidyverse`, `ggplot2`, `dplyr`, and `sf`.

Data sources can be accessed through ACS2018.csv, ACS2023.csv, and uscities.csv


##**Below is a sample graph from the project:**
![Percentage Point Change in Non-Citizen Population by City](https://raw.githubusercontent.com/jamessalmon/noncitizen-trends/main/SampleGraph.png)


[View the full HTML report here](https://jamessalmon.github.io/noncitizen-trends/PROJECT.html)

##**My Information**
**Author:** James Salmon  
**Affiliation:** Computational Social Science Student, University of Pittsburgh  
**Date:** April 2025



