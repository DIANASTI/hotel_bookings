## Intro
----------------------
This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.

All personally identifying information has been removed from the data.

We analyzed thsi dataset and tried to find interesting observations using data analytics technics.

## Dataset
-------------------
- The Hotel booking demand dataset consists of 119390 hotel reservations, based on real data, with the following features:
- Hotel - what type fo hotel it is : City or Resort
- IsCanceled - Value indicating if the booking was canceled (1) or not (0)
- LeadTime - Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
- ArrivalDateDayOfMonth - Day of the month of the arrival date
- ArrivalDateMonth - Month of arrival date with 12 categories: “January” to “December”
- ArrivalDateWeekNumber - Week number of the arrival date
- ArrivalDateYear - Year of arrival date
- StaysInWeekendNights- Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
- StaysInWeekNights - Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
- Adults -  Number of adults
- Children - Number of children
- Babies - Number of babies
- MarketSegment - Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
- Meal- Type of meal booked. Categories are presented in standard hospitality meal packages:Undefined/SC – no meal package;BB – Bed & Breakfast;HB – Half board (breakfast and one other meal – usually dinner);FB – Full board (breakfast, lunch and dinner)
- Country - Country of origin. Categories are represented in the ISO 3155–3:2013 format
- DistributionChannel - Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”
- IsRepeatedGuest - Value indicating if the booking name was from a repeated guest (1) or not (0)
- PreviousBookingsNotCanceled - Number of previous bookings not cancelled by the customer prior to the current booking
- PreviousCancellations - Number of previous bookings that were cancelled by the customer prior to the current booking
- ReservedRoomType - Code of room type reserved. Code is presented instead of designation for anonymity reasons
- AssignedRoomType - Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons
- BookingChanges - Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation
- Deposit_type - "No deposit"
- Agent - ID of the travel agency that made the bookinga
- Company - ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons
- DaysInWaitingList - Number of days the booking was in the waiting list before it was confirmed to the customer
- CustomerType - Type of booking, assuming one of four categories:
- ADR - Average Daily Rate as defined 
- RequiredCardParkingSpaces - Number of car parking spaces required by the customer
- ReservationStatus - Reservation last status, assuming one of three categories:
- ReservationStatusDate - Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel
- TotalOfSpecialRequests - Number of special requests made by the customer (e.g. twin bed or high floor)

## Links
---------------------
https://medium.com/@ndiviana/how-to-save-money-when-booking-a-hotel-eec907f15803

## Attachments
----------------------
- hotel_bookings.csv - booking confirmation data set 
- Hotel_Bookings.ipynb - a Jupyter notebook showing data set loading, cleaning, investigation how diffrent feature may affect a booking rate 

## Acknowledgements:
----------------------
The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.
The data was downloaded and cleaned by Thomas Mock and Antoine Bichat for #TidyTuesday during the week of February 11th, 2020.

- License: Attribution 4.0 International (CC BY 4.0)

For more details, please refer to   https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand?resource=download
