# Kickstarting with Excel

## Overview of Project
In this project we will be using Excel charts and pivot tables to analyze data

### Purpose
The purpose of this analysis is to understand how different theater campaigns fare in relation to their launch dates and their funding goals.

## Analysis and Challenges
A Kickstarter dataset with the performance and funding information of different campaigns across various fields and years was provided. To perform the analysis for this report, we reviewed the dataset and added some fields to be able to examine it at a closer level. Two of the key fields that were added include the year of creation and parent category for each campaign. 

### Analysis of Outcomes Based on Launch Date
To summarize the data pertaining to “theater” campaigns based on their launch date, we created a [pivot table](https://support.microsoft.com/en-us/office/create-a-pivottable-to-analyze-worksheet-data-a9a84538-bfe9-40a9-a8e9-f99134456576) showing theater outcomes by the month launched. To visualize this data and be able to find any trends, we charted the data using the “line with markers chart”.  

### Analysis of Outcomes Based on Goals
We also analyzed the outcomes of the campaigns based on their goals. To accomplish this, we used Excel formulas to group “theater-play” goals by ranges and displayed their success, failure, and cancelation rate on a line graph. 

### Challenges and Difficulties Encountered
A possible challenge to this analysis includes verifying the validity of the Kickstarter data provided. In other words, if the provided dataset is not a true representation of how theater campaigns fare, then the results of this analysis may be incorrect.


## Results

At a first glance, there seem to be more successful theater outcomes in May and less successful outcomes in December.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/61717854/151645699-c7e6c527-9363-4d02-96e3-6637f0230b60.PNG)

Given that the number of campaigns is different across months, we should look at the outcomes by percentage:

![rate of success by month](https://user-images.githubusercontent.com/61717854/151645719-1743d86c-3e9f-4508-97c6-c875a3112ead.PNG)

While the success rate is still greater in May and lower in December, the relationship (if any) between success and launch date seems to be very weak. The drop in success that we see in December may be driven by another variable.

Theater/Play outcomes seem to be more successful when they have a goal that is less than $1,000.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/61717854/151645734-116cd214-e4a2-49d6-b5af-4d2ac7d01f98.PNG)


It would be interesting to look at the outcome rates and average goals by month. After taking out an outlier (id 2960) from the Kickstarter data which most likely had a typo (goal stated was 30MM), we can see the following chart. This shows us that the relationship between launch date and success is not very strong. Also, this explains why we saw a drop in success in December (the average goal was significantly higher). In conclusion, success seems to be more related to average goal, and a lower average goal seems to be better for the success of a theater campaign.

![theater outcome % and avg goal](https://user-images.githubusercontent.com/61717854/151645739-9a0ad8d3-7d28-4277-a8df-dc7b9249ce82.PNG)

![theater outcome % and avg goal 2](https://user-images.githubusercontent.com/61717854/151645742-bb48869a-046e-4b86-89ca-cff965bb007c.PNG)


 A limitation for the data is that it does not include the genre of the plays. The genre of the play may be a lurking variable, making us draw incorrect conclusions about the relationship between the goal amount and the success of a theater campaign.


