# NYC Airbnb Analysis
## Overview 
Led a thorough project dedicated to analyzing essential metrics within NYC Airbnb data, employing strategic data-driven methods to prioritize vacation rental properties, project annual revenue, and offer insightful guidance for well-informed property investment decisions.
## Key Contributions
### Data Exploration and Cleaning
- Explored and scrutinized the NYC Airbnb dataset, identifying potential challenges in data cleansing.
- Documented the steps taken for data cleansing and maintained a version history for future reference.
### Filtered Listings:
- Applied relevant filters to listings, considering factors such as rental activity, minimum night requirements, and recent reviews.
- Documented all removed rows to ensure transparency in the data cleansing process.
### Prioritized Property Types:
- Utilized the number_of_reviews_ltm metric as a proxy for property rental frequency in estimating rental activity.
- Identified high-performing neighborhoods through standardized capitalization and removal of trailing spaces in the neighborhood column.
### Property Size Preferences:
- Refined the bedrooms column, creating a new column (bedrooms_clean) to replace empty cells with zeros.
- Constructed a pivot table to identify the most popular number of bedrooms for vacation rentals.
### Calculated Occupancy:
- Cleaned the calendar data, converting the available column into a numeric value (occupied).
- Created a new column (day_of_week) using the WEEKDAY() function for analyzing popular weekdays versus weekends.
- Developed a pivot table to compute the average occupancy rate for each listing.
### Methodology:
- Utilized Excel for data exploration, cleansing, and pivot table analysis.
- Applied data filtering and proxy metrics to inform strategic decision-making.
- Created advanced Excel functions for effective data standardization and analysis.
### Conclusion:
The project provided stakeholders with data-driven insights for property investment decisions. Through a strategic analysis of rental activity, prioritization of neighborhoods, and understanding property size preferences, the project offered valuable guidance for optimizing investment choices. Lower East Side one-bedroom listings proved to be the best choice for investment, ensuring a well-informed approach to property investment in the NYC Airbnb market for the client.
## Live Demo
[Link to Live Demo](https://docs.google.com/spreadsheets/d/1WM7ZrSIV52K5r3r0kLmMh3OgZ7K1_21fbrMfYkMoHLM/edit?usp=sharing)
