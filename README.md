# Kickstarter Analysis
This report is an analysis into Kickstarter campaigns, our client Louise wants to know how different campaigns performed in relation to their **launch dates and their funding goals**.

We have collected a diverse dataset which contains information on multiple Kickstarter campaigns across various categories and countries. This report will get into further details of our findings.

## Overview of Project
Louis is mainly interested in campaigns that are funding the theater category, specifically in these two areas-
* How the launch date relates to a campaigns outcome?
* How the funding goal relates to a campaigns outcome?

### Purpose
The main purpose of this report is to analyze the dataset and answer the two questions mentioned above. This will help Louise make an informed decision as to ***when she should launch her campaign***. As well as ***what should be a realistic funding goal***. 

## Analysis and Challenges
Lets take a closer look at the analysis and our findings.

### Analysis of Outcomes Based on Launch Date

Our dataset is very diverse and includes several categories like games, technology and many others. But for our report we filtered the data and narrowed it down to what is relevant to our client.
* Only selected the theater category
* Divided the outcomes into Successful, Failed and Canceled
* Grouped the data according to the month, so its easier to visualize (The data is taken from 2009 to 2017)
* Plotted a line chart to better communicate our findings

![Report Theater kaunch date](https://user-images.githubusercontent.com/93144225/140406578-4f6dbe86-8854-427f-86dd-4a5addb19f7c.png)

#### Findings
We can conclude the following things-
* The month of May has the highest rate of successful campaigns and as such is a good month for Louise to start hers.
* The month of December has the least number of successful campaigns and as such is better to avoid.
* When it comes to Theater campaigns, they are more likely to succeed then to fail. As the number of failed outcomes is much lower than successful ones.

### Analysis of Outcomes Based on Goals

This section of the report looks at how funding goals relate to the outcome of campaigns and will help to set a realistic funding goal.

First the data was organized-
* Group the data according to funding goal ranges. For example, the number of campaigns that had a goal of $1000 to $4999 or $5000 to $9999, etc.
* Furthermore, counting the number of **Successful, Failed and Canceled** campaigns (In their respective funding ranges).
* Counting the total number of campaigns in their funding ranges.
* Extracting a percentage value using the above organized data. Telling us what **percentage of campaigns were successful, failed or canceled** in their respective funding ranges.
* Plotted a line chart to better communicate our findings

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/93144225/140429306-684be928-010c-4f6b-9e7c-99aa418bae5c.png)

#### Findings
We can conclude the following things-
* From the graph we can see that if the goal is under a $1000, it has the highest rate of success.
* When the goal is from $1000 to $4999, it has very high success rate. We can conclude that this range provides a good balance between the success rate and funding goal.

### Challenges and Difficulties Encountered

Cleaning up the data and combing through it was a challenge, a lot of the dates were in the UNIX format. Those had to be converted to a readable format, using converter. Extra columns (Years, Percentage funded, etc) had to be added to make some of the graph’s work. Color coding some of the columns made the data easier to read.

#### Limitations of the dataset

One big limitation specially while finding the “Theater outcome based on launch date”, was that all the months have different number of campaigns. Some months have a lower number of successful campaigns, this can mean that the total campaigns that month is less than other months.

If all the months had the same total number of campaigns, the comparision would be more accurate.

### Additional Recommendations

For the “theater outcome based on launch date” graph, we can make a table with percentage values. This will show us the total number of campaigns, the successful percentage, the failed percentage and the canceled percentage.

We can use this data to make a **stacked column graph**. This will show us a different perspective for this dataset. 

