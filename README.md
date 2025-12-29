# Yorkshire-and-Humber-Regional-Crime-
Yorkshire and Humber Regional Crime Dashboard
dash board link (https://app.powerbi.com/groups/me/reports/d5eff88a-c4ef-49d9-a07e-2957cd13b459/70773a54bcc8ece771eb?experience=power-bi)
Project Overview

The Yorkshire and Humber Regional Crime Dashboard is a data analytics project designed to visualize and analyze regional crime trends across Yorkshire and Humber, UK, covering the areas of West Yorkshire, South Yorkshire, Humberside, and North Yorkshire.

This dashboard was developed using Microsoft SQL Server and Power BI, transforming raw crime data from official UK Police datasets into an interactive and insightful analytical report. It provides decision-makers with a clear view of crime categories, yearly comparisons, and regional variations, supporting law enforcement agencies in making data-driven decisions for crime prevention and resource allocation.

Objectives

To analyze regional crime data from 2022 and 2023 using SQL and Power BI.

To visualize crime patterns across different police forces and months.

To identify trends in total crimes, crime types, and geographical distribution.

To support data-driven decision-making for regional law enforcement authorities.

Data Source

Dataset: UK Police Open Data Portal

Region Covered: Yorkshire and Humber (West Yorkshire, South Yorkshire, Humberside, North Yorkshire)

Time Period: 2022–2023

Data Type: Monthly recorded crimes by type and police force

Methodology
1. Importing Data

Downloaded the monthly crime dataset from the UK Police Data Portal.

Saved and organized data under a new project folder named “Yorkshire Crime.”

2. Creating the SQL Database

Created a new database in Microsoft SQL Server named YorkshireCrimeDB.

Imported the flat files containing crime data into the database using the Import Flat File Wizard.

3. Data Cleaning

Renamed columns for clarity and consistency.

Modified data types and added a primary key.

Handled missing or null values and ensured dataset integrity.

4. Importing into Power BI

Connected SQL Server to Power BI using Get Data → SQL Server.

Imported the cleaned dataset and built data relationships.

Developed visualizations to highlight patterns, totals, and comparisons across years and regions.

Tools Used
Tool	Purpose
Microsoft SQL Server	Data cleaning, preparation, and integration
Power BI	Dashboard design and visualization
Excel	Data review and preprocessing
Dashboard Features
1. Total Crimes Overview

Displays total reported crimes across all four police regions for 2022 and 2023.

Shows an overall decline in crime from 2022 (673,709 crimes) to 2023 (374,875 crimes).

2. Crimes by Type

Visualizes 14 distinct crime categories (e.g., violent crime, theft, drugs).

Helps identify the most common and critical crime types across regions.

3. Total Crimes by Year

Clustered column chart comparing total crime counts for each year.

Highlights that crime decreased significantly from 2022 to 2023, suggesting improved policing or social changes.

4. Police Station Crime Reports

Donut chart showing regional contribution to total crimes:

West Yorkshire reported the highest crime share (around 50%) in both years.

North Yorkshire recorded the lowest share.

Illustrates urban–rural variation in crime intensity.

5. Total Crime Distribution Over Months

Line chart showing monthly crime fluctuations.

Peak months: May, July, and August (warmer months).

Decline toward year-end indicates possible seasonal behavior in crime rates.

6. Crime Type Distribution

Clustered column chart showing the frequency of different crime types across the two years.

Violent crimes recorded the highest number of cases, marking it as a key concern for regional authorities.

Key Insights

Total crimes decreased between 2022 and 2023, suggesting a potential improvement in public safety.

West Yorkshire consistently reported the highest number of crimes among the four forces.

Violent crimes are the most prevalent category in both years.

Seasonal trends show higher crime activity during mid-year months (spring–summer).

The dashboard supports targeted law enforcement and efficient resource deployment.
Conclusion

The Yorkshire and Humber Regional Crime Dashboard offers an analytical view of crime patterns using real police data. By integrating SQL data management with Power BI visualization, it converts large raw datasets into an interactive, visual narrative that helps law enforcement understand crime trends, seasonal variations, and regional disparities.

This project demonstrates how data analytics can improve decision-making, enhance situational awareness, and support the development of effective crime prevention strategies.
