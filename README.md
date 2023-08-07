Google Analytics Capstone Project - Bellabeat

1. Ask phase

Questions to be answered:
- What are some trends in smart device usage?
- How could these trends apply to Bellabeat customers?
- How could these trends help influence Bellabeat marketing strategy?

2. Prepare phase

In order not to damage the original datasets (CVS files), I downloaded them to my computer for further analysis. After inspecting of tables I realized that files with weight and heartrate have too small sample (8 and 7 users). So I didn't use them in my analysis.
The next step was to implement right formats for data (date, numbers, etc.)
Since the datasets are not very big I decided to use Excel for cleaning and analyzing and Tableau for visualization.

3. Process phase

The data were inspected for anomalies. 
- deleting duplicates: 
- deleting rows with null
- deleting unnecessary columns

![image](https://user-images.githubusercontent.com/99286647/206534162-797273db-3a08-4d64-9dfe-978ae2942a68.png)

4. Analyse and share phases (excel + Tableau)

4.1 Count the number of people of each type (sedentary, lightly active, fairly active, very active)
- Average daily steps for each user:

![image](https://user-images.githubusercontent.com/99286647/206543368-793fbdfd-7d97-4a93-b7e5-d39014823b6c.png)
- Countifs(sedentary < 5000, 5000 < lightly active < 7500, 7500 < fairly active < 10000, 10000 < very active)

![image](https://user-images.githubusercontent.com/99286647/206543950-aee8cc7f-fda5-4433-949e-a553ea9dc0d2.png)

![image](https://user-images.githubusercontent.com/99286647/206763708-802ee9bf-c37e-4f85-a6ce-9118c3468670.png)

_Conclusion: all types of users wear smart devices_

4.1 Steps/calories/sleep daily - graph in Tableau, average per weekday

![image](https://user-images.githubusercontent.com/99286647/207160801-e17996aa-cbc2-47b9-b370-79713b5ad330.png)

_Conclusion steps: users walk the recommended amount of steps daily (7.500). The less active day - Sunday_

_Conclusion calories: users burn average amount of calories daily (2.200 for lightly active day)_

_Cobclusion sleep: users don't sleep recommended amount of hours (8)._

4.2 Steps per hour: graph in Tableau, average per hour

![image](https://user-images.githubusercontent.com/99286647/207161399-63cf891c-4254-4d80-9092-bf51f3565baa.png)

_Conclusion: users are more active during lunchtime (between 12 pm and 2 pm) and in the evening (between 5 pm and 7 pm_

5. Act phase. Recommendations

5.1 Notifications about user's activities, reminders to stand up and walk

5.2 Post about sleeping (techniques, science articles).

5.3 Reminders getting ready for bed. Settings: turn off apps and screen brightness at certain time.

5.4 Reward system on burnt calories, total steps + share on social media

Link to Tableau dashboards: https://public.tableau.com/views/Bellabeat_16705267025550/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link
