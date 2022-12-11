# Hotel Bookings Exploratory Data Analysis

## Objective

Objective of this analysis is perform EDA on the given dataset and draw useful conclusions about general trends in hotel bookings and how factors governing hotel bookings interact with each other.

## Dataset
This is a hotel bookings dataset. This dataset contains booking information for a city hotel and a resort hotel. It contains the following features.
```
- hotel: Name of hotel ( City or Resort)
- is_canceled: Whether the booking is canceled or not (0 for no canceled and 1 for canceled)
- lead_time: time (in days) between booking transaction and actual arrival.
- arrival_date_year: Year of arrival
- arrival_date_month: month of arrival
- arrival_date_week_number: week number of arrival date.
- arrival_date_day_of_month: Day of month of arrival date
- stays_in_weekend_nights: No. of weekend nights spent in a hotel
- stays_in_week_nights: No. of weeknights spent in a hotel
- adults: No. of adults in single booking record.
- children: No. of children in single booking record.
- babies: No. of babies in single booking record. 
- meal: Type of meal chosen 
- country: Country of origin of customers (as mentioned by them)
- market_segment: What segment via booking was made and for what purpose.
- distribution_channel: Via which medium booking was made.
- is_repeated_guest: Whether the customer has made any booking before(0 for No and 1 for 
                     Yes)
- previous_cancellations: No. of previous canceled bookings.
- previous_bookings_not_canceled: No. of previous non-canceled bookings.
- reserved_room_type: Room type reserved by a customer.
- assigned_room_type: Room type assigned to the customer.
- booking_changes: No. of booking changes done by customers
- deposit_type: Type of deposit at the time of making a booking (No deposit/ Refundable/ No refund)
- agent: Id of agent for booking
- company: Id of the company making a booking
- days_in_waiting_list: No. of days on waiting list.
- customer_type: Type of customer(Transient, Group, etc.)
- adr: Average Daily rate.
- required_car_parking_spaces: No. of car parking asked in booking
- total_of_special_requests: total no. of special request.
- reservation_status: Whether a customer has checked out or canceled,or not showed 
- reservation_status_date: Date of making reservation status.

- Total number of rows in data: 119390
- Total number of columns: 32

## Exploratory Data Analysis

Performed EDA and tried answering the following questions:
 - Which type of hotel is mostly prefered by the guests
 - Where do the Guests come from which country
 - What is the Percentage of repeated guests
 - What is the percentage distribution of "Customer Type"
 - Which type of food is mostly preferred by the guests
 - How does the price per day vary over the year
 - How Much do Guests pay for a room per Night
 - How Long people stay at the hotels
 - Per month Bookings and cancellation data of Resort Hotel
 - Per month Bookings and cancellation data of City Hotel
 - Month wise average per day rate of city hotel and resort hotel
 
 ## Key Insights:
 -  Around 60% bookings are for City hotel and 40% bookings are for Resort hotel, therefore City Hotel is busier than Resort hotel. Also the overall adr of City hotel is slightly higher than Resort hotel.
 - Mostly guests stay for less than 5 days in hotel and for longer stays Resort hotel is preferred.
 - Transient customer type is more whcih is 75.1 %. percentage of Booking associated by the Group is vey low.
 - The most preferred meal type by the guests is BB( Bed and Breakfast)
 - Both hotels have significantly higher booking cancellation rates and Repeated guests are very few which only 3.1 %.
 - Guests from all over the world are staying in these two hotels.50 % of the guests are from Portugal,Great Britain and France.
 - July- August are the most busier and profitable months for both of hotels.
 - For customers, generally the longer stays (more than 15 days) can result in better deals in terms of low adr.
 
 
 






