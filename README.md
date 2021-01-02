# An Analysis of Kickstarter campaigns-
This is data analysis of kickstarter campaigns to study and reveal insider trends

## Overview of Project
This project is about analysis of crowdfunding projects and to know inside trends of these compaigns; such as goals, success rate and funds raised. 

### Purpose
Louise’s is managing a play for  fundraising purposes and she wants to know detilas of previously launched campaigns. 
She wants to know relationship between priorly launched campaign's dates, funding goals and net fund raised.  This analysis will help her setting realistic expectations about her fundraising compaign.

## Analysis and Challenges
It was not very tough, though I have to do some effort to reach the final outcome. 

### Analysis of Outcomes Based on Launch Date
As per Figure ![Theater_Outcomes_vs_Launch](https://github.com/FatimaJHussain/kickstarter-analysis-/blob/main/resources.zip/Theater_Outcomes_vs_Launch.png), number of successful events start picking up the pace from March. Most successful events were in month of May  and gradually decrease till December, where we can see, maximum number of failed events.

### Analysis of Outcomes Based on Goals
As per Figure: ![Outcomes_vs_Goals](https://github.com/FatimaJHussain/kickstarter-analysis-/blob/main/resources.zip/Outcomes_vs_Goals.png), when goal amount is less , most of the compaigns are successful. However, as the goal target is increased, number of successful compaigns decreases. Moreover, none of the compaign was cancelled, this shows that people are interested in attending these compaign events.  Also, there is a sudden rise in successful compaigns in the goal range of 30,000-40,000.

### Challenges and Difficulties Encountered
YEAR () function was introduced, but final pivot table had rows distribution on months. Thinking more into it, I figured out MONTH() in excel and was able to get the desired pivot table. 

## Results
1) What are two conclusions you can draw about the Outcomes based on Launch Date?
 * March till May is the time when compaigns pick up successfully.
 * December is the christmas time and people are busy with family and friends and compaigns are not successful
2) What can you conclude about the Outcomes based on Goals?
* Goal range of 1000-5000 is an moderate achiveable goal and most of the compaigns are successful. 
* Goal of 30000-50000 is also pretty successful and most probably corporate sector is involved in this fund raising.

3) What are some limitations of this dataset?
* Data set seems okay for me as it helped me to achive the desired goals.
4) What are some other possible tables and/or graphs that we could create?
* There is a strong relationship of success with description of compaign. Therefore, graph between blurb and goals / successful compaign is important.
* Name or title of the compaign has also stronhg effect on people, graph between name and successful compaign is also good to explore. 
* Graphs on the basis of successful compaigns in different countries in different months can also show some interesting trends. 
* Graph on the basis of subcategory and different cities is also interesting.
