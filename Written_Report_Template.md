# Kickstarting with Excel

## Overview of Project

The project is intended to provide Louise information about theater productions derived from plays that had funding using a kickstarter campaign. 

### Purpose

Louise wants to kickstart a successful theater kickstarter. The data provided from the spreadsheet of successful kickstarters from the past will provide insight to the type of production Louise will kickstart based off of the launch date and funding goal amounts.


## Analysis and Challenges


### Analysis of Outcomes Based on Goals
**Analysis of Outcomes and Goals**
- What can you conclude about the Outcomes based on Goals?

![Refer to Outcomes_vs_Goals.png.](resources\Outcomes_vs_Goals.png "Outcomes vs Goals")


    The data shows that the lower the monetary goal, a higher success rate is observed. The success rate is almost the complete inverse of the failure rate based on the target goal.

### Analysis of Outcomes Based on Launch Date
**Analysis of Theater Outcomes and Launch Date** 
*What are two conclusions you can draw about the Outcomes based on Launch Date?*

![Refer to Theater_Outcomes_vs_Launch_Date.png.](resources\Theater_Outcomes_vs_Launch_Date.png "Theater Outcomes vs Launch Date")

    Theater kickstarters observe the highest success rate in May, worldwide. Success rate of theaters kickstarters drop at a steady pace on an average of %13 per month after May. 

### Challenges and Difficulties Encountered
**Possible Challenges**
*What are some limitations of this dataset?*


    The information provided does not include a specific geographical location, thus not taking into account the cultural aspect of the success of the play Louise wants to create. For example, the USA has a the highest peak of success on May, but in Canada, the highest peak of success is in March.

    One limitation I would consider is the theme of the play. This can be inferred from the "blurb" column, but it is prone to misinterpretation. 

    

## Results
**What can we infer from the data?**


The highest chance of success a theater kickstarter has is within the month of May, with a budget ranging from less than 1000 to 1000 to 4999. The success rate is estimated to be %75.33, which is calculated as follows: the average of Outcomes Based on Goal "Less than 1000" and "1000 to 4999", multiplied by Theater Outcomes by Launch Date "May".

*Theater Outcomes by Launch Date*
    The lowest chance of success happens in December, where there are just as many theater kickstarter that failed as there were successes. The greatest chance of success for a theater kickstarter would be at the time of May. 

*Outcomes Based On Goal*
    Theater kickstarters with lower funding goals had a higher success chance than the inverse. 

*What are some other possible tables and/or graphs that we could create?*
    Another questions that we can possibly answer is "Which play was the most popular?" This can be answered by using the name, blurb, and backers column on the Main sheet, and create a new pivot table filtering by parent category, sub-category, outcome, and goal. This way we can narrow down on the successful theater kickstarters, and the goal amount associated with it. Adding in the blurb in the rows could provide context to the type of play produced.





