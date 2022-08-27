# surfs_up
Climate analysis for Surf shop on the island of Oahu ( SQLite and Python) 

### Overview
  - Entreprenuers when beginning a new investment venture often take into account many of the market variables that could influence the success of the venture. For this project an investor wants to determine whether a new venture, Surf'n'Shake, on the Island of Oahu would be feasible based on weather conditions, notably precipitation. 

## Resources
  - Python: Numpy, Pandas; MatPlotlib; SQLite: SQLalchemy; Jupyter Notebook, VS Code; Flask applications; Statistical Analysis
### Results
  - Based on the "Hawaii.sqlite" weather data file we were able to conduct analyzation of the weatger data of multiple stations across the Island of Oahu. We were able to chart precipitation and temperature over time across the various stations to determine a viable location based on those variables for a succesful business venture. After we were able to gather a generalized view, the investor was curious about how the temperature changed over the course of a year to determine if it would make sense for the shop to be open year round. Therefore we isolated the temperatures for June and December and gather a statistical summary of the whole month.
  - June vs December
  - ![June Temp Summary](https://github.com/MichaelG-B/surfs_up/blob/dd51bff569e8533c8c530caa5ef9ef2aa05c7837/June%20Temp%20Summary.png)
  - ![December Temp Summary](https://github.com/MichaelG-B/surfs_up/blob/dd51bff569e8533c8c530caa5ef9ef2aa05c7837/December%20Temp%20Summary.png)
  - One of the most prominent differences between June and December was the avg temperature, 74 in June vs 71 in December, showing that there is honestly little difference in temperature betweeen the two months on average.
  - The largest difference between the two months was in the minimum temperature, being 64 in June vs 56 in December, highlighting that there is indeed a possibility of less than ideal ice cream consumption conditions for the month of December.
  - Another notable difference in temperature between the two months is in the range most temps fall in, for June they tend to be between 73-77, whereas in December they tend to be between 69-74, which shows a similar net range of around 4.5 degrees. Outliers for June are less than 85 but higher than 64, whereass for December outliers are lower than 83 but higher than 56, a markedly wider differnece between the two outlier ranges. This is noteworthy since I would predict that there will be a higher possibilty of more days of lower sales in December than June, but this does not mean that this will occur just that it is more likely, therefore should be acknowledged in the cost dynamics of the shop if it is to be open during December.
### Summary
  - In summary the results of our weather analyzation for the viability of "Surf'n'Shop" shows that the weather of Oahu is realtively stable over the course of a year with little diversity, prompting essentially a two season climate, Summer and Winter. The average amount of precipitation for a year is around .25 inches, offering a rather low possibility of being "rained out" per say. The average temperature over the course of a year tends to be between 70-76 degrees, offering a fairly stable warm environment. Based on the current analyizations, there seems to be good hope for having the shop open year around, however further analysis would provide more firm answers.
## Additional Query's
  - I chose to add analyzation summaries for March and September as two additional queries in the hopes of gathering a more nuanced picture of the weather of Oahu over the course of a year.
  - ![March Temp/Precip Summary](https://github.com/MichaelG-B/surfs_up/blob/dd51bff569e8533c8c530caa5ef9ef2aa05c7837/March%20Temp:Precip%20Summary.png)
  - ![June Temp/Precip Summary](https://github.com/MichaelG-B/surfs_up/blob/dd51bff569e8533c8c530caa5ef9ef2aa05c7837/June%20Temp:Precip%20Summary.png)
  - ![September Temp/Precip Summary](https://github.com/MichaelG-B/surfs_up/blob/0b9d0fbb6e812f4518039a76a4125ad0129780e0/September%20Temp:Precip%20Summary.png)
  - ![December Temp/Precip Summary](https://github.com/MichaelG-B/surfs_up/blob/dd51bff569e8533c8c530caa5ef9ef2aa05c7837/December%20Temp:Precip%20Summary.png)
