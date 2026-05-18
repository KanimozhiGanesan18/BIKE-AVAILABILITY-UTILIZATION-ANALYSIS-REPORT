# BIKE-AVAILABILITY-UTILIZATION-ANALYSIS-REPORT
  The Bike Sharing Analytics project is designed to analyze and monitor real-time bicycle rental station data across multiple cities. The dataset contains information about bike stations, available bikes, empty docking stands, operational status, payment facilities, and geographic coordinates. 
  
1.	OBJECTIVES
   
⮚	Analyze bike station availability across multiple cities.
⮚	Monitor real-time bike inventory and empty docking stands.
⮚	Identify operational and non-operational stations.
⮚	Compare bike utilization across cities and stations.
⮚	Perform geographic analysis using latitude and longitude.
⮚	Build an interactive Power BI dashboard for business users.
⮚	Improve operational decision-making using data-driven insights.
⮚	Detect underutilized and overcrowded stations.
⮚	Support smart transportation and urban mobility planning.
⮚	Provide executive-level insights through KPIs and visualizations.

2.	DATA CLEANING IN POWER QUERY (PREPROCESSING)
   
         The following preprocessing steps were performed to ensure data quality.
⮚	Removed duplicate records using NAME column.
⮚	Corrected and changed date formats.
⮚	Remove Special character names in Name column.
⮚	Split the DATE column as “date” and “time” columns.
⮚	Change the column name as “latitude” and “longitude”

       TOOLS USED:
       
⮚	Excel 
⮚	Power BI (Power Query)
⮚	DAX

3.	DATA TRANSFORMATION
        To enhance the quality, usability, and analytical depth of the dataset, several data transformation steps were performed using Power Query and DAX.
      DEVELOPED CALCULATED TABLE:
  	
⮚	Year, Month Name, Quarter, Year-Quarter.
              This ensured consistent date relationships and improved report performance.
      DERIVED KEY PERFORMANCE INDICATORS (KPIS):
         Key metrics were developed using DAX to evaluate business performance:
         
⮚	Total Stations
⮚	Total Bikes YTD
⮚	Total Empty Stands
⮚	Total Open Stands
⮚	Total Closed Stations
 
            These KPIs provided a high-level summary of operational efficiency.
            
4.	DATA MODELLING
   
               Build relationships between tables to create a structured and scalable analytical data model.

    <img width="874" height="443" alt="Screenshot 2026-05-18 200941" src="https://github.com/user-attachments/assets/0000c382-6ad6-4c04-9d7a-5fd3521201ac" />

 
6.	DATA ANALYSIS (EDA) & VISUALIZATION
   
                INSIGHTS BASED CHARTS:
  	
 
PIE CHART – INSIGHTS:

⮚	Descriptive Analytics: Around 92.47% of bike stations are operational, indicating high service availability across the network. Most cities maintain stable bike distribution, while a few stations show low bike availability during peak usage.
⮚	Diagnostic Analytics: Closed stations are likely caused by maintenance activities, technical issues, or temporary operational shutdowns. Stations with fewer available bikes indicate higher customer demand or inefficient bike redistribution.
⮚	Predictive Analytics: High-demand stations may face bike shortages in the future if redistribution is not optimized. Urban locations with increasing usage trends may require additional bike stands and bikes over time.
⮚	Prescriptive Analytics: Implement real-time bike redistribution to balance bike availability across stations. Increase maintenance efficiency and expand capacity in high-demand locations to improve service reliability.

INSIGHTS BASED ON COLUMN CHART
 
⮚	Descriptive Analytics: Open stations without bonus facilities have the highest bike availability, contributing most to overall network operations.
⮚	Diagnostic Analytics: Lower bike availability in bonus-enabled stations may indicate higher user demand or limited station capacity.
⮚	Predictive Analytics: Bonus-enabled stations are likely to experience quicker bike shortages during peak usage periods.
⮚	Prescriptive Analytics: Optimize bike redistribution and reduce station downtime to improve overall service availability. 

INSIGHTS BASED ON LINE CHART
 
⮚	Descriptive Analytics: Bike availability shows a sharp decline over time, indicating high bike usage during initial periods.
⮚	Diagnostic Analytics: The rapid decrease in available bikes may be caused by peak-hour demand and insufficient bike redistribution.
⮚	Predictive Analytics: If current usage trends continue, several stations may experience bike shortages during busy periods.
⮚	Prescriptive Analytics: Implement real-time bike balancing and demand forecasting to maintain stable bike availability over time.

INSIGHTS BASED ON MAP:
 
⮚	Descriptive Analytics: Most bike stations across European cities are operational, showing strong geographic service coverage.
⮚	Diagnostic Analytics: A few regions with closed stations may indicate maintenance issues or lower operational efficiency.
⮚	Predictive Analytics: Urban regions with dense station clusters are likely to experience higher future bike demand.
⮚	Prescriptive Analytics: Expand bike capacity and improve operational monitoring in high-demand geographic regions to enhance service performance.

INSIGHTS BASED ON FUNNEL CHART:
 
⮚	Descriptive Analytics: Toulouse has the highest bike count, while smaller cities like Creteil and Jcdeauxbike have minimal usage.
⮚	Diagnostic Analytics: Large metropolitan areas show higher bike volumes due to greater population density and transport demand.
⮚	Predictive Analytics: Cities currently showing moderate growth, like Luxembourg and Nantes, are likely to see rising bike usage over time.
⮚	Prescriptive Analytics: Increase bike availability and infrastructure investment in mid-tier cities to balance demand and improve distribution efficiency.

INSIGHTS BASED ON TREEMAP:
 
⮚	Descriptive Analytics: Most available bikes are concentrated in a few large-capacity stands such as 20, 15, and 25.
⮚	Diagnostic Analytics: Higher availability in large stands suggests these locations serve high-demand or centrally located areas.
⮚	Predictive Analytics: Large-capacity stands are likely to continue holding the majority of available bikes as demand clusters in key zones.
⮚	Prescriptive Analytics: Increase capacity or redistribute bikes from low-usage stands to high-demand large stands to optimize availability.

7.	FINAL DASHBOARD:

 
<img width="1434" height="801" alt="Screenshot 2026-05-18 205508" src="https://github.com/user-attachments/assets/262b0680-951f-4eba-918a-38d67946267f" />


8.	CONCLUSION
   
                        The Bike Availability & Utilization Analysis reveals that the bike-sharing network is operating efficiently with a high percentage of active stations and strong geographic coverage across multiple cities. The dashboard highlights real-time bike availability, station utilization, operational status, and regional performance, helping identify demand patterns and service efficiency. The analysis also shows opportunities for improvement in bike redistribution, maintenance management, and capacity planning at high-demand locations. By leveraging real-time monitoring and predictive insights, organizations can enhance operational reliability, improve customer satisfaction, and optimize urban mobility services for future growth.
