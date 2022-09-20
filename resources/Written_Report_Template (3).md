# Kickstarting with Excel

## Overview of Project

### Purpose
This project checks diffrent fundraising campaigns performance based on their launch dates and outcomes based on goals
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
A pivot table was used based on the Parent category and years columns. within the data set, the Parent category within the table was anlysed. A dotted line chart from the pivot was put in place to show the result and visualize the correlation that exists between outcomes and launch months. The Year () function used to get data from date created conversion and place it in the new column, Years.  furthermore, we filtered Parent category to analyse the theathre category. With line chart created shows us the numbers of successful, failed, or canceled projects by month. The chart also demostrate how each month is impacted to increasing funding or not. Visualizing the chart, the moth of May was our best Month. however, the same month of May, June, July, and August were also horrible months becuase the number of failed increased. 

### Analysis of Outcomes Based on Goals
we have visualized another line chart of percentage of successful, failed, and canceled plays. 

on the spreadsheet, we created 7 columns: 

.Goal
.Number Successful
.Number Failed
.Total Projects
.Precentage Successful
.Percentage Failed
.Percentage Cancelled

we grouped those columns following dollars amount ranges with Goals columns:

.Less than 1,000
.1,000 to 4,999
.5,000 to 9,999
.10000 to 14,999
.15,000 to 19,999
.20,000 to 24,999
.30,000 to 34,999
.35,000 to 39,999
.40,000 to 44,999
.45,000 to 49,999
.Greater than 50,000

we populated the number of successful, failed, and canceled projects to count and collect the outcome and goals of plays with subcategory data set. For instance, when using the function COUNTIFS() we were able to get 141 number of successful, 45 number of failed and 0 number canceled. =COUNTIFS(KickStarter!$D:D, "<1000", KickStarter!$F:F, "=successful", KickStarter!$R:R, "=plays"); =COUNTIFS(KickStarter!$D:E, "<1000", KickStarter!$F:G, "=Failed", KickStarter!$R:S, "=plays"); =COUNTIFS(KickStarter!$D:F, "<1000", KickStarter!$F:H, "=Canceled", KickStarter!$R:T, "=plays"). we performed a sum () function to give us the total number of Project of number of successful, failed and canceled. at the end, we were able to determine the percentage of number of successful, failed and cnaceled projects. to visualize all of this, a line chart was created to show the relationship that exists between the goal amount range on the X-axis and the % of successful, failed, and canceled projects on the Y axis. 

### Challenges and Difficulties Encountered
From my own viewpoint, I can speculate that the budget range of 45,000 to 49,999 had zero successful Projects. one limitation of the data also can be the number of projects. may be the info was not captured on this data set and we may not have enough data set to work wiith. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

.Month of May was the best month. howvwer, May, June, and October had the same number of failed campaigns. 

. there is a relationship between the goal amount and the campang's success or failure rate.
The rate of the successful projects will decrease as funding goal amount increases. I'm only specualting that a marketing camapain can bring in more demand and may be gather more interest. not sure if we can see it here because of data limitations



- What can you conclude about the Outcomes based on Goals?

WE can conclude that theres is a relationship between the goal amount and the camapain's success failure rate. we see that if the rate of successful projects will decrease as the funding goal amount increases. the reasoning behind this may be that our data set limits us to speculate. however, a marketing campaign can help raise more money and draw interest of certain groups that the we would not reach otherwise. 

- What are some limitations of this dataset?

a limitation of personal data from people who actually contibute to these campaings. we need to include that aspect of data to know who actually contibute and we can target their family member to increase revenue. it will be very interesting to analyse how much each induvual donated.

- What are some other possible tables and/or graphs that we could create?

Markerting, gender, age, and social status. we could add a line chart based on the average donation. 
