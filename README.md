# Hospitality-Data-Analytics

## Project Overview
AtliQ Grands, with a portfolio of multiple five-star hotels in India, has a 20-year legacy in the hospitality industry. Recently, they have faced a decline in market share and revenue within the luxury/business hotel segment due to competitive strategies from rivals and suboptimal management decisions. To counteract this, the Managing Director of AtliQ Grands is looking to adopt "Business and Data Intelligence" as a strategic measure to reclaim their position in the market. Nevertheless, they lack an internal data analytics team to furnish the necessary insights.

## Tech stacks

- PowerBi Desktop
- Excel
- DAX language
- DAX studio (for optimizing the report)

## Business related terms

-Revenue
-Total Bookings
-Total Capacity
-Total Succesful Bookings
-Occupancy %
-Average Rating
-Total cancelled bookings
-Cancellation %
-Total Checked Out
-Total no show bookings
-No Show rate %
-Booking % by Platform
-Booking % by Room class
-ADR --> Average Daily Rate 
-Realisation %
-RevPAR --> Revenue per Available Room
-DBRN --> Daily Booked Room Nights
-DSRN --> Daily Sellable Room Nights
-DURN --> Daily Utilized Room Nights

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
      → day_type
      → date
      → week mumber
  
  ⁕ dim_hotel
      → 8 different properties
      → unique id for each property
      → 2 categories business & luxury
      → name of cities in which the properties are located
      
   ⁕ dim_rooms
      → class of the room (Standard ,Elite ,Premium ,Presidential)
      → room id
  
  ⁕ fact_bookings
      → booking id
      → property id
      → booking date
      → check in date
      → check out date
      → room category
      → number of guests
      → booking platform
      → ratings given
      → booking_status
      → revenue generated
      → revenue realized
  
   ⁕ fact_aggregated_bookings
      → propert  id
      → check in date
      → room category
      → successful bookings
      → capacity

 ## Data Model

- Data modeling is crucial and serves as the foundation of a report. All visuals are constructed based on the data model.
- Inadequate data modeling can compromise the overall performance of a report.
- In this project, we have followed star schema modeling method.
  <img src="https://github.com/usershanks/Hospitality-Data-Analytics/blob/main/Data_model.png" class="center">
