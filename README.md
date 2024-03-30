# Splendor_Hotel_Group_Booking_Analysis
# Analyzing data in Power Query and Power BI
# Introduction
This is a personal related project. I analyzed a dataset from Splendor Hotel Group booking data. The task involves a thorough analysis of a comprehensive dataset featuring intricate details of bookings, guest demographics, distribution channels and financial metrics. The dataset contained 199,390 rows and 17 columns. The following variables are included in the detailed data file:

a) Hotel: Type or name of the hotel within the Splendor Hotel Group.

b) Booking Date: The date when the booking was made.

c) Arrival Date: The date when the guests are scheduled to arrive.

d) Lead Time: The number of days between the booking date and arrival date.

e) Distribution Channel: The channel through which the booking was made (e.g., Direct, Onliine Travel Agent).

f) Country: Country of origin of the guests.

g) Revenue: The revenue generated from the booking.

The aim of this research is to extract meaningful insights that will not only inform operational improvements but also contribute to the overall success of Splendor Hotel Group in delivering unparalled hospitality.

# Data Profiling, Data Modeling and Data Transformation 
After importing my data into power query, I checked for the validity of my data using column distribution, quality and profiling. I also made sure my columns were in the rigth data type. The calendar DAX function was used to construct a calendar table based on the arrival and booking dates. For efficient analysis, the tables were then combined with the fact table. THe switch DAX function was used to group the lead time into four categories to obtain the lead time contributing significantly to revenue and the cancellation rate. 

# Data Analysis and Visualizations 

![rev_rev_loss](https://github.com/OlotoDamilola/Splendor_Hotel_Group_Booking_Analysis/assets/109422215/c651b60b-a3af-4ad0-9c91-8509fa7be204)

For the years 2015 - 2017 revenue reached its highest peak in August 2017 of $1,985,171 also with its highest of $1,363,454 due to cancellation. In 2016, it was seen that revenue started to rise at the start of the second quarter with the majority of the revenue coming in July - September. At $291,521, January 2016 brought in the least amount of money. November 2015 recorded the least revenue loss of $99,947 with a total revenue of $363,041.




