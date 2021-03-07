# Kickstarter Analysis
## Overview of Project
The objective of this analysis is to provide a basic idea about the funding amount required at the time of year to conduct a Kickstarter Campaign for theater events and especially for plays. We want to determine an appropriate goal and establish if there is too much or too little funding. We are trying to understand a suitable time of year to get this funding and if timing is a factor for this campaign.
# Analysis and Challenges
## Analysis of Outcomes Based on Launch Date
While performing the analysis on Outcomes Based on Launch Date, the month of May appears to be when successful campaigns are at their peak. The curve picks up rise in trend from the month of April. Based on the chart below the months of December & January seem to be the months when not many projects are launched.
![Theater_Outcomes_Vs_Launch.png](https://github.com/ritwikthakar/kickstarter-analysis/blob/main/Resources/Theater_Outcomes_Vs_Launch.png)
## Analysis of Outcomes Based on Goals
Upon further analysis, it is shown that as the funding increase, the line of the chart decreases. We could say that success is possible in the range of 35,000 to 45,000, however the number of campaigns is significantly less.
![Outcomes_Vs_Goals.png]( https://github.com/ritwikthakar/kickstarter-analysis/blob/main/Resources/Outcomes_Vs_Goals.png)
## Challenges and Difficulties Encountered
One challenge I faced while preparing the data was with the “Countifs” function as this was something which was new to me. I was used to sorting data by applying filters and sorting data. After looking at the hints, I was able to solve for the “Countifs” function.
# Results
## - What are two conclusions you can draw about the Outcomes based on Launch Date?
* The Months of May & June have a higher probability of success rate at 67% and 65% respectively based on empirical data.
* The months of December and January show lower success rates historically.
## - What can you conclude about the Outcomes based on Goals?
•	Majority of the successful projects have received funding in the range of 1,000 and 4,999. Funding over 4,999 has exhibited a sharp decline of 55% in the success rates.


## - What are some limitations of this dataset?
There are no indications that could show a reason for cancelation or failure. We are also missing information about when and how these campaigns advertised and promoted. 
## - What are some other possible tables and/or graphs that we could create?
We could consider the duration of campaigns and try to understand what the appropriate duration. We can also consider looking at performers to see if there is any influence from these categories on the probability of success or failure for a particular Kickstarter.
