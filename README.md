# MN Interstate Traffic Volumes

## Project Overview
The Minnesota Department of Transportation (MnDOT) is hoping to use their traffic volumes data to improve their infrastructure on the Minneapolis interstate. MnDOT requested help with designing charts and developing a business intelligence dashboard to better understand traffic patterns. They requested three specific visuals:
- Traffic volume throughout the year; ideally organized by year, month, week, day, and hour
- Traffic volume in various weather conditions
- Traffic volume on different holidays

Interstate data from MnDOT was uploaded into [Tableau Public](https://public.tableau.com/app/discover) where a series of charts were developed and then assembled into a single dashboard.

## Resources
- Tableau Desktop Public
- Tableau Public
- [Metro_Interstate_Traffic_Volume.csv](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Metro_Interstate_Traffic_Volume.csv): MnDOT provided hourly traffic data collected between October 2, 2012 and September 30, 2018. The dataset includes information on the date, temperature, precipitation, weather, traffic volume, and identifies whether the date is a holiday.

## Analysis & Results
The final product is saved to Tableau Public as [MN Interstate Traffic Dashboard](https://public.tableau.com/shared/GGB9MGP9R?:display_count=n&:origin=viz_share_link). Screenshots of the the dashboard and the associated visualizations are copied belowfor reference.

### MN Interstate Traffic Dashboard
In addition to the required visuals, the dashboard includes a drop-down menu where users can filter by year. While the database includes information between 2012 and 2018, MnDOT wanted to see the most recent data for the past three years. As such, the dashboard is filtered to display traffic volumes for only 2016, 2017, and 2018. The dashboard also includes a download button to save the dashboard as a PDF. 
![MN Interstate Traffic Dashboard](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/MN%20Traffic%20Dashboard.png)

### Monthly Traffic Volumes by Year
Monthly total traffic volumes between 2016 and 2018 range from 1.9M to 3.4M vehicles on the Minneapolis interstate. Traffic is generally the lowest in February and the highest in May and August.
![Monthly Traffic Volumes by Year](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/Monthly%20Traffic%20Volumes%20by%20Year.png)

### Traffic Volumes by Hour
The graph breaks down traffic volumes at every hour of the day for the calendar period. Unsurprisingly, traffic is generally higher during the day and lower over night. The chart below shows a sample of traffic volumes for the month of January. However, the entire year can be viewed on the dashboard or in the visualizations folder.
[Traffice Volumes by Hour](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/Sample%20Traffic%20Volume%20by%20Hour%20-%20January.png)

### Traffic Volumes by Weather Type
Traffic volumes are highest when the weather is cloudy or clear. Traffic drops by more than 50 percent when weather conditions are poor. 
![Traffic Volumes by Weather Type](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/Traffic%20Volumes%20by%20Weather%20Type.png)

### Traffic Volumes by Holiday
Minnesota drivers spend the most time on the road on New Years Day, Labor Day, and Memorial Day. Traffic, on average, is about the same on Thanksgiving as during the Minnesota State Fair.
![Traffic Volume by Holiday](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/Traffic%20Volumes%20by%20Holiday.png) 

## Summary
