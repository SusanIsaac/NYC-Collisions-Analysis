
# NYC Collisions Analysis
### Traffic Safety Overview | Data Analyst Bootcamp Capstone Project

## Project Overview

Motor vehicle collisions are an important road-safety concern in New York City. Understanding when collisions occur, where they are concentrated, and which contributing factors are frequently reported can help identify areas for further investigation and support data-informed road-safety decisions.

This project explores New York City motor vehicle collision data using Power BI. The analysis examines collision frequency across months, seasons, days of the week, and hours of the day, alongside collision locations, contributing factors, and reported fatalities.

The objective is to transform collision records into meaningful visual insights that support a better understanding of traffic-safety patterns.

## Project Objectives

The analysis focuses on the following objectives:

- Examine monthly collision distribution and identify possible seasonal patterns.
- Explore collision frequency by weekday and hour to identify periods of elevated activity.
- Identify streets with high reported collision counts and assess their contribution to the overall total.
- Examine reported contributing factors and investigate the factors associated with fatal collisions.
- Develop practical recommendations based on the observed patterns.

## Dashboard Overview

The Power BI dashboard brings together the project's key metrics and visualizations in one interactive report.

<img width="1217" height="714" alt="Screenshot 2026-10-11 152540" src="https://github.com/user-attachments/assets/273ff6eb-4902-47ac-ba0d-7a5f1f20bb27" />

### Dashboard Components

The dashboard includes:

- **Key Performance Indicators:** Total reported collisions, persons killed, leading collision street, and a contributing-factor summary.
- **Contributing Factors:** A comparison of reported factors associated with collisions.
- **Seasonal Distribution:** Collision counts across Spring, Winter, Summer, and Fall.
- **Street-Level Analysis:** Collision counts and street-level collision percentages.
- **Hourly Distribution:** Collision frequency across different hours of the day.
- **Day-of-Week Analysis:** Comparison of reported collisions across the seven days of the week.
- **Monthly Distribution:** Percentage of total collisions attributed to each month.

Together, these visualizations provide an overview of collision patterns across time, location, and contributing factors.

## Key Findings and Insights

### 1. Monthly and Seasonal Patterns

The monthly distribution shows variation in collision percentages throughout the year. March records the highest displayed monthly percentage, at approximately 10.5%, followed by January at approximately 9.7% and February at approximately 8.9%. December has the lowest displayed percentage, at approximately 7.1%.

The seasonal chart shows Spring with the highest reported collision count, at approximately 64,000, followed by Winter at approximately 61,000, Summer at approximately 58,000, and Fall at approximately 55,000.

Viewed together, the charts suggest that collision counts vary across the year, with relatively high totals in Spring and Winter. However, these figures alone cannot establish that seasonal conditions caused the differences.

### 2. Collision Frequency by Day and Hour

The weekday visualization shows Friday with the highest displayed collision count, at approximately 37,000. Thursday follows at approximately 35,000 collisions.

The hourly visualization shows fluctuations in collision frequency throughout the day, with several hours displaying elevated counts around the later part of the day.

These patterns identify time periods worth investigating in greater detail. Traffic volume, commuting patterns, congestion, and other travel behaviors may help explain the distribution, but additional evidence is needed to establish the causes.

### 3. Collision Locations

The dashboard identifies Belt Parkway as the leading collision street in its summary metrics.

This makes the location a useful starting point for further investigation. However, a high collision count does not necessarily mean that a road is more dangerous than other roads, because traffic volume, road length, and the number of vehicles using the road can differ.

A more detailed assessment should examine individual road segments, collision severity, traffic exposure, and the circumstances surrounding reported incidents.

### 4. Contributing Factors and Fatalities

The dashboard includes contributing-factor comparisons and reports 635 persons killed in its summary metrics.

The main contributing-factor summary identifies Driver Inattention/Distraction, while the visible factor chart also shows a substantial number of records categorized as Unspecified and Unsafe Speed.

These categories should be validated against the underlying data before a definitive ranking is reported, since the dashboard's summary and detailed chart appear inconsistent.

Fatal collisions require a separate analysis. Records involving at least one person killed should be examined by Vehicle 1 contributing factor to determine which factors occur most frequently in fatal collision records. This ranking cannot be established from the dashboard screenshot alone.

## Recommendations

Based on the observed patterns, the following actions are recommended for further investigation:

1. **Investigate monthly variation:** Examine the circumstances associated with the March peak, including traffic volume, weather, and travel patterns.
2. **Review high-frequency periods:** Investigate collision hotspots during weekdays and hours with elevated collision counts.
3. **Conduct location-based analysis:** Examine collision-prone segments of Belt Parkway and other high-count streets, prioritizing locations with serious injuries or fatalities.
4. **Validate contributing factors:** Review the underlying records to distinguish identified factors from unspecified entries and reconcile the dashboard's rankings.
5. **Prioritize collision severity:** Analyze injuries and fatalities alongside collision counts so road-safety measures reflect the potential harm, not just the frequency of incidents.
6. **Use exposure-adjusted comparisons:** Where suitable traffic-volume data is available, calculate collision rates relative to traffic exposure rather than relying solely on raw counts.

## Methodology

The project uses a visual analytics approach in Power BI.

The analysis involves:

1. Reviewing the collision dataset and identifying the fields required for the analysis.
2. Preparing date, time, location, collision count, fatality, and contributing-factor fields.
3. Grouping collision records by month, season, weekday, hour, street, and contributing factor.
4. Creating summary metrics and charts to compare the distributions.
5. Interpreting the results, identifying patterns for further investigation, and formulating recommendations.

The exact calculations and filters should be verified against the underlying dataset to ensure consistency across dashboard visuals.

## Tools and Technologies

- **Power BI:** Data modeling, visualizations, dashboard development, and analysis.
- **Microsoft Excel or CSV:** Dataset review and preparation, where applicable.
- **GitHub:** Project documentation and portfolio publication.

## Conclusion

This project demonstrates how collision records can be transformed into an interactive traffic-safety dashboard. The visualizations highlight variation in collisions across months and seasons, differences between weekdays, elevated counts at particular hours, and the importance of examining high-count streets and reported contributing factors.

The results provide a foundation for further investigation into road-safety risks. More reliable conclusions about the causes of collisions and the factors associated with fatal incidents require validation of the underlying data and additional analysis of collision severity, traffic exposure, and road conditions.

## Data Limitations

The dashboard displays approximately 238,421 collisions and 635 persons killed. 
The project brief specified the period from January to August 2020. However, this analysis uses data covering the full year, from January to December 2020, to provide a complete overview of collision patterns throughout the year.

## Project Files

- `README.md` — Project overview, findings, methodology, and recommendations.
- `images/nyc-collisions-dashboard.png` — Power BI dashboard screenshot.
- Power BI project file — Add the `.pbix` file to the repository if it is available and suitable for sharing.
- Source dataset — Include the original data or a link to its source, subject to applicable access and sharing restrictions.
