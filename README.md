# Hotel_Reservation_Analysis

### Overview
This project involves the analysis of a hotel reservation dataset to uncover valuable insights into guest preferences, booking trends, and other key factors that influence hotel operations. The analysis was conducted using SQL queries to explore various aspects of the dataset, such as the most popular meal plans, booking trends, room types, and market segments. The insights derived from this analysis can help in making data-driven decisions to optimize hotel operations and enhance guest satisfaction.

#### Dataset Description
The dataset used for this analysis contains comprehensive information about hotel reservations. It includes the following columns:
Booking_ID: A unique identifier for each hotel reservation.
no_of_adults: The number of adults in the reservation.
no_of_children: The number of children in the reservation.
no_of_weekend_nights: The number of nights in the reservation that fall on weekends.
no_of_week_nights: The number of nights in the reservation that fall on weekdays.
type_of_meal_plan: The meal plan chosen by the guests.
room_type_reserved: The type of room reserved by the guests.
lead_time: The number of days between booking and arrival.
arrival_date: The date of arrival.
market_segment_type: The market segment to which the reservation belongs.
avg_price_per_room: The average price per room in the reservation.
booking_status: The status of the booking (either "Cancelled" or "Not Cancelled").

The dataset contains a total of 700 reservations.

#### Key Insights
The analysis of the dataset revealed the following key insights:
1. Total Reservations: There were 700 reservations in the dataset.
2. Most Popular Meal Plan: Meal Plan 1 was the most popular among guests, with 527 guests selecting this option.
3. Average Price per Room for Reservations Involving Children: The average price per room for reservations involving children was 144.57 units.
4. Reservations in 2017: A total of 123 reservations were made in the year 2017.
5. Most Commonly Booked Room Type: Room Type 1 was the most commonly booked room type.
6. Weekend Reservations: 383 reservations included weekend nights.
7. Lead Time: The highest lead time was 443 days, and the lowest was 0 days.
8. Most Common Market Segment: The Online market segment was the most common method for reservations.
9. Booking Status: There were no reservations with a booking status of "Confirmed". The status was either "Cancelled" or "Not Cancelled".
10. Total Number of Adults and Children: Across all reservations, there were 1316 adults and 69 children.
11. Average Weekend Nights for Reservations Involving Children: The average number of weekend nights for reservations involving children was 1.
12. Most Common Room Type for Reservations Involving Children: The most common room type for reservations involving children was Room Type 1, with an average price of 123.12 units.
13. Market Segment with Highest Average Price per Room: The Online market segment generated the highest average price per room.

#### SQL Queries
The analysis was conducted using SQL queries to extract the above insights. This cab be reffered from the file.

### Conclusion
The analysis of the hotel reservation dataset provides valuable insights into guest preferences and booking trends. These insights can be used to optimize hotel operations, improve guest satisfaction, and develop data-driven strategies for the hotel industry.

### Repository Structure
Hotel_Reservation_Analysis.pptx: The PowerPoint presentation summarizing the analysis.
SQL_Queries.sql: A file containing all the SQL queries used for the analysis.
README.md: This file, providing an overview of the project.

### How to Use

#### Explore the SQL Queries:
Open the SQL_Queries.sql file to view the SQL queries used for the analysis.
You can run these queries on your own SQL database to replicate the analysis.

#### View the Presentation:
Open the Hotel_Reservation_Analysis.pptx file to view the detailed presentation of the analysis.
