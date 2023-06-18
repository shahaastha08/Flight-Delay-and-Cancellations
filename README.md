# Flight-Delay-and-Cancellations
A Tableau Dashboard to get insights from the 2015 Flight Dataset in the US

## Introduction

In this Dashboard, I present an in-depth analysis of flight delays and cancellations, utilizing the powerful data visualization software, Tableau. By leveraging Tableau's robust capabilities, I have transformed raw data into a visually appealing and interactive dashboard, enabling us to unravel intricate patterns, trends, and insights within the vast realm of flight-related information. This dashboard serves as a visual journey, showcasing my skills in data exploration, visualization design, and storytelling, as well as my ability to extract meaningful insights from raw data. 

This dataset consists of 2015 flight delays and cancellations and information on the various reasons for the delay like weather related delay, airline delay, departure delay, in-flight delay,and so on. In 2015 there are lots of flight delays in the United States. Nearly one third of all flights in our data set have delays.

This Tableau Dashboard provides a summary of the data, and provides insights into the reasons and patterns observed in delayed and canceled flights.

## About Dataset

This dataset is taken from Kaggle - https://www.kaggle.com/usdot/flight-delays/data

The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics tracks the on-time performance of domestic flights operated by large air carriers. Summary information on the number of on-time, delayed, canceled, and diverted flights is published in DOT's monthly Air Travel Consumer Report and in this dataset of 2015 flight delays and cancellations.

## Summary
![Summary](https://github.com/shahaastha08/Flight-Delay-and-Cancellations/assets/37699951/5afd01d3-e3a0-49c7-8040-396f8d9bd268)

https://public.tableau.com/views/FlightDelayandCancellations_16865293067240/Summary?:language=en-US&:display_count=n&:origin=viz_share_link

From the Summary, we can see that there are a total of 14 airlines out of which Southwest Airlines has the maximum number of flights, followed by Delta Airlines, and Atlantic Southeast Airlines.

Also in terms of average air time and average distance traveled, the top 5 airlines are Virgin America, United Airlines, Alaska Airlines, JetBlue Airways, and American Airlines. So, we can conclude that the airlines with maximum number of flights like Southwest Airlines and Delta Airlines have shorter distance flights, while airlines like Virgin America, United Airlines, Alaska, etc have less number of flights but longer ones. This might be helpful in determining more information about delays and cancellations.

## Delay
![Delay (1)](https://github.com/shahaastha08/Flight-Delay-and-Cancellations/assets/37699951/5e93a02b-8b52-4c43-9f46-2baed2bd4cde)

https://public.tableau.com/views/FlightDelayandCancellations_16865293067240/Delay?:language=en-US&:display_count=n&:origin=viz_share_link

From the above Dashboard page, we can see that there are 7 different reasons for delays, and Late Aircraft delay and Airline delay are among the top 2 reasons. Since, Average Late Aircraft delay is the maximum, we will take a deeper look at which airlines cause the maximum late aircraft delay. Frontier Airlines has the highest delay in this regard, whereas US Airways has the least delay.

Also, I tried to rate airlines in terms of average distance traveled vs average airline delay. In the bubble chart above, the size of the bubble represents average airline delay and the color bar represents the average distance traveled. We can see that Virgin America airline, despite traveling for a longer distance on an average has the least airline delay, whereas Atlantic Southeast Airlines despite traveling a shorter distance, has a large airline delay. Thus, this plot can be used as a reference to choose airlines based on the distance an individual wants to travel.

The Day wise plot of the different types of delays doesn’t show significant patterns. However, there is a slight decrease in the average delay in the days from Jan 20th to Feb 11th, with the exception of a few peaks. Security delay stays pretty constant over time with a peak around Jan 17th - this was because airports in the US had started confiscating guns and other weapons which may have caused the peak in delay. Also, there is a greater average airline, departure, and weather delay in January and this might be because of the extreme cold weather in the winters during the month of January.

## Cancellation
![Cancellations (1)](https://github.com/shahaastha08/Flight-Delay-and-Cancellations/assets/37699951/07260bc0-f903-4d0a-a72d-08756bbcc325)

https://public.tableau.com/views/FlightDelayandCancellations_16865293067240/Cancellations?:language=en-US&:display_count=n&:origin=viz_share_link

From the cancellation page we can see that American Eagle Airlines has the highest number of canceled flights, followed by Southwest and Atlantic Southeast Airlines. So, these airlines should not be preferred in terms of cancellations.

Also, the number one reason for cancellation is B - Weather followed by A - Airline/Carrier and C - National Air System. Only 2 flights in 2015 were canceled due to D - Security.

Geographically, most of the flights that have been canceled originated in Texas, California, Illinois, and New York. Additionally, among cities, flights flying from Boston to New York and vice versa had the highest cancellations.

## Conclusion & Next Steps

This Dashboard contains descriptive visualizations about insights into delays and cancellations of flights. Using these insights, we can create a predictive model to predict delays and cancellations for future flights. In the visualization, I also talk about delays and cancellations with respect to the airlines. This information can be leveraged to create a ranking system for the airlines based on several factors like distance, average delay, #cancellations, etc. This will be very useful as a complementary feature with travel websites and apps where people will be able to choose which websites they should choose. We can also collect ticket price and other relevant airline related data and use that in our ranking model.

Thus, this Dashboard is just the beginning of exploring this dataset and learning more about the airline industry.










