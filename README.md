# Covid and Tech YouTube Trends

<ins>Analysis:</ins>
Using the youtube_with_covid.csv file found in the data folder, we were able to conduct t-tests for the different vaccination rates

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

The p-values for all tests are very small, less than our alpha of 0.05. Because these values are less than our alpha value, we can conclude that each vaccination rate is statistically significant against the three youtube metrics we used. This means that there is a relationship between views and the fully vaccinated rate, for example. A 1% increase in the vaccination rate is expected to increase the number of views, likes, and comments. In this case, we must reject our null hypothesis because our p-values are less than our alpha at 95% confidence.


Now that we know that the relation is statistically significant, we can conclude the following:

## How did the coronavirus pandemic affect the popularity of tech career videos on youtube? ##

The number of youtube Tech videos is continue raising from 2019 to 2023. We can also see from 2020 to 2022, there is a huge increase of tech video upload. 2020-2022 has the top 3 view counts from 2019-2023. View count from 2020-2021 has the highest increase and the the total number of videos has the highest increase from 2021-2022. The may result from the high view counts in 2021 and the video creators make more tech career videos because it is getting more popular. There is a high percentage in 2021 (~67%) because the COVID vaccination rolled out in December 2020. Then we can continue to see the increase in 2022 which also reaches to the highest vaccination rate. In 2022, vaccines were becoming more accessible, so more people have completed the 2 doses. The view counts are the highest in 2021. In 2020, we experienced shelter in place and layoffs due to COVID. People maybe tended to think about switching career or strengthening skills, so we can see from 2020-2021, there is a sharp increase of the tech video views. In 2021, after the vaccine has rolled out and people started to get vaccinated, we are starting to see the light of ending the pandemic. People may have a eager thought of strengthening their skills to help them get ready after the pandemic ended which may lead to tech videos increasing in popularity that year. In 2022, the view count has a small drop compare to 2021 but the vaccination rate is the highest. Since more people finished the 2 doses, and the society are softly re-opened during that time, people may be able to get back to their original job and career field, so the mindset of switching career may become weaker. Also, people may watch those tech videos in 2021 to get prepared for job market after the pandemic ended. 2022 may be the year that people put in action after they learned from those videos.
From 2021 to 2022, there is a high increase for tech video uploads. Since people are getting vaccinated in 2021 and high view counts in 2021, video creators may create more videos about tech careers due to the increase in popularity in 2021. With the COVID vaccine, it created a hope for getting back to normal. Video creators upload more tech career videos and hoping to provide a help guide for people on their career plan after the pandemic and get more view counts at the same time.

## Which type of tech career increased the most in popularity? (IT, Data Analytics, Software Engineering, etc.) ##

We researched today’s top rated tech positions and compared it to YouTube’s video tile pertaining each tech position. The top tech positions we searched were Web Developer, Software Developer, Data Scientist, Data Analysis, and Business Analyst. In 2019 and 2020, Web Developer was the most supplied YouTube video than another career. Throughout the years, 2020 – 2022 there was an increase in tech YouTube videos. Each tech category had an increase. Also, the same trends found in 2019 – 2020 were found in 2021 – 2022. In 2022 to 2023, there was an increase in tech YouTube video, but the trend slightly shifted. From 2019 to 2022, data scientist was the third leading YouTube video but in 2023 data analysis surpassed data scientist. From 2019 – 2023, Web Developer is the most supplied YouTube video out of the tech field.

## Which channels popularity correlated the most with the vaccination rate of CA? ##

Now that we know how the pandemic affected the tech career genre as a whole and sub-categoriws within this genre, let's break it down by individual channel. 

After comparing the total view count by month for each channel vs the fully vaccinated rate of CA, we found a medium negative correlation for 5 channels (thedevlife, A Life Engineered, PushToProd, Devslopes, TechLead). 
Doing the same for total like count gave us 4 channels with a medium negative correlation (thedevlife, A Life Engineered, PushToProd, Rahul Pandey).
Again doing the same for comment count gave us a strong negative correlation for 1 channel (PushToProd), a medium positive correlation for 1 channel (Thu Vu data analytics), and a medium negative correlation for 1 channel (A Life Engineered).

Of the 50 channels in our dataset, only a few channels popularity indicators had any correlation with the vaccination rates and only 1 had a strong correlation. All but 1 correlation was negative. We cannot say that the COVID-19 pandemic caused the decrease in popularity in these channels but there is a correlation. The channels just decreased in popularity over time and the vaccination rates increased so it could have been a variety of factors that contributed to the decline in these channels.

## Conclusion ##

The COVID-19 pandemic increased the number of tech career focused videos being posted, with the most popular career being Web Developer. There was little to no correlation with the popularity of individual channels. What can be inferred from this is that the tech career video genre became a more popular topic to make videos about but individual channels success was not affected by this trend.

## Citations ##
Help with YouYube API - https://www.youtube.com/watch?v=D56_Cx36oGY&t=683s 00:00 - 13:15
Cell 12, https://stackoverflow.com/questions/30653208/retrieve-video-ids-contained-in-a-playlist-youtube-api-v3
Cell 49, https://stackoverflow.com/questions/71767087/concat-dataframes-using-rows-from-second-dataframe-which-dont-exist-in-first-da
Cell 191, 192, https://stackoverflow.com/questions/68715304/dual-x-axis-in-python-same-data-different-scale
Cell 195, https://stackoverflow.com/questions/44664247/python-dictionary-how-to-get-all-keys-with-specific-values
