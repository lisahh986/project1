This is our Life Expectancy Data Analytics Project!

We set out to answer 6 key questions regarding Life Expectancy.

1. How is life expectancy in a country affected by Alcohol Consumption, GDP, Population, Vaccination DTP, Vaccination Measles and, Health Spending?

2. Do countries with higher GDPs have higher life expectancies? 

3. Should a country having a lower life expectancy value(<65) increase its 
healthcare expenditure in order to improve its average lifespan? 

4. Does Life Expectancy have a positive or negative relationship with 
drinking alcohol?

5. Do densely populated countries tend to have lower life expectancy?

6. What is the impact of Immunization coverage has on Life Expectancy?

-------------------------
We combined data from the The Organisation for Economic Co-operation and Development (OECD) for use in our analysis.
you can find these data at:

Life Expectancy: https://data.oecd.org/healthstat/life-expectancy-at-birth.htm,

Alcohol Consumption: https://data.oecd.org/healthrisk/alcohol-consumption.htm, 

GDP: https://data.oecd.org/gdp/gross-domestic-product-gdp.htm, 

Population: https://data.oecd.org/pop/population.htm, 

Youth Vaccination: https://data.oecd.org/healthcare/child-vaccination-rates.htm, 

Health Spending: https://data.oecd.org/healthres/health-spending.htm

-------------------------

Do countries with higher GDPs have higher life expectancies? 

Stats- Correlation: 62%; Max: 117794; Min: 6998; Median: 40648; Mean: 42688
Based on our data it appears that a higher gdp is positively correlated with a higher life expectancy

![Life Expectancy Vs GDP Chart](images/LEvGDP.png)

Should a country having a lower life expectancy value(<65) increase its healthcare expenditure in order to improve its average lifespan?

Stats- Correlation: 62%; Max: 11055; Min: 222; Median: 3247; Mean: 3505

In general more spending on healthcare has a net positive affect. Our data suggests that countries with a low life expectancies tend to benefit more from an increase in healthcare spending.

![Life Expectancy Vs Health Spending Chart](images/LEvHS.png)

Does Life Expectancy have a positive or negative relationship with 
drinking alcohol?

Stats- Correlation: 15%; Max: 11.8; Min: 1.4; Median: 8.8; Mean: 8.27

Our data indicates a slight positive correlation between alcohol sales and life expectancy.

![Life Expectancy Vs Alcohol Sales Chart](images/LEvAlc.png)
Do densely populated countries tend to have lower life expectancy?

![Life Expectancy Vs Population Chart](images/LEvPop.png)

What is the impact of Immunization coverage has on Life Expectancy?
Stats- Correlation: 62%; Max: 99.9; Min: 78.5; Median: 95; Mean: 94.0

![Life Expectancy Vs Vaccination Chart](images/vax.png)

























LE
The lower quartile is: 77.1
The upper quartile is: 82.51666666666667
The interquartile range is: 5.416666666666671
The the median is: 81.23333333333333


GDP
The lower quartile is: 29890.427142500004
The upper quartile is: 54759.71845683333
The interquartile range is: 24869.291314333328
The the median is: 40648.208082000005
Mean of GDP for countries with life expectancy below 81: 27922.21303260527
Mean of GDP for countries with life expectancy over 81: 54377.42584991667
Ttest_indResult(statistic=-5.49767715637582, pvalue=2.3139374963364098e-06)
The correlation between GDP and the life expectancy is 0.615072938805191.


HS
The lower quartile is: 2060.7546666666667
The upper quartile is: 5233.8025
The interquartile range is: 3173.047833333333
The the median is: 3247.049333333334
Mean of HEALTH SPENDING for countries with life expectancy below 81: 2007.0453771929824
Mean of HEALTH SPENDING for countries with life expectancy over 81: 4690.970326388889
Ttest_indResult(statistic=-4.426987638050461, pvalue=0.00015755976301420576)
The correlation between HEALTH SPENDING and the life expectancy is 0.6193802064853304.

Alc
The lower quartile is: 6.85
The upper quartile is: 10.516666666666666
The interquartile range is: 3.666666666666666
The the median is: 8.766666666666667
Mean of ALCOHOL for countries with life expectancy below 81: 7.665789473684209
Mean of ALCOHOL for countries with life expectancy over 81: 8.758333333333333
Ttest_indResult(statistic=-1.2503143560575949, pvalue=0.22180102102107158)
The correlation between ALCOHOL and the life expectancy is 0.15481183724191316.
![Alt text](images/aLE.png)


Vax
The correlation between VACCINATION DTP and the life expectancy is 0.42159274691845483.
The correlation between VACCINATION MEASLES and the life expectancy is 0.34152186579128924.

Pop
Mean of POPULATION for countries with life expectancy below 81: 207.17493099686598
Mean of POPULATION for countries with life expectancy over 81: 27.312308805555556
Ttest_indResult(statistic=1.8269935450736512, pvalue=0.08417594211506635)








SUMMARY
The correlation between HEALTH SPENDING and the life expectancy is 0.6193802064853304.
The correlation between GDP and the life expectancy is 0.615072938805191.
The correlation between VACCINATION DTP and the life expectancy is 0.42159274691845483.
The correlation between VACCINATION MEASLES and the life expectancy is 0.34152186579128924.
The correlation between ALCOHOL and the life expectancy is 0.15481183724191316.
========================
Readme 10
explain pictures 5
analysis and conclusion 20
summarize major findings 5



