<div id="top"></div>

<h3 align="center">Hotel Bookings Analysis</h3>

  <p align="center">
    Data Analytics Bootcamp final project that explores the use of Python in analysing hospitality data
    <br />

  </p>
</div>


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#built-with">Built With</a></li>
    <li><a href="#data-source">Data Source</a></li>
    <li><a href="#project-components">Project components</a></li>
    <li><a href="#dataset-summary">Dataset summary</a></li>
    <li><a href="#objective">Objective</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#list-of-original-variables"> List of original variables</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
The project was the final stage of the Data Analytics bootcamp I finished in December 2021. It explores a vast dataset found on Kaggle which compares various booking information between two hotels: a city hotel and a resort hotel. It includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things - a total of 32 variables, however, during the first part of the data exploration some variables were deemed redundant and eliminated, and a number of new calculated and categorical variables were created.

The basic motivation for choosing this dataset was to explore the use of Python for data analysis in the hospitality industry, in which I currently work.

<p align="right">(<a href="#top">back to top</a>)</p>



## Built With

* [Python]
  * Pandas
  * NumPy
  * Plotly
  
  
<p align="right">(<a href="#top">back to top</a>)</p>

## Data Source

The dataset used in this project can be found on Kaggle under the following link:

https://www.kaggle.com/jessemostipak/hotel-booking-demand

<p align="right">(<a href="#top">back to top</a>)</p>



## Project components

Github Link: [Project Repository](https://github.com/martamalecka/hotel-bookings-analysis)

PROJECT PART 1 - [Data Cleaning and Feature Engineering](https://github.com/martamalecka/hotel-bookings-analysis/blob/main/Hotel%20Bookings%20Analysis%20-%20Part%201%20-%20Data%20Cleaning%2C%20Feature%20Engineering.ipynb)

PROJECT PART 2 - [EDA and Data Visualization](https://github.com/martamalecka/hotel-bookings-analysis/blob/main/Hotel%20Bookings%20Analysis%20-%20Part%202%20-%20EDA%20and%20Data%20Visualisation.ipynb)

[PPT presentation discussing the results](https://github.com/martamalecka/hotel-bookings-analysis/blob/main/hotel%20bookings%20analysis.pdf)

[YouTube presentation during the Bootcamp´s Demo Day - see from min. 26:00 to min. 39:00](https://www.youtube.com/watch?v=_a42n1FRhUY&t=2359s)

<p align="right">(<a href="#top">back to top</a>)</p>

## Dataset summary

* This data set contains a single file which compares various booking information between two hotels: a city hotel and a resort hotel.
* Includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. A total of 32 variables.
* All personally identifying information has been removed from the data.
* Both hotels are assumed to be located in Portugal, however their exact location and name are unknown.
* The dataset contains a total of 119390 entries.

<p align="right">(<a href="#top">back to top</a>)</p>

## Objective

The objective of this project is to answer the following 3 questions for each hotel of the dataset:

* What is the seasonality for each hotel and what are the top performing months?
* What are the top countries in terms of bookings and/or revenue?
* What´s the most frequent guest type for each hotel?

<p align="right">(<a href="#top">back to top</a>)</p>


## Roadmap

- [ ] Part 1 - Data Cleaning and Feature Engineering
- [ ] Part 2 - EDA and Data Visualisation

<p align="right">(<a href="#top">back to top</a>)</p>


## List of original variables: 

* hotel - Hotel (H1 = Resort Hotel or H2 = City Hotel)
* is_canceled - Value indicating if the booking was canceled (1) or not (0)
* lead_time - Number of days that elapsed between the entering date of the booking into the PMS and the arrival date
* arrival_date_year - Year of arrival date
* arrival_date_month - Month of arrival date
* arrival_date_week_number - Week number of year for arrival date
* arrival_date_day_of_month - Day of arrival date
* stays_in_weekend_nights - Number of weekend nights (Saturday or Sunday) the guest stayed or booked to stay at the hotel
* stays_in_week_nights - Number of week nights (Monday to Friday) the guest stayed or booked to stay at the hotel
* adults - Number of adults
* children - Number of children
* babies - Number of babies
* meal - Type of meal booked. Categories are presented in standard hospitality meal packages: Undefined/SC – no meal package; BB – Bed & Breakfast; HB – Half board (breakfast and one other meal – usually dinner); FB – Full board (breakfast, lunch and dinner)
* country - Country of origin. Categories are represented in the ISO 3155–3:2013 format
* market_segment - Market segment designation. In categories, the term “TA” means “Travel Agents” and “TO” means “Tour Operators”
* distribution_channel - Booking distribution channel. The term “TA” means “Travel Agents” and “TO” means “Tour Operators”
* is_repeated_guest - Value indicating if the booking name was from a repeated guest (1) or not (0)
* previous_cancellations - Number of previous bookings that were cancelled by the customer prior to the current booking
* previous_bookings_not_canceled - Number of previous bookings not cancelled by the customer prior to the current booking
* reserved_room_type - Code of room type reserved. Code is presented instead of designation for anonymity reasons.
* assigned_room_type - Code for the type of room assigned to the booking. Sometimes the assigned room type differs from the reserved room type due to hotel operation reasons (e.g. overbooking) or by customer request. Code is presented instead of designation for anonymity reasons.
* booking_changes - Number of changes/amendments made to the booking from the moment the booking was entered on the PMS until the moment of check-in or cancellation
* deposit_type - Indication on if the customer made a deposit to guarantee the booking. This variable can assume three categories: No Deposit – no deposit was made; Non Refund – a deposit was made in the value of the total stay cost; Refundable – a deposit was made with a value under the total cost of stay.
* agent - ID of the travel agency that made the booking
* company - ID of the company/entity that made the booking or responsible for paying the booking. ID is presented instead of designation for anonymity reasons
* days_in_waiting_list - Number of days the booking was in the waiting list before it was confirmed to the customer
* customer_type - Type of booking, assuming one of four categories: Contract - when the booking has an allotment or other type of contract associated to it; Group – when the booking is associated to a group; Transient – when the booking is not part of a group or contract, and is not associated to other transient booking; Transient-party – when the booking is transient, but is associated to at least other transient booking
* adr - Average Daily Rate as defined by dividing the sum of all lodging transactions by the total number of staying nights
* required_car_parking_spaces - Number of car parking spaces required by the customer
* total_of_special_requests - Number of special requests made by the customer (e.g. twin bed or high floor)
* reservation_status - Reservation last status, assuming one of three categories: Canceled – booking was canceled by the customer; Check-Out – customer has checked in but already departed; No-Show – customer did not check-in and did inform the hotel of the reason why
* reservation_status_date - Date at which the last status was set. This variable can be used in conjunction with the ReservationStatus to understand when was the booking canceled or when did the customer checked-out of the hotel


<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

If you wish any information on the project feel free to contact me on LinkedIn or by email:

Linkedin: (https://www.linkedin.com/in/maleckamar/) 

Email: maleckamar@gmail.com


<p align="right">(<a href="#top">back to top</a>)</p>


