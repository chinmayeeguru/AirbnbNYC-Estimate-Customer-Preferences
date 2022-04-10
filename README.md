# Introduction

Airbnb business has been negatively affected by the COVID-19 pandemic due to the unavoidable travel restrictions. For the past few months, it has seen a major decline in revenue in NY city. Now with the restrictions beginning to lifted, the business must ensure complete preparedness.


# Assumption

Number of reviews are considered as number of bookings made assuming they are equivalent to each other.

# Data Cleaning

- We have ignored the listings where -

•	number_of_reviews = 0, as this means number of booking is 0 as well.
•	availability_365 = 0, these properties are not available for booking.
•	last_review is blank, there are no booking history.
•	neighbourhood = Sea gate, very high price difference compared to the other properties in that area.

- Categorization of numerical variable : We have categorized the ‘Price’ variable to create bins.

# Visualizations and Insights

Exploratory data analysis was performed on the Airbnb data to identify trends and customer preferences based on area, room types and price per night. 
The graphs were plotted using Tableau to draw insights and recommendations.

##### 1. Customer Preferences of Property Types

![image](https://user-images.githubusercontent.com/103338455/162640807-476c3394-02db-44ff-923d-1a61a0387258.png)

- Out of the 3 types of properties, ‘Entire home/apt’ and ‘Private room’ types are preferred by Airbnb customers over ‘Shared rooms’ in NY city.
- Major portion of the listed properties in NYC are of type ‘Entire home/apt’ and ‘Private Room’ (97.5%).
- Shared rooms account for only 2.5% of the total listed properties.

##### 2. Customer Preferences for Room types in specific Areas

![image](https://user-images.githubusercontent.com/103338455/162640835-e51d4a06-8b7a-4d2f-98e6-db62b8056318.png)

- In Manhattan, more than 60% of the listings are of type Entire home/apt.
- In Queens and Bronx, more than 50% of the listed properties are of private room type.
- Shared room listings are not popular in all areas of NYC.

##### 3. Customer Preferences for Price

![image](https://user-images.githubusercontent.com/103338455/162640862-a8f496c3-1d18-4784-aa2c-40f7e00e8479.png)

- Low priced properties are high in demand in NYC. Specifically the ones within 50-100$ price per night range.
- High priced properties have a gradual decline in total number of listings and they have lower reviews/bookings.
- Around 23K listings in NYC are low priced ( < 250$ ).

##### 4. Customer Preferences for Stay Duration

![image](https://user-images.githubusercontent.com/103338455/162640878-9077e21a-217e-4822-9b84-007eff586900.png)

- Properties with minimum stay duration of below 5 nights have very high number of bookings.
- The demand gradually declines as the stay duration increases.
- There is also a visible demand for listings offering a minimum stay of 30 nights.


# Recommendations

##### 1. Target Hosts Offering Minimum Stay Duration

![image](https://user-images.githubusercontent.com/103338455/162640976-17c0d54b-3375-4103-ad49-ddfd7535c7e8.png)

- Properties that are low-priced and have least minimum stay duration are more preferred by customers. 
- Such hosts have also received the high number of bookings in the past.
- Hosts offering a 30- days stay are also preferred among travellers.

##### 2. Acquiring Premium  properties in Bronx and non-premium  properties in Manhattan

![image](https://user-images.githubusercontent.com/103338455/162640953-ce2ad4a7-2b21-426c-a038-0794098cf65d.png)

- Properties in Manhattan are more expensive than any other area while those in Bronx are the least expensive.
- Since Manhattan is already expensive as well as high in demand, business can acquire non-premium listings in this area to attract more bookings with the budget-friendly price.  
- Business can acquire premium properties in Bronx as the current rates are not so high yet.


##### 3. Customer preference for Entire apt or Private room stays intact

![image](https://user-images.githubusercontent.com/103338455/162640971-d7c409d1-c7bb-41a4-b183-469f7b02d2a4.png)

- Provided the social distancing norms in place, people are most likely to opt for entire apt/private rooms.
- The business can acquire properties that are of entire apt or private room types to meet the demand in post Covid period.

- Assuming that post COVID-19 people will prefer to book properties to stay for longer duration, the ones with minimum 30-night stays and with lower price can be acquired to grow business.






