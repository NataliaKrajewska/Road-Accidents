# Road Accidents

<h2>Table of Contents</h2>

- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Data Source](#data-source)
- [Tools](#tools)
- [Project Walkthrough](#project-walkthrough)
- [Findings](#findings)

<h2>Project Overview</h2>
This project aimed to analyze road traffic accidents that occurred in Great Britain during years 2021 and 2022. The primary focus was on creating an interactive dashboard using Excel to provide insights into the accident data. The file consist of 8 tabs: Dataset, KPIs, Monthly Trend, Road Type&Surface, Area&Light, Dashboard, Data Analysis.

<h2>Problem Statement</h2>

**<br>Primary Key Performance Indicators (KPIs):</br>**
- What is the number of total casualties after accident?
- What is the number of total casualties by accident severity?
- What is the percentage of total casualties by severity?
- What is the highest number of casualties by the type of vehicle?

**Secondary Key Performance Indicators (KPIs):**
- What is the number of total casualties by vehicle type?
- What is the monthly trend (2021 vs. 2022)?
- What is the number of casualties by road type?
- What is the distribution of casualties by road Surface?
- What is the relation between casualties, area, and light conditions?


<h2>Data Source</h2>
The dataset used in this project is the "Dataset" sheet in "Road_Accidents.xlsb" file.

<h2>Tools</h2>

- Microsoft Excel

<h2>Project Walkthrough</h2>

**1. Data Cleaning:**
   - Correction of misspellings.
   - Filling blank cells with "Unknown".

**2. Data Processing:**
   - Adding "Month" column and extracting month name from "Accident Date" column using TEXT function.
   - Adding "Year" column and extracting year from "Accident Date" column using TEXT function.

**3. Data Analysis**

- Creating Pivot Tables in tabs named according to the analyzed KPIs ("Primary KPIs", "Monthly Trend", "Road Type&Surface", "Area&Light" tab). Additionally, all created Pivot Tables were summarized in "Data Analysis" tab.
    

![](Data_Analysis.png)

- Calculating percentage of Fatal, Serious and Slight Casualties.
- Creating calculated items within the Pivot Table to calculate Total Casualties by Car Type (car, bus, van, motorcycle, agricultural vehicle, other) and calculating percentage of Total Casualties by Car.
- Creating calculated items within the Pivot Table to calculate Total Casualties by Road Surface (dry, wet, snow/ice, unknown).
- Creating calculated items within the Pivot Table to calculate Total Casualties by Light Conditions (daylight, darkness).
- Introducing a timeline and a slicer (Rural/Urban Area).

**4. Data Visualization**

- Developing donut charts representing the percentage of fatal, serious, slight casualties and casualties by car.
- Creating a line chart for monthly trend in 2021 and 2022.
- Creating a pivot chart (bar chart) representing casualties by road type.
- Creating a treemap representing the number of casualties by road surface.
- Creating pivot charts (donut charts) representing the number of casualties by area and light conditions.
- Dashboard building.

![](Dashboard.png)

**User Interface:**

- Filter Panel was created for the timeline and slicer with hovering effect to display filtered data from 2021, 2022, rural and urban area.
- Navigation Panel on the left side of the dashboard contains clickable black icons that navigate to "Dashboatd" tab, "Data Analysis" tab, "Reported Road Casualties Great Britain" Wikipedia website and e-mail. Additionally there are two icons at the botton of this panel that navigate to my LinkedIn and Github profiles.

<h2>Findings</h2>

- The number of total casualties after accident is 417883.
- There were 7135 fatal, 59312 serious and 351436 slight casualties. That constitutes accordingly 1.7%, 14.2% and 84.1% of all casualties.
- Car accidents generated the highest number of casualties: 333485 (79.8%).
- There were 33672 casualties of accidents involving motorcycles.
- There were 33472 casualties of accidents involving vans.
- There were 12798 casualties of accidents involving buses.
- There were 1032 casualties of accidents involving agricultural vehicles.
- There were 3424 casualties of accidents involving other vehicles (pedal cycle, ridden horse and others).
- Monthly trend line chart indicates that there were more casualties in 2021 than 2022 with an exception of February, when the number of casualties was similar.
- Single carriageway accidents were associated with the highest number of casualties (309698) in comparison with other road types.
- There were 279445 casualties of accidents on dry road surface, 115261 casualties of accidents on wet road surface, and 22781 casualties of accidents on snowy/icy road surface.
- Urban area accidents were associated with higher number of casualties (255864) than rural area accidents (162019).
- There were more casualties of accidents in daylight (304963) than in darkness (112920).
