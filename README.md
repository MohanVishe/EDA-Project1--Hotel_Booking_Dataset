# Hotel Booking Dataset Exploratory Data Analysis (EDA)

## Introduction

![image](https://github.com/MohanVishe/EDA-Project1--Hotel_Booking_Dataset/assets/114080820/bfd6f165-d068-49f6-884a-ed9e5f9b1602)


Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions!

This data set contains booking information for a city hotel and a resort hotel and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.

## Features Information

- **Hotel**: Type of hotel (Resort Hotel or City Hotel)
- **Is_canceled**: Whether the booking was canceled (0 for Not canceled, 1 for Canceled)
- **Lead_time**: Number of days between the date of booking and arrival date
- **Arrival_date_year**: Year of arrival from 2015 to 2017
- **Arrival_date_month**: Month of arrival from Jan to Dec
- **Arrival_date_week_number**: Week number of year from 1 to 53
- **Arrival_date_day_of_month**: Day of arrival date
- **Stays_in_weekend_nights**: Number of Saturday/Sunday nights stayed or booked to stay at the hotel
- **Stays_in_week_nights**: Number of Monday to Friday nights stayed or booked to stay at the hotel
- And more...

## Overview of Data

The dataset has 119,390 rows and 32 columns.

## Data Pre-Processing

### Handling Missing/Null Values
- Removed columns "company" and "agent" due to considerable missing values.
- Filled null values in the "children" column with the rounded median value.
- Removed rows containing missing country values.

### Handling Data Types
- Converted the "children" column from float to integer.

## Exploratory Data Analysis (EDA)

### Analysis Tasks
1. Analysis of bookings in different types of hotels
2. Annual number and percentage of arriving visitors
3. Booking distribution for each year separated by hotel type (not canceled)
4. Length of stay in hotels
5. Dominating meal bookings
6. Months with the highest and lowest number of bookings
7. Correlation matrix for important numerical features
8. Relation between Average Daily Rate (ADR) and number of people
9. Top booking countries
10. Time-based count of bookings
11. Car parking space requirements
12. Target sectors for advertisement
13. Months with cheaper booking rates

## Conclusion

- City hotels have a higher number of bookings.
- Bookings peaked in 2016 but declined in 2017.
- About 1/3 of bookings were canceled.
- The countries "PRI", "GBR", and "FRA" had the highest number of bookings.
- ADR tends to increase with the increase in the number of people.
- November to January has cheaper booking rates.
The majority of distribution channels and market segments involve travel agencies, suggesting a focus on targeting them.

The EDA provides valuable insights for understanding booking trends and informing decision-making processes in the hospitality industry. Further analysis and modeling can be conducted based on these findings to optimize hotel management strategies.
