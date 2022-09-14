# Happiness-V.S.-Alcohol-Study

<b>Overview:</b> 

A comparison analysis of the 2018 World Bank Report for alcohol consumption and the 2018 report from The World Happiness Report.  

<hr>

<b>Data Sets Used:</b>

-2018 Happiness Report CSV

-2018 Alcohol Consumption Liters/Capita CSV 

-2015 Happiness Report CSV (For the country grouping by region. Omitted in the 2018 Happiness Report CSV)

In order to use the data from all three CSVs, we renamed the column titles for 'Country and region' to the same thing so we can merge all three of them on that one column. Joining them using the default "inner" setting, the program drops all of the countries whose names aren't a match on all of the CSVs. Then, the null values are dropped, the information is sorted in alphabetical order, and the index is reset. The end result is a dataframe with 133 rows and 12 columns.

The data is then used in various graphs for visual inspection.

<hr>

<b>The Various Statistical Analyses Run:</b>

-Liner Regressions

-Pearson Correlation

-Outlier evaluation

-Kruskal-Wallis Test

-Conover-Iman Test

<hr>

<b>The Following Graphs/Plots are Created and Exported:</b>

-Scatter plots comparing the amount of alcohol consumed to the overall happiness score of each country, the rank of each country, and each individual aspect of happiness measured by the World Happiness Report and their corresponding linear regression equations.

-Bar chart that shows the ranking of each country and the amount of alcohol consumed.

-Bar chart that is organized by the average ranking of each region, with the average amount of alcohol consumed by each region.

<hr>

<b>Link To Presentation Slides:</b>

https://docs.google.com/presentation/d/1SV1RPHfspDE0TLBuD3jLpVEQ6RW1D5F1/edit?usp=sharing&ouid=104775578395208017247&rtpof=true&sd=true

<b>Link To Scikit-Posthocs Information and Install:</b>

https://scikit-posthocs.readthedocs.io/en/latest/

<hr>

<b>Contributers:</b>

<b>Daniel Davis:</b>

<p><a href="https://github.com/Dans1451">GitHub</a></p>
<p><a href="https://www.linkedin.com/in/daniel-davies1451/">LinkedIn</a></p>

<b>Diandra McNeill:</b>

<p><a href="https://github.com/dmcneill0711">GitHub</a></p>
<p><a href="https://www.linkedin.com/in/diandra-mcneill-765410233/">LinkedIn</a></p>

<b>Christian Tourteau:</b>

<p><a href="https://github.com/Christ1129">GitHub</a></p>
<p><a href="https://www.linkedin.com/in/christian-tourteau/">LinkedIn</a></p>
