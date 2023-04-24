![banner](https://uspto.report/TM/97094460/mark.png)
# Case Study: Bellabeat Marketing Analysis 


## Introduction
This case study is part of the Google Data Analytics course capstone. In this scenario I am an analyst tasked with analyzing fitness smart device usage data from Fitbit to gain insight into how consumers are using their smart devices. The goal is to guide future marketing strategies for Bellabeat, a high-tech manufacturer of health-focused products for women, based on the insights gained from the Fitbit data.

## The Data
The data for this analysis is the [FitBit Fitness Tracker Data](https://www.kaggle.com/arashnic/fitbit) (CC0: Public Domain, dataset made available through Mobius)

This Kaggle data has 18 CSV files containing personal fitness tracker data collected between April 12, 2016 and May 12, 2016 from thirty fitbit users who consented to the submission of personal tracker data, including minute-level output for physical activity, heart rate, and sleep monitoring. It includes information about daily activity, steps, and heart rate that can be used to explore users’ habits.

There is a main data set which includes information about daily activity, steps, heart rate ect. that can be used to explore users’ daily habits. The remaining data sets break down the data by hour, minute, and seconds for each user.

For the purpose of this case study I will be using the following datasets:
- `dailyActivity_merged.csv`
- `sleepDay_merged.csv`
- `hourlySteps_merged.csv`
- `minuteStepsWide_merged.csv`
- `minuteMETsNarrow_merged.csv`
- `dailyCalories_merged.csv`
- `weightLogInfo_merged.csv`

## Technologies
In order to complete this project, I used the following technologies:
- Python - NumPy, pandas, matplotlib
- jupyter notebook
- etc.

## Approach
To achieve the project objective of analyzing user behavior and providing recommendations to improve engagement, I followed these steps:

- Data cleaning and preparation: Cleaned and preprocessed the data to remove missing values, outliers, and inconsistencies.
- Exploratory data analysis: Conducted a thorough analysis of the data to identify patterns, trends, and correlations in user activity. In particular, focused on:
  - Aggregating the data to make it useful and accessible.
  - Organizing and formatting the data.
  - Performing calculations.
  - Creating visualizations.
  - Identifying trends and relationships.
  
Some areas of focus were:
  - The amount of time users spend sedentary.
  - The type of intensity users were exerting during their workouts.
  - How often users were logging no data.
  - How often users were logging sleep data.


## Results
After completing the project, I was able to provide six marketing strategies Bellabeat can take to unlock new growth opportunities for the company.
   
   ### 1. Provide Replacement Battery
   Battery life of the Bellabeat Leaf is 6 months. This is a plus for the brand since this eliminates users having to take off the device to charge every few days. Once a device is taken off for charging, there is no guarantee the user will put it back on. With 17% of the data inactive or missing you want to limit the number of times a user has to take off their device which might be a reason for the missing and inactive data. 
   
   But, since the battery will eventually need to be changed, 
   - **<span style="color:#fb937b">I recommend providing 1 replacement battery with the purchase of the Leaf. The coin cell battery used to power the Leaf is not a typical battery people have laying around the house. During the time it would take for them to get a replacement battery, the user may decide to give up on Bellabeat and try another fitness tracker product. Providing a replacement battery could potentially extend the customer lifespan. The more data and time a user has invested in a product the harder it would be to leave.</span>**
   
   
   ### 2. Reliable for High Intensity Activity   
   Based on the findings above, users are using their devices for both light activity and high intensity activity. On average 66% of users are working out between 4-6 days a week, with about half of the users working out at least 30 minutes a day. A workout friendly watch may be important to its users. In order to compete against the likes of fitbit, you are going to want to provide a device to your users that can track and withstand the wear and tear of these activities. 
   
   Right now Bellabeat lacks a device meant for tracking high intensity activities, alienating a portion of potential customers. Their devices track activity by steps. So if you complete an activity that is not step-based such as weightlifting or some other high intensity activity, the Bellabeat device will not recognize those activities or steps associated with them. These activities can be entered in the app manually, but is not convenient to the user.
   
- **<span style="color:#fb937b">I recommend conducting a survey with current customers as well as non customers to gauge opinion of the importance of automatic tracking of activity.</span>**


   
### 3. Comfortable for Sleep
   Users are rarely wearing their devices to track sleep. Only 24 of the 33 participants used their device for sleep tracking. The majority of those 24 participants inconsistently tracked sleep. 
   
   You will want to provide a device that is comfortable to wear. If the device is uncomfortable the users will take it off and eventually stop using it. Right now, Bellabeat sells clips and straps for the Leaf made of metal and leather that are not ideal for sleep comfort. 
   
   - **<span style="color:#fb937b">I suggest making a sleep comfortable clip that users can wear during sleep. Another option is to provide sleep tracking using the phone app for those who find wearing the device during sleep uncomfortable</span>**.
   
   
   ### 4. Automated Tracking
   Automate as much as possible, do not rely on users to input data manually. As shown above, when data needed to be added manually users inconsistently input the data. Ways Bellabeat can help Automate:
   
   - **<span style="color:#fb937b">provide or partner with a scale that can sync with the Bellabeat app for automatic tracking of weight.</span>**
   - **<span style="color:#fb937b">Automatic reminders sent to users on their device or phone to weigh themselves</span>**.
   - **<span style="color:#fb937b">Automatically recognize workouts - this would require a product update as the Leaf does not contain the technology for this type of motion detection</span>**.
   
   
   ### 5. Participation Incentives 
   The data above showed the most inactive days of the week appear to be the middle of the week with Tuesday, Wednesday, and Thursday. The least inactive days of the week appear to be the beginning and end of the week with Monday, Friday, and Saturday. Also, User step activity spikes in the early morning and late afternoon during the weekday, and during the early afternoon during the weekend. There is a significant step decrease in the evening during the weekend.
   
   - **<span style="color:#fb937b">I suggest using this data to create programs and competitions where users can earn badges and join groups to encourage workouts and activity during the middle of the week and throughout the month.</span>**
   - **<span style="color:#fb937b">As mentioned above users were paid for their participation in this study. Their activity over the span of the study could be a good indicator for participation in the programs or competitions implemented by Bellabeat. The participants started strong at the beginning of the 30 days, but the number of users who worked out dropped significantly in the final week. As such, you will want to implement reminders so activity participation does not fall off towards the end of the programs.</span>** 
   
   
   ### 6. Eliminate Sedentary Behavior
   
   According to studies, being sedentary for a prolonged amount of time can have adverse effects on your health. In particular, time spent sedentary is a risk factor for diabetes, obesity, and cardiovascular disease. Studies even show that the effects of sedentary behavior are difficult to offset, even with exercise. The best way to negate sedentary behavior is to break up long periods of sitting as often as possible.
   The analysis above showed that even with movement reminders users were sedentary for over an average of 15 hours with an average of 4 hours of active time. That means that users were sedentary for almost 80% of their day. As a fitness and wellness brand and based on the studies above that list the negative impacts being sedentary has on one's health, this is something Bellabeat should look to combat.
   The obvious solution is to have movement reminders sent to their device or phone, as the data above showed that these reminders spiked user steps in the last 10 minutes. Unfortunately though, only 17% of users are completing the movement goal after they receive a reminder. 
   - **<span style="color:#fb937b">I recommend Bellabeat to add an additional movement reminder at the half hour mark to further encourage breaking up long periods of sitting.</span>**
   - **<span style="color:#fb937b">I also suggest Bellabeat educate their customers on the dangers of sedentary behavior through their app and/or through email to their subscribers. This could be a quick way to educate their users and provide best practices they can follow to break up this behavior.</span>**
   
   ## Conclusion
   In this case study, I used real Fitbit data to evaluate smart watch device usage, determine trends, and theorize what was causing them. I was then able to develop an action plan for how these trends can help guide Bellabeat marketing strategy based on those findings.
