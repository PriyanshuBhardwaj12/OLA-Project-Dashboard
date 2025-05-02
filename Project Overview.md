OLA – Power BI Dashboard Project
Note: This dashboard is based on assumed data and not real-time OLA data.

Project Overview
This multi-page Power BI dashboard visualizes various aspects of an assumed dataset for OLA. It consists of five pages, each dedicated to a specific analysis area:

Overall

Vehicle Type

Revenue

Cancellation

Ratings

1. Overall Page
Provides a high-level summary of bookings and ride volume.

Pie Chart: Displays booking status breakdown (status vs. count of Booking ID).

Line Chart: Shows ride volume trend over time (Date vs. count of Booking ID).

Cards:

Total Bookings: Count of all booking IDs.

Total Booking Value: Sum of all booking values.

Slicer: Filters all visuals by Date.

2. Vehicle Type Page
Focuses on bookings and distance metrics categorized by vehicle types.

Cards:

Total Booking Value

Successful Booking Value

Average Distance Travelled

Total Distance Travelled

Slicer: Filters the data by Date.

3. Revenue Page
Analyzes revenue and ride distance distribution.

Stacked Column Charts:

Revenue by Payment Method: Shows payment methods vs. sum of booking value.

Ride Distribution Day-wise: Date vs. total ride distance.

Table: Displays Top 5 Customers based on the number of bookings.

Slicer: Filters all data by Date.

4. Cancellation Page
Examines ride cancellations from both customer and driver perspectives.

Pie Charts:

Canceled Rides by Customers: Count of canceled rides by customers.

Canceled Rides by Drivers: Count of canceled rides by drivers.

Cards:

Total Bookings

Successful Bookings

Canceled Bookings

Cancellation Rate (calculated via DAX as a percentage)

Slicer: Filters the data by Date.

5. Ratings Page
Displays user and driver ratings data.

Cards: Average or total rating values for Drivers and Customers.

Slicer: Allows filtering by Date.

Summary
This dashboard utilizes a variety of Power BI visual elements such as cards, pie charts, line charts, stacked column charts, tables, and slicers to offer a comprehensive analysis of assumed OLA booking and performance data. The dashboard is designed to provide insights across booking trends, revenue, ride cancellations, and user ratings, making it a useful tool for operational and strategic decision-making.

