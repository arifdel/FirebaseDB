It is a Image recommendation system based on user's calorific experience

1. Firstly we take the user's calorific value.
2. Based on the recent food taken by the user. We take its calorific value and make a range around it.
3. For that range we make a query to our firebase database for the food items having calorific value in range.
4. Lastly we recommend those items to users as they have similar Calorific value.
