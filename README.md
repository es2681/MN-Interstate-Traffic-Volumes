# MN Interstate Traffic Volumes

## Project Overview
Among other things, the [Minnesota Department of Transportation](https://www.dot.state.mn.us/) (MnDOT) is responsible for the development and maintenance of state roads and highways. The agency keeps a large collection of highway traffic records and is interested in using this information to improve Minneapolis interstate infrastructure. MnDOT requested help condensing its overwhelming dataset into meaningful findings to better understand the interstate's current traffic patterns. The agency requires the development of a dashboard including visualizations of the following:
- Traffic volume throughout the year organized by year, day, and hour
- Traffic volume in various weather conditions
- Traffic volume on different holidays

Traffic data from MnDOT was uploaded into [Tableau Public](https://public.tableau.com/app/discover) where a series of charts were developed and then assembled into a single dashboard. The completed Tableau dashboard is located **[here](https://public.tableau.com/views/MNInterstateTraffic_17171775150730/MNTrafficDashboard?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link)**.

## Resources
- Tableau Desktop Public
- Tableau Public
- [Metro_Interstate_Traffic_Volume.csv](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Metro_Interstate_Traffic_Volume.csv): MnDOT provided hourly traffic data collected between October 2, 2012 and September 30, 2018. The dataset includes date, time, temperature, precipitation, weather, interstate traffic volume, and identifies whether the date is a holiday.

## Analysis & Results
The final product is saved to Tableau Public as [MN Interstate Traffic Dashboard](https://public.tableau.com/shared/GGB9MGP9R?:display_count=n&:origin=viz_share_link). Screenshots of the the dashboard and the associated visualizations are copied below for reference, and are also saved in the [visuals](https://github.com/es2681/MN-Interstate-Traffic-Volumes/tree/main/Visuals) folder.

### MN Interstate Traffic Dashboard
In addition to displaying the requested visuals, the dashboard includes a drop-down menu where users can filter the data by year. While the database includes traffic information between 2012 and 2018, MnDOT was most interested in the recent traffic patterns of the past three years. The dashboard is currently filtered to display traffic volumes for 2016, 2017, and 2018. Different years can be viewed using the drop-down menu on the Tableau Public website. The dashboard also includes a download button so that it or any of the visualizations individually can be saved as PDFs. 
![MN Interstate Traffic Dashboard](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/MN%20Traffic%20Dashboard.png)

### Monthly Traffic Volumes by Year
Monthly total traffic volumes between 2016 and 2018 range from 1.9M to 3.4M vehicles on the Minneapolis interstate. Traffic is generally the lowest in February and highest in May and August.
![Monthly Traffic Volumes by Year](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/Monthly%20Traffic%20Volumes%20by%20Year.png)

### Traffic Volumes by Hour
The graph breaks down total traffic volume at every hour of the calendar year. Unsurprisingly, traffic is generally highest during the day and lower over night. The chart below shows a sample of traffic volumes for the month of January. The entire year can be viewed on the dashboard or in the [visuals](https://github.com/es2681/MN-Interstate-Traffic-Volumes/tree/main/Visuals) folder.
![Traffice Volumes by Hour](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/Sample%20Traffic%20Volume%20by%20Hour%20-%20January.png)

### Traffic Volumes by Weather Type
Traffic volumes are highest when the weather is cloudy or clear. Traffic drops by more than 50 percent when weather conditions are poor. 
![Traffic Volumes by Weather Type](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/Traffic%20Volumes%20by%20Weather%20Type.png)

### Traffic Volumes by Holiday
Minnesota drivers spend the most time on the road on New Years Day, Labor Day, and Memorial Day. Traffic, on average, is about the same on Thanksgiving as during the Minnesota State Fair held in August.
![Traffic Volume by Holiday](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/Traffic%20Volumes%20by%20Holiday.png) 

## Summary
The dashboard displays traffic volume trends of the Minneapolis interstate based on holiday, weather, time of day, and month. For further analysis, MnDOT should compare the data to more recent results collected between 2019 and present, to investigate whether volumes have changed over time. Major increases or decreases in traffic may have significant impacts on interstate infrastructure needs. Additional consideration should be given to alternative types of travel such as cycling and public transporation. Improvements to bike lanes and bus or lightrail schedules may lead to increased ridership which would help reduce car congestion on the highways. 
