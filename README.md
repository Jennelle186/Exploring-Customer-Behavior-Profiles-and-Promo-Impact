# Exploring-Customer-Behavior-Profiles-and-Promo-Impact
Exploring Customer Behavior, Profiles, and Promo Impact: A Comprehensive Analysis of Hey You App Data from January 2021 - May 2021

This repository contains code for analyzing customer, order, and vendor activities in the event of promos. The analysis includes generating visualizations such as bar graphs, and pie charts, and calculating percentages.

# Data Description
  Trans_date - Transaction Date
  
  Trans_hour - Transaction Hour
  
  Customers - Number of unique customers active/ordering
  
  Vendors - Number of unique vendors active/ordering
  
  Orders - Number of unique orders through the app
  
  Amount - Total processed order amount in Australian dollars
  
  Promo_count - Number of orders with promos
  
  Promo_amount - Total discounts / promos given
  
  Android - Number of unique customers who used Android Device
  
  GCF - Number of unique customers who used Google Food Ordering
  
  Macintosh - Number of unique customers who used Mac
  
  Tablet - Number of unique customers who used iPad/iPod
  
  Windows - Number of unique customers who used Windows Device
  
  X11 - Number of unique customers who used Linux / CrOS Device
  
  iPhone - Number of unique customers who used iPhone
  
  Blacklisted - Number of unique customers blacklisted (note of course at the time of
  ordering they weren’t blacklisted yet, but eventually, they were)
  
  Not Blacklisted - Number of unique customers who are not blacklisted


#Analysis
The analysis covers the following steps:

1. Visualizing the customer, order, and vendor  activity per month by the device using a line plot.
2. Calculating the total count of each device and plotting a bar graph to display the device usage by customers.
3. Determining the top 3 devices used by customers and creating a pie chart to represent their usage percentages.
4. Calculating the number of blacklisted and not blacklisted customers and determining their percentages.

#Usage
Usage
To run the analysis, follow these steps:

1. Ensure you have the required dependencies installed (e.g., pandas, matplotlib).
2. Import the necessary libraries and load the dataset.
3. Apply the provided code snippets to perform the desired analysis and visualize the results.

#Results
The analysis provides insights into customer, vendor, and order activity in the event of a promo. The visualizations generated include line plots, bar graphs, and pie charts, which help in understanding trends and proportions within the dataset. 
  
