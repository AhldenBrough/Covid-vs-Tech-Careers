# Covid and Tech YouTube Trends

<ins>Analysis:</ins>
Using the youtube_with_covid.csv file found it data, we were able to conduct t-tests for the differnt vaccination rates

*Fully Vaccinated Rate

*One Dose Rate

*Up to Date Rate 

against the main metric we use to test video engagement:

*Views

*Likes

*Comments

Once the tests were conducted, they were then combined into a data frame to show all results at once. The p-values for their tests are shown below:

| Test | P-Value |
| --- | --- | 
| Views and Fully Vaccinated | 2.475101e-234 |
| Likes and Fully Vaccinated | 2.031317e-170 |
| Comments and Fully Vaccinated | 1.908052e-232 |
| Views and One Dose | 1.481831e-179 |
| Likes and One Dose | 2.069415e-170 | 
| Comments and One Dose | 3.323470e-232 | 
| Views and Up to Date | 1.474065e-179 |
| Likes and Up to Date | 1.756779e-170 |
| Comments and Up to Date | 2.475101e-234 |

The p-values for all tests are very small, less than our alpha of 0.05. Because these values are less than our alpha value, we can conclude that each vaccination rate is statistically significant against the three youtube metrics we used. This means that there is a relationship between views and the fully vaccinated rate for example. A 1% in the vaccination rate is expected to increase the number of views, likes, and comments. In this case, we must reject out null hypothesis because our p-values are less than our alpha at 95% confidence.
