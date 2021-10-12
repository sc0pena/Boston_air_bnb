# Boston AirBNB
Overview/Purpose: Analyze Boston AirBNB listing data to determine:
1. Does list price (dependant variable) increase with number of bedrooms, number of bathrooms, number of beds?
2. Does price per night increase/decrease with specific Boston neighborhoods?
3. Are some rental room types (house, bedroom, condo, etc) in demand more (available less) than others? 

Background: 
Listing data collected from Kaggle (https://www.kaggle.com/airbnb/boston). Data is from 2009-2016. 

Methods/Models

Outcome 1 (pricing increase based on rooms and beds) correlation plotted on scatter diagram
- I thought about concatenating bedrooms + bathrooms + beds into 1 categorical variable and using pandas.get_dummies(), but the population is small (I don't think this was a   good approach)

Outcome 2 (pricing per neighborhood) displayed on a bar chart

Outcome 3 (rental room type demand) displayed on a bar chart

