# World Happiness Report from 2008 and 2017

## About the project
In this project, I will use R and apply exploratory data analysis techniques to explore relationships in one variable to multiple variables and to explore a selected data set for distributions, outliers, and anomalies.

## Introduction
The World Happiness Report is a landmark survey of the state of global happiness. The World Happiness Report 2018, ranks 156 countries by their happiness levels. It is done by a group of independent experts using the data provided by the yearly Gallup World Poll. The happiness index is created by many major areas. I Select these majors in my analysis to study the effect of it in the happiness score.

Factor | Type | Description
------ | ---- | -----------
Country| String | Name of the Country.
Score | Float | National AVG response to the questions: “Please imagine a ladder, with the worst possible life as a 0 and the best possible life as a 10. On which step of the ladder would you say you personally feel you stand at this time?”. This measure is also known as the Candrill Life Ladder.
GDP per Capita| Float | Natural log of GDP per Capita GDP : the total value of all the goods and services produced by a country in a particular year, divided by the number of people living there. [Reference](https://dictionary.cambridge.org/dictionary/english/gdp-per-capita)
Social Support | Float | National AVG of the responses to the GWP question “If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?”
Healthy Life Expectancy |Float| Life Expectancy AVG based on data by the WHO and the WDI Life Expectancy : The average number of years that a person can expect to live in “full health” by taking into account years lived in less than full health due to disease and/or injury.[Reference](http://www.who.int/healthinfo/statistics/indhale/en/)
Positive Affect |Float| AVG of three positive affect measures in GWP: happiness, laugh and enjoyment.
Negative Affect |Float| AVG of three negative affect measures in GWP: worry, sadness and anger.
Continent |String| Continent of Country.

## Project Questions
    Q1) How is the performance of the world happiness score over the years?
    Q2) What are the factors affect the happiness Score?
    Q3) To what extend effect these factors on the happiness Score?
    Q4) How is the performance of happiness score in world continents over the years?
    Q5) How’s the distribution of the most factor effect on happiness score over the world continents?


## Helpful links
http://www.sthda.com/english/wiki/ggcorrplot-visualization-of-a-correlation-matrix-using-ggplot2 
http://www.sthda.com/english/wiki/ggplot2-axis-ticks-a-guide-to-customize-tick-marks-and-labels 
http://www.sthda.com/english/articles/32-r-graphics-essentials/128-plot-time-series-data-using-ggplot/ 
http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html
