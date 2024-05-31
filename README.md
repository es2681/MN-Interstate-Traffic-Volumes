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
- [Metro_Interstate_Traffic_Volume.csv](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Metro_Interstate_Traffic_Volume.csv)

## Analysis & Results
The final product is saved to Tableau Public as [MN Interstate Traffic Dashboard](https://public.tableau.com/shared/GGB9MGP9R?:display_count=n&:origin=viz_share_link). Screenshots of the the dashboard and associated visualizations are also copied below.

### MN Interstate Traffic Dashboard
![MN Interstate Traffic Dashboard](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/MN%20Traffic%20Dashboard.png)

### Monthly Traffic Volumes by Year
![Monthly Traffic Volumes by Year](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/Monthly%20Traffic%20Volumes%20by%20Year.png)

### Traffic Volumes by Hour
![Traffice Volumes by Hour](https://github.com/es2681/MN-Interstate-Traffic-Volumes/blob/main/Visuals/Traffic%20Volumes%20by%20Hour.png)

### Configuring Data in Power BI
The Microsoft Excel Sales Data, Purchases, and Countries tables were imported into Power BI. They were examined for duplicate, null, or otherwise unexpected values. Each column was checked or altered to ensure the correct data type designation. A currency exchange table was added to the file so that the sales figures could later be homogenized.

### Designing the Data Model
Table relationships were configured to develop a data model. Cardinality and cross filter direction were considered for each relationship to ensure accuracy. A Calendar table was generated using a DAX formula and then marked as a Date Table. Using the Exchange Data table, the Sales Data table was duplicated with all currency converted to US dollars and named Sales in USD.
![Data Model](https://github.com/es2681/Tailwind-Traders-Report/blob/main/Resources/Data%20Model.png)
### Calculating Aggregations
DAX code was used to calculate aggregations for Yearly Profit Margin, Quarterly Profit, Year-to-Date Profit and Median Sales. 

### Developing a Sales Report
Graphs, charts, and other visuals were generated according to Tailwind Trader specifications into a Sales Report, including an overview of the company's sales and profits. Text was enlarged and the color theme was updated so that the report would be accessible to a greater audience.
#### Sales Overview Page
![Sales Overview](https://github.com/es2681/Tailwind-Traders-Report/blob/main/Resources/Sales%20Overview.png)
#### Profit Overview Page
![Profit Overview](https://github.com/es2681/Tailwind-Traders-Report/blob/main/Resources/Profit%20Overview.png)
### Creating an Executive Dashboard
The finalized report was published to Power BI Service. Visuals were pinned to an Executive Dashboard where they were designed to be user-friendly via the web as well as mobile devices.

## Summary
Raw sales data at Tailwind Traders was cleaned, transformed, and visualized so that company executives could make data-driven decisions for their future marketing budget. Based on the high median sales distribution in the UAE yet the country's relatively low annual profit margin and total count of loyalty points, executives decided to increase marketing and promotions in the UAE to encourage more of these larger sales as well as drive customer loyalty. 
