# Assingment-

## Dataset 

: user details,  Cooking session , order details

##Dataset description 
User Information
•	Details like user ID, name, age, location, contact information, and registration date.
Session Details
•	Information about cooking sessions, including session IDs, start and end times, durations, dishes prepared, and session ratings.
Order Information
•	Data on orders placed by users, such as order ID, date, status, amount, and the total number of orders.
Ratings and Preferences
•	Ratings for both the cooking session and the food prepared, as well as the user's favorite meal and time of day preferences.
## Exploraatory data analysis( EDA)
Data Description and EDA Summary
•	Dataset: Contains 22 columns and 16 rows after merging, detailing user behavior, cooking sessions, and orders.
•	Null Values: Only the Rating column has 2 null values, which were retained.
•	Data Types: Predominantly object, with numeric columns like Age, Duration (mins), Session Rating, and Amount (USD).

Questionnaire
1.	What is the relationship between cooking sessions and user orders?
2.	Which dishes are the most popular?
3.	How do demographics (e.g., age, location) influence user behavior?


1.
•  Relationship Between Duration and Amount:
•	A positive correlation was observed between the cooking session duration and the order amount.
•	A scatter plot was created to visualize this relationship.
•  Relationship Between Session Rating and Food Rating:
•	No significant correlation was found between session ratings and food ratings.
•	The analysis excluded null values in the Rating column for this comparison.
2 
Dish Popularity Analysis
1.	Most Popular Dishes:
o	Spaghetti and Grilled Chicken are the top Popular among users.
2.	Moderately Popular Dishes:
o	Caesar Salad, Pancakes, and Veggie Burger show moderate demand.
3.	Least Popular Dish:
o	Oatmeal is the least ordered dish.
3
	Meal Type Popularity
•	Most Popular: Dinner
•	Moderate: Lunch
•	Least Popular: Breakfast

	Age vs dish name

Spaghetti: Min 26, Max 38, Median 31
•	Typically ordered by users aged between 26 to 38 years, with a median age of 31.
•  Pancakes: Min 28, Max 42, Median 35
•	Orders span ages 28 to 42, with a median age of 35, indicating a slightly older user group.
•  Grilled Chicken: Min 27, Max 38, Median 29
•	Ordered by users aged between 27 to 38, with a median age of 29, suggesting a younger audience.
•  Caesar Salad: Min 26, Max 35, Median 30
•	Users range from 26 to 35 years, with a median age of 30, indicating a relatively younger group.
•  Oatmeal: Min 35 (Age)
•	This dish is ordered only by users aged 35 or older, indicating it appeals to an older demographic.
•  Veggie Burger: Min 31, Max 40, Median 37
•	Ordered by users between 31 and 40 years, with a median age of 37, suggesting a middle-aged audience

Location Analysis
•	Key Locations: Mostly from New York, Chicago, and Los Angeles.
##Conclusion
The analysis provides valuable insights into user preferences and behavior:
1.	Duration & Spending: Longer cooking sessions correlate with higher order amounts.
2.	Dish Popularity: Spaghetti and Grilled Chicken are the most popular, while Oatmeal is the least ordered.
3.	Meal Time Preferences: Dinner is the most popular meal time, followed by lunch and breakfast.
4.	Age & Preferences: Oatmeal appeals to older users, while Pancakes are preferred by those in their 30s.
5.	Location Trends: Users are primarily from urban areas like New York, Chicago, and Los Angeles, reflecting diverse meal preferences.







