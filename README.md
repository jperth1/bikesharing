# bikesharing
Citi Bike data analysis

[link to dashboard] (https://public.tableau.com/app/profile/jeanette.perthel/viz/NYCCitiBikeStory_16241360771900/NYCCitibikeStory)

# Overview

The purpose of this analysis is to investigate data from the Citi Bike bike-sharing model in New York City to develop a plan for a similar bike-sharing system in Des Moines, Iowa. Using Citi Bike bike-sharing data from August 2019 this analysis uses Tableau to analyze important data points, pin-point patterns, and visualize critical results for potential application of this model in Des Moines, Iowa.  

### Resources
-	Data Source: 201908-citibike-tripdata.csv via citibikenyc.com
-	Software: Tableau Public 2021.1, Jupyter Notebook 6.1.4, Python 3.9.1

## Results 

The Citi Bike data analysis illustrated three important trends: 
-	The majority of Citi Bike users are subscribers
-	Men make up the majority of Citi Bike users
-	Citi Bikes are highly utilized during traditional commuting hours. 

These trends are consistently seen throughout the analysis and will be highlighted in the visualizations provided here.

### Citi Bike Customer Overview

In August 2019 2,344,224 rides were taken on Citi Bikes. 81.07% of Citi Bike users are subscribers while only 18.93% are customers. The majority of Citi Bike users being subscribers indicates that local New Yorkers regularly utilize the bike-sharing service, and most profits derive from annual subscription fees. Moreover, the 18.93% of users registered as customers can indicate these users either visitors to the city, or locals who use the bike-sharing service occasionally. More data would be needed to make a distinction on this point. Additionally, men make up 65.28% of Citi Bike users, woman make up 25.01% of Citi Bike users, and 9.62% of users are Unknown. Unknown users could include gender non-conforming individuals or individuals who choose to not disclose this demographic information. More data would be needed to make this distinction.

![Citi_Bike_Customer_Overview](/Resources/Citi_Bike_Customer_Overview.png)

![Citi_Bike_Gender_Breakdown](/Resources/Citi_Bike_Gender_Breakdown.png)



### Citi Bike Trips during the Weekday by Hour

This visualization indicates that majority of Citi Bike trips taking Monday through Friday are taken during typical commuter hours, between 7AM and 9AM and 5PM and 7PM. Morning ridership peaks around 8AM Monday through Friday between approximately 27,000 and a little over 36,000 rides. Evening ridership peak around 6PM Monday through Friday between approximately 21,000 and 45,000 rides. On Saturday and Sunday the most popular time to use a Citi Bike is between 12PM and 5PM with Saturday peaking at 12PM with a little over 31,000 rides and Sunday’s peak at 4PM with a little over 23,000 rides. This visualization highlights the trend that Citi Bikes are highly utilized during traditional commuter hours.

![Trips_per_Weekday_per_hour](/Resources/Trips_per_Weekday_per_hour.png)

### Citi Bike Trips by Gender during the Weekday by Hour

The previous visualization if further broken down to investigate the role gender plays in trips throughout the week by hour. 

Men make up a larger proportion of Citi Bike user during the weekday and are more than twice as likely to use them during typical commuter hours than woman. The most popular time for a man to use a Citi Bike is on Thursday between 6PM and 7PM, with a total of 36,749 trips. 

Women make up a smaller proportion of Citi Bike users and are more likely to use them during commute hours. The most popular time for a woman to use a Citi Bike is on Thursday between 6PM and 7PM, with a total of 11,336 trips. 

Among unknown users, the most popular day to use Citi Bike is Saturday between 10AM and 7PM.

Interestingly These is a drop in trips for both men and women on Wednesdays between 5PM and 7PM. This visualization highlights two trends: men make up the majority of Citi Bike user, and Citi Bikes are highly utilized during traditional commuting hours. 

![Trips_by_Gender_Weekday_per_Hour](/Resources/Trips_by_Gender_Weekday_per_Hour.png)

### User-type Trips by Gender and Weekday

This visualization breaks down the relationship between ridership, user type, gender, and weekday. This visualization highlights the trends that subscribers make up the majority of Citi Bike users and men make up the majority of Citi Bike users.

Men make up the majority of Citi Bike subscribers, and they take the majority of their trips Monday to Saturday, with Thursday being the most popular day at 259,316 rides, and Wednesday being the least popular day at 173,110 rides.

Women Citi Bike subscribers take the majority of trips Thursday to Sunday with the most popular day being Thursday at 81,281 rides. 
Unknown Citi Bike subscribers also take the majority of trips on Thursdays through Saturday with Thursday being the most popular day at 6,082 rides. Among men, woman, and unknown subscribers Thursday is the most popular day to use a Citi Bike.

Among Customer users, Males and Unknown users are more likely to utilize Citi Bikes. Unknown users show the highest ridership on Saturday with 55,375 rides. For all customers the most popular day to use Citi Bikes is on Saturday.


![User_Trips_by_Gender_by_Weekday](/Resources/User_Trips_by_Gender_by_Weekday.png)

### Checkout Times for Users

This visualization illustrates the duration of trips, or how long a Citi Bike is checkout by a user. Checkout times peak at 5 minutes with 146,752 rides. After 5 minutes the number of rides decreases about 10,000 every additional minute.

![Checkout_Times_for_Users](/Resources/Checkout_Times_for_Users.png)

### Checkout Times by Gender 

This visualization illustrates the relationship between gender and checkout times. This visualization also compliments the trend that men make up the majority of Citi Bike users.

Among men, women and unknown users, trip times peak between 5 to 11 minutes with men representing a significantly larger portion of trips which peaks at 5 minutes with 108,087 rides. Women’s check out time peaks at 6 minutes with 34,151 rides, and unknown user’s checkout time peaks at 11 minutes with 7,389 rides. 

![Checkout_Times_by_Gender](/Resources/Checkout_Times_by_Gender.png)


## Summary

Overall, the analysis of the Citi Bike bike-sharing data highlights three consistent trends: 
-	The majority of Citi Bike users are subscribers
-	Men make up the majority of Citi Bike users
-	Citi Bikes are highly utilized during traditional commuting hours. 

These trends provide valuable insight for model adaptation in Des Moines, Iowa. For successful implementation further research should be conducted on the demographic make-up Des Moines, and marketing strategies should be focused on male ridership. 

### Additional Chart Recommendations

For further research and analysis, it is recommended to explore the relationship between ridership numbers, checkout start locations, gender. This chart could provide more insight into where users are checking out bikes the most and provide insight for Des Moines when planning bike station location. 

Additionally, it is recommended to explore the relationship between ridership numbers, gender, and birth year. This could provide more insight into demographic trains and further pinpoint demographic groups more likely or less likely to utilize the bike-sharing service. 
