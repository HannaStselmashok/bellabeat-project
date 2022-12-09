Google Analytics Capstone Project - Bellabeat

1. Ask phase
Questions to be unswered:
- What are some trends in smart device usage?
- How could these trends apply to Bellabeat customers?
- How could these trends help influence Bellabeat marketing strategy?

2. Prepare phase
The data (CSV files) was downloaded to my computer. After inspection of tables I realised that files with weight and heartrate have too small sample (8 and 7 users). So I didtn't use them in my analysis.
The next step was to implement right formats for data (date, numbers, etc.)
Since the dataset are not very big I decided to use excel for cleaning and analysis and Tableau for visualization.

3. Proccess phase
The data was inspected for anomalies. 
- deleting dublicates: 

![image](https://user-images.githubusercontent.com/99286647/204351401-f17bce32-2d04-4b85-b957-7f201842b2c0.png)
- deleting raws with null
- deleting unnecessary columns

![image](https://user-images.githubusercontent.com/99286647/206534162-797273db-3a08-4d64-9dfe-978ae2942a68.png)

4. Analyse and share phases (excel + Tableau)
4.1 Count the number of people of each type (sedentary, lightly active, fairly active, very active)
- Average daily steps for each user:

![image](https://user-images.githubusercontent.com/99286647/206543368-793fbdfd-7d97-4a93-b7e5-d39014823b6c.png)
- Countifs(sedentary < 5000, 5000 < lightly active < 7500, 7500 < fairly active < 10000, 10000 < very active)

![image](https://user-images.githubusercontent.com/99286647/206543950-aee8cc7f-fda5-4433-949e-a553ea9dc0d2.png)
