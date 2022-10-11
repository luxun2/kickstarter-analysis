# kickstarter-analysis
Performing analysis on kickstarter trends

# Kickstarting with Excel

## Overview of Project
This project is to analyze how different factors and facets of a project can affect it's success. We take a large amount of data from a pipeline and organize that information to synthesize insights into a various kickstarters.

### Purpose
The purpose here is to help our client Louise successful in her own kickstarter fundraising goals. She is interested in how other campaigns performed in relation to two key metrics, their launch dates and their funding goals. We can filter this data for our data set and visualize how these two categories helped shape their outcomes. 

## Analysis and Challenges


### Analysis of Outcomes Based on Launch Date
We performed our analysis for the launch dates first. We created a pivot table in excel and filtered the table based on categories, years, and outcomes. There is a focus on the theatre category since that is the kickstarter Louise is intending to start. A line chart was created on this pivot table and named "Theater_Outcomes_vs_Launch.png" as shown here. 
![This is an image](https://imgur.com/a/CLffd63)


### Analysis of Outcomes Based on Goals
Next we compiled the data of the outcomes based on goal size using various COUNTIF() statements. An example of code can be viewed here. ```=COUNTIFS(Kickstarter!D:D, ">=10000",Kickstarter!D:D, "<14999", Kickstarter!F:F, "successful", Kickstarter!N:N, "theater/plays")``` Another line chart was made of this data as shown here in this image. ![This is an image](https://imgur.com/a/haGFbrf)

### Challenges and Difficulties Encountered
The largest challenges here is understanding how to seperate the data using complex countif statements and how what chart to use to properly convey the data. There we some difficulties in understanding the Github markup langauge but this is solved by reading the documentation. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
One conclusion we can observe here is the most successful kickstarters began in May. Another one is that the failures started to spike in October while successes began to trough in December, leading us to beleive that most theater kickstarters would be preferable in the summer than in the winter. 

- What can you conclude about the Outcomes based on Goals?
In our Goals analysis we can see that failures spike when the goals get too high, specifically around the $45000 to $49999 range. It would make sense that most of the successes are gained when the goals are small and less than $1000, meaning a smaller budget production would be best for Louise.

- What are some limitations of this dataset?
Some limitations of the dataset is that we might not have all categories that we'd like to help Louise to succeed. For example we could want any information on expenses demanded by the kickstarter, and some measurement of how many people were involved on the team would be interesting to know as well. We are limited by it's possible accuracy and perhaps even it's overall size. We can see that there is some standard deviations and outliers in all data sets that much be considered that can throw off our results. 


- What are some other possible tables and/or graphs that we could create?
We can create some bar charts to better compare different categories based on average donations or percent funded. We can create more pivot tables to focus how the other categories fared in terms of goals or start date. 
