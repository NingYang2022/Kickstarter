# Kickstarting with Excel

## <font color=#6495ED>Overview of Project</font>
Upcoming playwright Louise, who wants to start a crowd fundraising campaign to help her play *Fever*. Her budget is tight, and she's hesitated about jumping into her first fundraising campaign. She needs help. Through this project, we will use Excel to organize, sort, visualize and analyze the crowd funding data to determine whether there are specific factors that make a campaign successful. Using Excel to analyze the current data will help her gain greater understanding of the campaign, and make her own plan that leads her first one successful.
### <font color=#6495D>Purpose</font>
* To visualize and analyze the campaign outcomes based on their launch dates and funding goals.
* To draw consulions and provide recomendations based on the analyzation.
---
## <font color=#6495ED>Analysis</font>

### <font color=#6495D>Analysis of Outcomes Based on Launch Date</font>
4,113 records are collected in total. Analysis is conducted to find the direct relationship between outcomes (Successful, failed, canceled) and launch date (month) for theater category only. Result indicates successful and failed followed the similar pattern. May, June and July are the top three months. Jan, March, September and December are the four lowest months. Cancelation remains relatively flat throughout the year with October has none. 

![table of Thearter Outcomes by Launch Date](https://github.com/NingYang2022/Kickstarter/blob/main/table%20of%20Thearter%20Outcomes%20by%20Launch%20Date.PNG?raw=true)
![Outcomes Based on Launch Date](https://github.com/NingYang2022/Kickstarter/blob/main/Theater_Outcomes_vs_Launch.PNG?raw=true)


### <font color=#6495D>Analysis of Outcomes Based on Goals</font>
Further analysis is conducted for Plays subcategory to identify the relationship between pre-set goals and outcomes. Result shows successfuly pecentage is higher than failed percentage when goals are set below $15,000, and between $35,000 and $45,000. Goals that are set between $45,000 and $49,000 is 100% failed. Goals that are set less than $1,000 has the highest successful percentage at 76%. Goals that are set between $15,000 to $19,999 has sucessful percentage and failed percentage split evenly at 50%.

![table of Outcomes Based on Goals](https://github.com/NingYang2022/Kickstarter/blob/main/table%20of%20Outcomes%20Based%20on%20Goals.PNG?raw=true)
![ Outcomes Based on Goals](https://github.com/NingYang2022/Kickstarter/blob/main/Outcomes_vs_Goals.PNG?raw=true)

### <font color=#6495D>Challenges and Difficulties Encountered</font>
* For worksheet "Outcomes Based on Goals", While  Using  <font color=#6495ED>COUNTIFS()</font> function to populate the "Number Successful", it's difficult to write the function, I had to be more careful when filtering on the Kickstarter "outcome" column, applying "Goal"clolumn ranges, and "plays" as the criteria.

---
## <font color=#6495ED>Results</font>

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    1. For theater category, fundrasing shall be launched in May and June, which has highest successful outcomes.
    2. For theater category, fundrasing shall be avoid in January, March, September and December, which have lowest successful outcomes.

- What can you conclude about the Outcomes based on Goals?
    1. For Plays subcategory Goals shall be set either below $15,000 or between $35,000 to $45,000, where there are higher possibility for success than failure.

- What are some limitations of this dataset?
    1. Chart "Outcomes Based on Goals" shows that 67% sucessful outcome in the "goal" range between $35,000 and $45,000, which could give us wrong understanding that people would think goal should be set high to make it sucessful, in fact few projects totally happened.
- What are some other possible tables and/or graphs that we could create?
    1. We can create charts of successful counts based on goals to see that there are more good outcomes where goals are set between $1,000 and $5,000, and not for the range between $35,00 and $45,000 where chart "Outcomes Based on Goals" shows confusing results.
    ![Successful_Counts_based_on_Goals](https://github.com/NingYang2022/Kickstarter/blob/main/Successful_Counts_based_on_Goals.PNG?raw=true)
    ![Percent_of Success_based_on_Goals](https://github.com/NingYang2022/Kickstarter/blob/main/Percent_of%20Success_based_on_Goals.PNG?raw=true)
