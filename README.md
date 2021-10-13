# Boston AirBNB
Overview/Purpose: Analyze Boston AirBNB listing data to answer 3 questions:
1. Does list price (dependant variable) increase with number of bedrooms, number of bathrooms, number of beds?
2. Which neighborhoods in Boston have higher priced listings (categorize highest to lowest)?
3. Are some rental types (house, room, etc) in demand more (IE less available) than other rental types? 

Background: 
Listing data collected from Kaggle (https://www.kaggle.com/airbnb/boston). Data is from 2009-2016. 

Methods/Models

For question 1 (pricing increase based on rooms and beds) correlation plotted on scatter diagram + statistics provided
- I thought about concatenating bedrooms + bathrooms + beds into 1 categorical variable and using pandas.get_dummies(), but the population is small (I don't think this was a   good approach)

For question 2 (neighborhood pricing) displayed on a bar chart; show descriptive statistics

For question 3 (rental type demand based on 90 day availability) show inferential and descriptive statistics

