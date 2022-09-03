# Project: Airline-Crashes
This project is used to demonstrate skills and knowledge gained through the course of #NG30DAYS OF LEARNING.
----
# Problem Objectives
1. Yearly how many planes crashed? how many people were on board? how many survived? how many died?
2. Highest number of crashes by operator and Type of aircrafts.
‘Summary’ field has the details about the crashes. Find the reasons of the crash and categorize them in different clusters i.e Fire, shot down, weather (for the ‘Blanks’ in the data category can be UNKNOWN) you are open to make clusters of your choice but they should not exceed 7.
3. Find the number of crashed aircrafts and number of deaths against each category from above step.
4. Find any interesting trends/behaviors that you encounter when you analyze the dataset.

# Data sourcing:
The data used for this project was obtained on Github, check the link below 
https://github.com/theoyinbooke/30Days-of-Learning-Data-Analysis-Using-Power-BI-for-Students/tree/main/Airline%20Project

# Data Preparation & Transformation
Delete:
18 Blank rows in operators' data and 19 rows without location details were removed.
Irrelevant data:
The Time data& route data were removed.
Add New Attributes:
Added five columns for yr. month, and day, index and no. of survived resp.
Trim: location, operators
 Created New Table: contains causes of crashes and no. of crashes that each factor has caused.
Issue;
there was no sufficient information on ground attribute of the dataset.

# Data Visualization
The dataset was visualised using Power Bi software.

#Summary:
Shot down cases; 
A total crash of 132 was caused by shot-down incidents.
Out of Fuel cases;
Total crashes of 214 were caused by fuel scarcity.
Killed Cases;
Total crashes of 289 were caused by annihilation incidents.
System Failure:
A Sum of 710 cases was caused by system failure of the aircraft and operators.
Weather:
Total Crashes of 1814 were caused by Climatic factors such as rain, storm, snow, lightning, fog, and poor visibility.
Unknown:
765 crash cases were caused by an unknown factor in this dataset.

#Insight:
The highest occurrence of aircraft crashes was recorded in the year 1998 with a value of 368445.
The highest no. of survived from aircraft crashes was recorded in the year 1999 with a value of 1788.
The highest no. of fatalities (death) events in aircraft crashes was recorded in the year 1972 with the value of 2937.
The Highest No. of crashes by the operator was 179
The Highest No. of crashes by aircraft type was 333.

# Thanks.
