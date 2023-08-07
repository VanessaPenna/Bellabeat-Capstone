# Bellabeat-Capstone
Capstone Project for Google Analytics Professional Certificate
Ask:

Bellabeat, a high tech manufacturer of health focused smart devices for women.
(Bellabeat.com).

Analyze a data set to gain insights into how non- Bellabeat users are using their smart devices and Bellabeat would like to use the data to gain insights on how to better market their devices.

What are some of the user trends?
How will these trends influence Bellabeats marketing of their products?

The Stakeholders:
Urska Srsen, Bellabeat’s co-founder and Chief Creative Officer
Sando Mur, Mathematician and Bellabeats’s co-founder, key member of executive team

Data sources:
Fitbit Fitness Health Tracker - Collaborator Mobius
Top Contributors Anastasiia Chebotina, Macarena Lacasa, Julen Aranguren

Prepare:

Data sources used:Fitbit Fitness Health Tracker

ROCCC (Reliable, Original, Comprehensive, Current, Cited)

Reliable: Reliable for the purpose of this study as it is open source collected from 33 fitbit users
Original: Originality cannot be confirmed as it it is coming from a secondary source and not the originator
Comprehensive: Data does feel as it has some limitations, unsure of sample size and certain demographics. 
Current: No, 2016 data
Cited: Yes, see dated sources

Process:

Daily activities_merged data 
Fixed structural errors such as typos, capitalization, incorrect spelling
Eliminated duplicates
Changed decimals to whole numbers
Eliminated tracked distance column
Renamed total distance column to total tracked distance
Eliminated logged activities as most of the values were and wouldn’t have a significant impact on data
Added days of the week column (titled ActivityDay)

HourlySteps and HourlyCaloriesMerged
Split ActivityDate column into 2 columns; ActivityDate and ActivityTime
Added AM/PM column

SleepDayMerged
Added column TotalMinutesAsleep in Hours

Made All 4 Google sheets in CSV files

Analyze:

Data is only 33 users over a months time (4-12 to 5-12-2016)

Loaded the 4 files into BigQuery, separately
Individual Users (unique IDs)
Daily activity 33
Daily sleep 24
Hourly calorie 33
Hourly steps 33

Some users may not sleep with their smart device and that would account for the lower number in daily sleep.

Using Bigquery and SQL Several queries were asked and answered

1.Total active minutes by users ID in descending order
2.Activity levels by Days of the week in minutes
3.Min/max/avg of total steps, total distance, calories and activity levels grouped by user ID
4.Total minutes of sleep vc total steps by ID
5.Total number of calories by hour of the day
6.Hours of the day and total calories by ID

Tables were saved and uploaded to Tableau

Share:

Started in tableau with technical difficulties and moved to Googlesheets were my data lived to create several data visualizations 
Visualizations include:
Total Hours Slept by Date
Step Totals Per Activity Hour
Activity Type by Days of the Week
Active Minutes by Days of the Week


Act:

Trends emerged that users were active with their smart device Early in the week but less so by the end of the week. Virtually no data on thursdays. This would suggest that users are excited about a freah start ot he week and may not stay on track through out the week.

To keep up with market trends Bellabeat should:
Data is from 2016 and technology has changed exponentionally.Is bellabeat up-to-date with latest technological advances?

More relevant reminders, can Bellabeat add features that are more relevan to todays lifestayle and help users stay on track more consistently? Ideas such as a daily mental health (Just Breathe.)reminder or a time to stand up reminder if youve been sitting to long - allow users at sign up or to edit profile to adjust which kind of reminder and when to receive them.

Appeal to your community with challenges that benefit the greater good. Step challenges that unlock charitable contributions or more community focused goals that directly impact women can lead to more consistent activity.
"I'm happy to meet my step goals knowing I'm helping out XYZ cause!"




