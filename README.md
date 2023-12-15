# Oakville-housing-analysis
-------------------

## Description

The project talks about:

1. Comparative housing prices for Oakville to surrounding regions (Burlington, Milton, Vaughan, Oshawa)
2. Factors in the regions such as population, income, school districts, amenities.
3. Comparing sale changes and growth in all regions, and how they compare to Oakville.

The analysis we are going to do is:
1. Analyzing sale prices of housing within various regions comparable to Oakville
2. Analyzing factors such as popularity of the city, income, schools, amentities, and other variables that may affect housing prices
3. Create visualizations that help demonstrate factors that may be a stronger influence than others of housing prices in cities within the GTA.

The questions we are going to answer are:
1. What unique variables has set Oakville apart from the other cities nearby if at all?
2. What sort of factors increase or decrease the value of housing within the GTA? 
3. What are the different economic states of each city based on household income, unemployment rate and housing cost ?
4. Which city display the greatest growth (population, infrastructure, economic) ?
5. Which cities offer the greatest housing opportunities?
6. Which city/cities is/are more appealing for families?

## Members of the group
1. Maisie DeGraaf ([@MaisieDeGraaf](https://github.com/MaisieDeGraaf))
2. Jaylene Hughes ([@jhyooz](https://github.com/jhyooz))
3. Pooja Niranjan ([@Pooja14n](https://github.com/Pooja14n))
4. Robert Skrepnek ([@RSkrep](https://github.com/RSkrep))
5. Peggy Tadi ([@peggz19](https://github.com/peggz19))

   
## Work breakdown structure
1. Maisie DeGraaf - Burlington Data Frame
2. Jaylene Hughes - Vaughan Data Frame
3. Pooja Niranjan - Oakville Data Frame
4. Robert Skrepnek - Milton Data Frame
5. Peggy Tadi - Oshawa Data Frame

## Datasets used:
1. Census Profile, 2016 Census
https://www12.statcan.gc.ca/census-recensement/2016/dp-pd/prof/index.cfm?Lang=E
Statistics Canada , Feb. 8, 2017
2. Census Profile, 2021 Census
https://www12.statcan.gc.ca/census-recensement/2021/dp-pd/prof/index.cfm?Lang=E
Statistics Canada , Feb. 9, 2022
3. Housing Starts: by Dwelling Type
https://www.cmhc-schl.gc.ca/professionals/housing-markets-data-and-research/housing-data/data-tables/housing-market-data/housing-starts-dwelling-type
CMHC, April 6,2023
4. 2021-2022 Academic Year
https://data.ontario.ca/dataset/number-of-elementary-and-secondary-schools-by-school-boardschool-authority/resource/220a6820-0084-46ee-9747-f295f58301f2
Data Ontario, Fe. 24,2023
5. Oakville Property Tax 2023
https://wowa.ca/taxes/oakville-property-tax
WOWA
(done for each city)
6. Housing Market Portal
https://www03.cmhc-schl.gc.ca/hmip-pimh/en/TableMapChart/Table?TableId=2.1.31.2&GeographyId=35&GeographyTypeId=2&DisplayAs=Table&GeograghyName=Ontario#TableMapChart/061008/5/Burlington
CMHC, April 5, 2022
7. Regional Housing Reports December 2016 and 2021
https://durhamrealestate.org/durham-reports.cfm
Central Lake Association of Realtors, 2016 and 2021
8. Places API Playground
https://apidocs.geoapify.com/playground/places/
GeoApify Docs
9. Oshawa and Vaughan Average Sale Price and Median Sale Price
https://trreb.ca/index.php/market-news/market-stats
Toronto Real Estate Board
10. Oakville, Burlington and Milton Average Sale Price and Median Sale Price
https://www.rahb.ca/market-stats/
Realtors of Hamilton-Burlington Board
11. Oshawa, Whitby, Clarington and GTA Property Tax Rates 2016
https://johnowen.realtor/blog.html/oshawa-whitby-clarington-and-gta-property-tax-rates-2016-4393669
John Owen, May 25, 2016

## Code Snippits
![image](https://github.com/MaisieDeGraaf/oakville-housing-analysis/assets/144713762/bd556054-22a7-4172-8568-dff1b3b5c14c)
![image](https://github.com/MaisieDeGraaf/oakville-housing-analysis/assets/144713762/f7150cf1-1f5a-40f6-a7a3-4ab1525346c1)
![image](https://github.com/MaisieDeGraaf/oakville-housing-analysis/assets/144713762/661dc7dc-9769-45b3-9c45-78951eb05ae6)

## Analysis
1. From analysis, some final summaries we can see is that Oakville has a couple factors that separates them from the other 4 towns analysed in this report. Despite having a mid to smaller population compared to the rest, Oakville has significantly more leisure spaces than comparable towns and cities. Oakville is the only town that in 2016 to 2021 has not significantly increased the amount of new builds created each year. This is in despite of their population growing at a rate comparable to other towns and cities. Lastly, Oakville is the only town that has more private schools than it does Catholic schools.
2. Analysis: all cities have had a growth in population over the course of 5 years with Burlington having both the lowest total increase and lowest percent increase. Milton has the greatest total increase as well as the greatest percent increase.
Analysis For all cities the total household income increased with Vaughan having the greatest increase in household income With regards to Rent only one city's rent decreased and that would be for Milton. Both Oshawa and Vaughan had major increases to their average rent with Oshawa having the greatest percent increase. even after these increases Oakville remains having the greatest total rent for both analyzed years. Milton has the greatest Household income as of 2021 beating the previous holder of Burlington.
3. Unemployment
Unemployment in all 5 cities drastically increased from 2016 to 2021 most likely due to the pandemic however there is a steady increase among all 5 cities of about 5%.
Leisure:
Oakville has the most leisure spaces while Milton has the least. Vaughan, Burlington and Oshawa have a similar amount of spaces.
4. Analysis of the Estimated House Value and Average Sale Price for the 5 cities considered was carried out for the year 2016 and 2021 and it is seen from the graph that mostly houses sold at higher prices than what they are estimated, except for Vaughan in 2016 where it is the other way. Oakville has the highest Estimated House Value and Average Sale price when compared to the other cities considered. Also, Oakville has a higher difference between the Estimated House Value and Average Sale price of the houses.
5. Schools : Vaughan is the city with the most schools, having a total of 133. This result could be correlated with the population number. With regards to Oakville, the city comes second, with a total number of 99 schools.
Housing tenure : Whether we look at the total number of owned houses or the total number of rented houses, each city displays a growth between 2016 and 2021. However, Vaughan is the city where owned houses are prioratized, opposite to Oshawa who's dominating in the rental market among all of them.
Pie chart : The pie charts helps showing the differences of the rental and property market amoung all cities. We are able to see that Vaughan has more owned houses, Oshawa has more rented houses and Oakville seem to stay constant
Scatter : This plot helps showing the correlation between population and home tenure. The more the population, the more the owned houses. People see to draw more towards this preference.
6. Ratio of leisure to population:
Burlington - 663 people per leisure space
Oakville - 499 people per leisure space
Vaughan - 1287 people per leisure space
Milton - 568 people per leisure space
Oshawa - 493 people per leisure space

## Limitations
1. Size of sample
2. Reliability of data
3. Available data
4. Data only since 2016
5. Incomplete 2023 data

