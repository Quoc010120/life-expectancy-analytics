![world-earth-draw](/img/background1.jpg)

# Analysis of Life Expectancy and GDP Data from WHO

## Introduction

In this analysis, I served as a data researcher for the International Headquarter of Empathy And Logic (IHEAL). My goal was to explore the relationship between a country's GDP and its life expectancy, supporting the organization's belief that a nation's wealth influences the life expectancy of its people. The data was sourced from the World Bank and the World Health Organization.

Key Question: Is there a correlation between a country's GDP and its life expectaddress socio-economic inequalities globally.

![cute-little-dog-impersonating-business-person](/img/background2.jpg)

## Data Summary

First i will import library i will need to use in the future for analytics. After that, i import csv file by `read_csv`, then turn dataframe to a pivort table to have a clearly look at some data indicate.
The dataset includes information on GDP and life expectancy for six countries. A brief overview shows:

- **United States**: Highest GDP \(\~\$14 trillion\) but not the highest life expectancy\.
- **Zimbabwe**: Lowest GDP \(\~\$9 billion\) and lowest life expectancy \(mean of 50 years\)\.
- **Germany**: Highest life expectancy with a GDP of \~\$3 trillion\.

![Country-LETC-GDP](/img/country-table.png)

## Analytics

### Life Expectancy Trends (2000-2014)

Base on the `figure1` and table below Zimbabwe experienced the most dramatic rise in life expectancy, increasing by 28%, from around 40 years in 2000 to approximately 60 years by 2014. This notable improvement can be attributed to significant health interventions and recovery from the HIV/AIDS epidemic.

In contrast, other countries saw more gradual increases in life expectancy over the same period. For example:

- Chile and Germany: Both countries maintained consistently high life expectancies, ranging from the mid-70s to the low-80s, with a modest increase of about 2% to 3%.
- China and Mexico: These countries showed steady improvements in life expectancy, growing by around 4% to 5% over the period. China rose from around 70 to 75 years, while Mexico increased from 75 to nearly 77 years.
- United States: Life expectancy in the U.S. increased by approximately 2%, rising from around 76 years in 2000 to about 78 years in 2014.

Overall, while Zimbabwe showed the most rapid growth in life expectancy, other nations experienced more stable and consistent increases during the same period.

![LEABY-across-country](/img/figure1.png)

![LEABY-increase-2000-2014-across-country](/img/table-1.png)

### GPD across nations

Between 2000 and 2014, the GDP of the six nations analyzed in the provided dataset has generally increased, with varying degrees of growth. China exhibited the most remarkable rise, with a staggering 765.3% increase, elevating its GDP from approximately $1.2 trillion to over $10.4 trillion. This substantial growth underscores China's rapid economic expansion during this period.

Chile also showed a significant increase, with a 235.2% rise in GDP, indicating strong economic performance. Zimbabwe, despite starting from a lower base, managed a 137.5% increase, showing recovery and growth, albeit with fluctuations in the earlier years.

Germany and Mexico demonstrated steady but moderate GDP growth, with increases of 99.5% and 89.9%, respectively. These countries maintained a consistent upward trajectory, though less dramatic compared to China or Chile.

The United States, while still showing a healthy increase of 68.9%, had the slowest GDP growth among the six nations. This slower growth reflects the more mature state of its economy during this period.

In summary, all six nations saw their GDP increase over time, with China leading the charge in terms of percentage growth, while the United States had more modest gains.

![GDP-across-country](/img/figure2.png)

![GDP-increase-2000-2014-across-country](/img/table-2.png)

### Correlation between life expectancy and GDP

Base on the figure3 below we can draw some conclusion:

- Positive Correlation: As life expectancy increases, GDP tends to rise as well. The data points cluster in the upper-right quadrant, suggesting that countries with higher life expectancy tend to have stronger economies.
- Socioeconomic Development: The positive correlation implies that improved living conditions, healthcare, and economic prosperity contribute to longer life expectancy. Countries with higher GDP invest more in healthcare infrastructure, education, and social services, leading to better health outcome.
- Policy Implications: Policymakers can use this insight to prioritize investments in healthcare, education, and economic development. Fostering economic growth can positively impact citizens’ well-being and life expectanc

.
In summary, this graph underscores the importance of socioeconomic factors in determining life expectancy.

![GDP-LE-rela](/img/figure3.png)

### GDP Trends Across Six Nations (2000-2014)

The graph displays the GDP trends from 2000 to 2014 for six countries: Chile, China, Germany, Mexico, United States of America, and Zimbabwe. Each country's economic performance is represented by a line graph that shows the GDP growth over the years. Here are some key observations:

#### Variability Across Countries:

- **China** demonstrated the most remarkable growth, with a 765.3% increase in GDP, growing from approximately $1.2 trillion to over $10.4 trillion. This rapid rise underscores China's economic expansion during this period.
- **Chile** also showed significant economic growth, with a 235.2% increase in GDP, indicating a strong economic performance over the years.

- **Zimbabwe**, starting from a lower base, experienced a 137.5% increase in GDP. Despite early fluctuations, Zimbabwe's economy showed substantial recovery and growth by 2014.

- **Germany** and **Mexico** displayed steady but moderate GDP growth, with increases of 99.5% and 89.9%, respectively. Their economies maintained a consistent upward trend, albeit less dramatic than China or Chile.

- **The United States** had the slowest GDP growth among the six nations, with a 68.9% increase. This reflects the more mature and stable state of its economy during this period.

#### Economic Growth and Stability:

- **China**'s and **Chile**'s rapid GDP growth are indicative of their dynamic economic environments and development policies during this period.
- **Zimbabwe**'s fluctuations in GDP highlight the challenges it faced but also its resilience and eventual economic recovery.

- **Germany**, **Mexico**, and **The United States** showed more stable growth, with fewer fluctuations, indicating economic maturity and stability.

#### Policy Implications:

- These GDP trends provide valuable insights for policymakers and economists to analyze economic growth, stability, and areas needing further development. China's rapid growth and Zimbabwe's recovery are of particular interest for further analysis.

This analysis helps in understanding how different countries have fared economically over time and can guide decisions related to economic policies and investments.

![LEBY-2000-2014](/img/figure4.png)
