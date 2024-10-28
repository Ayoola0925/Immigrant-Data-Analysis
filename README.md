#### Immigrant-Data-Analysis



### Table of Contents

- [Project Overview](project-overview)

- [Tools and Technologies Used](tools-and-technologies-used)

- [Data Cleaning Process](data-cleaning-process)

- [Data Analysis](data-analysis)
  
- [Key Performance Indicators (KPIs)](key-performance-indicators-(kpi))

- [Dashboard Creation](dashboard-creation)

- [Results and Insights](result-and-insights)

- [Visuals](visuals)

- [Conclusion](conclusion)


  
## Project Overview

This project involves the analysis of immigration data categorized by various means of transportation. The goal was to clean the data, perform exploratory data analysis (EDA), and create a visually appealing dashboard to present the findings effectively.


## Tools and Technologies Used

- Data Source: Microsoft Excel

- Data Transformation: Power BI

- DAX (Data Analysis Expressions): Used for calculations and measures


  
## Data Cleaning Process

- Data Import: Imported the dataset from Excel into Power BI.

- Data Transformation: Cleaned the data by:

- Removing unnecessary columns.

- Correcting syntax issues.

# Calendar Table Creation:

- Created a calendar table using the DAX function:
DAX
Calendar = CALENDARAUTO()

- Added a Year column with the formula:
DAX
Year = YEAR([Date])

Relationship Setup: Established a relationship between the main dataset and the calendar table using the date field.



## Data Analysis

- Total Immigrants by State: Calculated the total number of immigrants for each state.

- Top 10 Ports with the Highest Immigrants: Identified the top 10 ports based on the number of immigrants using filtering techniques.

- Total Immigrants by Year and Border: Analyzed immigration trends over the years and by border entry points.

- Total Immigrants as per Measure:

Created a measure to calculate total immigrants:
DAX
Total Immigrant = SUM(Border_Crossing_Entry_Data[Value])

Created another measure for total states:
DAX
Total State = COUNT(Border_Crossing_Entry_Data[State])


## Key Performance Indicators (KPIs)

- Total Immigrants: [11b]

- Total States: [395K]



## Dashboard Creation

Visualizations: Developed a dashboard using various chart types, including:

- Table Chart

- Line Chart

- Line and Clustered Column Chart

- Donut Chart

- Stacked Column Chart

- Gauge Chart

- Card Chart
- 
Formatting: Customized visuals and properties to enhance clarity and aesthetics.

Design: Selected color schemes and completed naming conventions for clarity.


## Results and Insights

The dashboard effectively illustrates immigration trends by state and port, providing valuable insights for policymakers and stakeholders interested in immigration data.


## Visuals

<p align="center">
  <img src="https://via.placeholder.com/300" width="45%" alt=![Immigrants Dashboard](https://github.com/user-attachments/assets/fa5425b7-a2b8-479b-8a00-69e3942d4446)>
  <img src="https://via.placeholder.com/300" width="45%" alt=![Immigrants Dashboard 2](https://github.com/user-attachments/assets/2b174c8c-74b7-46f5-afcd-6be6f2633045)
>
</p>


## Conclusion

This project showcases my ability to clean, analyze, and visualize data effectively using Power BI. The insights gained can be instrumental for various stakeholders in understanding immigration patterns.
