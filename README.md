# Hotel-Data-analyst-project

## Overview 
This project invloves analyzing a hotel dataset using python and the pandas library. The dataset includes information about hotel bookings, room details, property information and aggregated booking statistics. The goal is to clean, transform and analyze the data to derive meaningful insights about occupancy and revenue. 

## Features 
- Data cleaning to handle outliers and missing values
- data transformation to create new mertics
- Insightful analysis to answer business related questions
- Visualization of trends in hotel bookings and revenue

## Dataset Descrption 
The Project uses the following datasets:
1. **Fact_Bookings** :  Contains details about bookings, including date, number of guests, revenue, and booking status
2. **Dim_Date** : Provides date - related dimensions like day type and week number.
3. **Dim_Hotel** : Included hotel preperty details such as city and category
4. **Dim_Room** : contains room level information like room class
5. **Fact_Aggregated_Booking** : Aggregated Bookings data by preperty, room category and date.

### **Schema Highlights**
- **Fact_Bookings**:
`booking_id`,`preperty_id`,`booking_date`,`check_in_date`,`checkout_date`,`no_guests`,`room_category`,`booking_platform`,`rating_given`,`booking_status`,`revenue_generated`,`revenue_realized`
- **Dim_Dates**:
`date`,`mmm yy`,`week no`,`day_type`
- **Dim_Hotels**:
`preperty_id`,`prepoerty_name`,`category`,`city`
- **Dim_Rooms**:
`room_id`,`room_class`
- **Fact_Aggregated_Bookings**:
`preperty_id`,`check_in_date`,`room_category`,`successful_bookings`,`capacity`

## Business questions 
Check out the business questions [here](Python_question.txt)
