# Kickstarting with Excel

## Overview of Project

### Purpose

The purpose of this project was to analyze real world Kickstarter data and help a playwright launch a Kickstarter of their own for their new play with a $10K budget. The Kickstarter data contained lots of different types of categories, but for this project the analysis was focused on the performance of Theater & Play Kickstarters. The data contains information about Kickstarters from all around the world, and across lots of different categories including music, technology, and games.  

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

In order to analyze outcomes by launch date, I first had to get a years column created. Converting a unix time stamp is something I hadn't done before - but I found it interesting! 

![photo of Unix conversion] (Users\tbrec\DataAnalysis\Bootcamp\Homework_Repos\Week1_HW_Excel\01-Kickstarter\Resources\Unix_Conversion.png)

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered

Most of the challenge for me came from getting the sumifs set up for the outcome by launch date analysis. It took a bit of work to get it setup, but I eventually got it. I also ran into some issues around edge cases and did not include an 'or equal to' operator in my formulas - so my data was off when I first created my summary graph. 


## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

I would advise not to start a Theater Kickstarter in December - less than 50% of the Theater Kickstarters in December were successful, and all other months were above 50%. The middle of the year (Apr - July) seems to be the best time to launch a Theater kickstarter according to the data. However, the % succesful isn't that much greater in these months. Personally, I would advise against making a launch timining decision solely based on this analysis. I don't think the differences in % succesful would be statistically significant if it were to be tested.


- What can you conclude about the Outcomes based on Goals?

I would advise to stay away from having a Kickstarter goal of over $45,000. The success rate is very low - only 12% of projects with a goal of above $45,000 ended up being successful. Goals below $5,000 have a much higher success rate than other goal ranges - above 70%. While the budget for the new play is $10K, I would advise against trying to fund the entire $10K budget through Kickstarter if the playwright is afraid of the Kickstarter "Failing" and not reaching the full goal amount. 

- What are some limitations of this dataset?

Some of the limitations of this dataset include the fact that location data stops at Country. It might be interesting to only look at Kickstarters in the local area and see if any trends can be found. I.e., Kickstarters in the local community are much more successful when they have a goal below $20K. The most recent data comes from 2017 - given that the world has changed a ton post Covid, I would prefer to analyze more recent data if I'm going to be giving reccomendations. 

- What are some other possible tables and/or graphs that we could create?

One other area that I would reccomend exploring would be average total amount pledged by goal range. I would like to see what Kickstarter goal ranges have the highest average total amount pledged - if the playwright isn't worried about the Kickstarter being labeled a "failure" I would potentially reccomend having a higher goal if a higher goal is correlated with higher average amounts raised. They may not meet the Kickstarter goal, but the total amount of money raised will still be higher. According to the Kickstarter website, creators still receive funds if the Kickstarter doesn't meet their goal.  