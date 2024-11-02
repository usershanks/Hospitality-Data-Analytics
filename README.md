# Hospitality-Data-Analytics

## Project Overview
AtliQ Grands, with a portfolio of multiple five-star hotels in India, has a 20-year legacy in the hospitality industry. Recently, they have faced a decline in market share and revenue within the luxury/business hotel segment due to competitive strategies from rivals and suboptimal management decisions. To counteract this, the Managing Director of AtliQ Grands is looking to adopt "Business and Data Intelligence" as a strategic measure to reclaim their position in the market. Nevertheless, they lack an internal data analytics team to furnish the necessary insights.

## Tech stacks

- PowerBi Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)

## Business related terms

- **Revenue**: Total income generated from bookings.
- **Total Bookings**: Total number of bookings received.
- **Total Capacity**: Maximum number of bookings the hotel can accommodate.
- **Total Successful Bookings**: Total number of bookings that were completed successfully.
- **Occupancy %**: Percentage of available rooms that are occupied.
- **Average Rating**: Overall customer satisfaction rating of the hotel.
- **Total Cancelled Bookings**: Total number of bookings that were cancelled.
- **Cancellation %**: Percentage of total bookings that were cancelled.
- **Total Checked Out**: Total number of guests who have checked out.
- **Total No Show Bookings**: Total number of guests who did not show up for their reservation.
- **No Show Rate %**: Percentage of bookings that resulted in no shows.
- **Booking % by Platform**: Percentage of bookings made through various platforms (e.g., website, mobile app, third-party sites).
- **Booking % by Room Class**: Percentage of bookings categorized by room types (e.g., standard, deluxe, suite).
- **ADR**: Average Daily Rate - the average revenue earned per occupied room.
- **Realisation %**: Percentage of potential revenue actually realized from bookings.
- **RevPAR**: Revenue per Available Room - calculated by dividing total revenue by total available rooms.
- **DBRN**: Daily Booked Room Nights - total number of room nights booked for a given day.
- **DSRN**: Daily Sellable Room Nights - total number of room nights available for sale.
- **DURN**: Daily Utilized Room Nights - total number of room nights occupied for a given day.


### Questions to ask before starting with dashboard

- What is the objective of building this PowerBi dashboard?
- In what terms the success of this project will be measured?
- What will be time dead-line of the project?
- do the stakeholders expecting pre-view before the actual release?
- What are all the hopes stakeholders have out of this project?
- what are all fears the stakeholder have in terms of building this dashboard?
- Who are all will be using this dashboard and for what purpose?
- what are all expectation the stakeholders have, by the completion of this project?
- What can go wrong while building this project?
- what are all the resources/ data needed to build this dashboard?
- is there any inputs from stakeholders in terms of design and views of the dashboard?

  ### Dataset **Understanding.**
  Grasping the data available is essential before initiating any analysis. A comprehensive understanding of the data is important before embarking on the analytical process.

  Dimension table : It will have the static data like details of hotel, room type etc.

  Fact table : It will have the data about the bookings and transactions.

  ⁕ dim_date
    - day_type 
    - date
    - week mumber
  
  ⁕ dim_hotel
    - 8 different properties
    - unique id for each property
    - 2 categories business & luxury
    - name of cities in which the properties are located
      
   ⁕ dim_rooms
    - class of the room (Standard ,Elite ,Premium ,Presidential)
    - room id
  
  ⁕ fact_bookings
    - booking id
    -property id
    - booking date
    - check in date
    - check out date
    - room category
    - number of guests
    - booking platform
    - ratings given
    - booking_status
    - revenue generated
    - revenue realized
  
   ⁕ fact_aggregated_bookings
    - propert  id
    - check in date
    - room category
    - successful bookings
    - capacity
   
 ## Data Model

- Data modeling is crucial and serves as the foundation of a report. All visuals are constructed based on the data model.
- Inadequate data modeling can compromise the overall performance of a report.
- In this project, we have followed star schema modeling method.
  <img src="https://github.com/usershanks/Hospitality-Data-Analytics/blob/main/Data_model.png" class="center">
  
 ### Dashboard View
 ![hospitality_project](https://github.com/user-attachments/assets/6c4baf11-b7d2-47e9-a7d0-d04c0de01e65)

## Project Outcome

This report facilitates data-driven decision-making and assists in addressing the numerous 'why' questions that emerge from different scenarios.
 
 
