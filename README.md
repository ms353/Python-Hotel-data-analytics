# Python-Hotel-data-analytics
The dataset covers up all the recorded hotel booking information. It consists of two kinds of hotels which are resort hotels and city hotels. In the dataset, we have 119,390 rows and 32 columns which gives a different kind of parameters. According to the variables, people can get information about details of booking processes such as lead time, most popular month to travel, deposit type, etc. Unfortunately, there is no price information to analyze the cheapest time to travel or booking. You may find the Hotel Booking data set by clicking here.
Hospitality Data Analysis: Unlocking Insights with Python
Welcome to the Hospitality Data Analysis project! This repository showcases a comprehensive analysis of a hospitality dataset using Python's powerful Pandas library. Our primary focus is on calculating the Occupancy Rate—a critical metric in the hotel industry—along with other insights that can help optimize hotel operations and improve customer satisfaction.

Project Description
About AtliQ Grands
AtliQ Grands is a premier hospitality chain operating across major cities in India, including Delhi, Mumbai, Hyderabad, and Bangalore. With over 20 years in the industry, AtliQ Grands offers a diverse portfolio of hotels such as AtliQ Seasons, AtliQ Exotica, AtliQ Bay, and AtliQ Palace. The company caters to a variety of guests through its luxury and business properties, with bookings available via multiple channels, including its own website, Makemytrip, Logstrip, Tripster, and offline methods.

Dataset Overview
The dataset provided contains rich information across multiple dimensions:

Hotels: Detailed data on properties, including their names, categories (Luxury, Business), and locations.
Rooms: Information on different room classes (Standard, Elite, Premium, Presidential).
Bookings: Data on bookings, including booking dates, check-in/check-out dates, number of guests, booking platforms, ratings, booking status, and revenue details.
Aggregated Bookings: A summary of bookings by property, room, and check-in date, including room capacity and booking success rates.
Key Metric: Occupancy Rate
The occupancy rate is the most crucial metric in the hotel industry, reflecting the percentage of available rooms that are occupied over a specific period. By analyzing this metric, we can gain valuable insights into hotel performance, peak booking times, and potential areas for improvement.

Project Objectives
Analyze Booking Trends: Understand booking patterns across different properties and room types.
Calculate Occupancy Rates: Determine the occupancy rates for various properties, providing insights into hotel performance.
Revenue Analysis: Evaluate revenue generated and realized from different booking platforms and room categories.
Platform Performance: Compare booking success rates across different platforms to identify the most effective channels.
Customer Ratings: Analyze customer feedback to understand satisfaction levels and areas for improvement.
Tools and Technologies Used
Python: The primary programming language used for data manipulation and analysis.
Pandas: A powerful library for data processing and analysis.
Jupyter Notebook: An interactive environment for writing code, visualizing data, and sharing insights.
Dataset Structure
dim_date: Contains date-related information.
dim_hotels: Contains property details, including property ID, name, category, and location.
dim_room: Contains room-related details, including room ID and class.
fact_aggregated_bookings: Contains aggregated booking data by property, room, and check-in date.
fact_bookings: Contains detailed booking information, including booking ID, dates, number of guests, platforms, ratings, and revenue.
Key Insights
Occupancy Rates: Identified peak and off-peak seasons, helping the management to strategize better pricing and marketing efforts.
Revenue Trends: Uncovered top-performing booking platforms and room categories.
Customer Ratings: Analyzed customer ratings to understand satisfaction levels and key drivers of positive experiences.
Contributing
We welcome contributions to improve this project! Feel free to fork the repository, make your changes, and submit a pull request.

Acknowledgments
Special thanks to the AtliQ Grands team for providing the dataset and to the open-source community for the incredible tools that made this analysis possible.

This README provides a detailed overview of your project, making it both informative and engaging for anyone interested in exploring hospitality data analysis.
You may find all variables with explanations below:

hotel: Hotel type(resort or city)
is_canceled: Whether a reservation was canceled or not. If it was canceled, it equals 1 or not 0
lead_time: Number of days that elapsed between the date of booking and arrival date to the hotel
arrival_date_year: The year that was arrived at the hotel
arrival_date_month: The month that was arrived at the hotel
arrival_date_week_number: The week number that has been arrived at the hotel
arrival_date_day_of_month: The number of the day in that month that has been arrived at the hotel
stays_in_weekend_nights: How many weekend nights were booked?
stays_in_week_nights: How many weekday nights were booked?
adults: How many adults booked a room?
children: How many children booked a room?
babies: How many babies booked?
meal: Type of meal booked. Categories are presented in standard hospitality meal packages: Undefined; SC = no meal package; BB = Bed & Breakfast; HB = Half board (breakfast and one other meal – usually dinner); FB = Full board (breakfast, lunch and dinner)
country: Guests are coming from which country?
market_segment: Marketing methods of booking. TA = Travel Agent, TO = Tour Operator.
distribution_channel: Channels of purchasing
is_repeated_guest: Repeated guest or not. If guest is repeated, it equals 1 or not 0
previous_cancellations: Number of previous cancellations
previous_bookings_not_canceled: Number of booking that have not previous cancellations
reserved_room_type: Code of room type reserved. Code of room type can not be defined due to anonymity.
assigned_room_type: Code of room type booked. Sometimes reserved room and assigned room may be different due to operational reason such as overbooking.
booking_changes: Number of changes
deposit_type: Types of deposit: No deposit, refundable, non-refundable
agent: ID of the travel agent. Thus, it is not useful variable.
company: Booking company but there are a lot of missing values.
days_in_waiting_list: Number of days the booking was on the waiting list before it was confirmed by the hotel
customer_type: Customer types include 4 categories which are Contract, Group, Transient, Transient-party. Contract means that there is an allotment or other contract between guest and hotel. Group as befits the name, a group booking. Transient, guest has not any contract or not related to any group, usual way. Transient-party is same to transient but it is associated to other transient bookings.
adr: Average daily rate equals total accommodation price divided by the number of nights.
required_car_parking_spaces: Number of car parking spaces required by the customer
total_of_special_requests: Number of special requests made by the customer suach as twin bed or speacial room
reservation_status: Last status of reservation; checked out, canceled, no-show(custumer did not check in but informed hotel why it is.
reservation_status_date: The date that shows the last status of the reservation.
