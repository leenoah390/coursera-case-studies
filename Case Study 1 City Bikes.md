Case Study 1:
# Bike-Share Membership #

### Introduction and Goals ###
Cyclistic is a bike-share company operating in Chicago since 2016. The company provides customers access to its fleet of bikes by way of short-term passes (single-ride, full-day) and annual memberships. Customers who purchase short-term passes are referred to as casual riders. Customers who purchase annual memberships are Cyclistic members.

The company’s current marketing strategy is based on a general awareness approach in targeting all potential customers. The director of marketing, Lily Moreno, believes in targeting Cyclistic’s casual rider market and turning more casual riders into members.

Before making such decisions, we must analyze the habits of casual riders and how they differ from members to determine what is holding back these casual riders from purchasing memberships over short-term passes.

### Findings ###
#### Overview ####
![Home Page](dashboard_home.PNG)

The bar charts on the right side of the image display the total count of riders over the months, days, and hours of the year.

From the top chart focused on **Month**, both members (dark grey) and casual riders (red) follow a similar trend of less riders during the winter / colder months and more during the summer / warmer months. However, as the months get colder, the difference in total rides between members and casual gets stronger.

From the middle chart focused on **Day of the Week**, it is clear that casual riders are much more active on the weekends over the Monday-Friday week days while members follow an opposite trend. The count of member rides follows a camel hump shape where peak rides is on Wednesday and less rides on the weekends.

The bottom chart focuses on the **24 hours of the day**. The number of member rides have two peaks that correspond to the hours of 7-9AM and 4-6PM.

Based on the above findings, we conclude that **members are more likely to be consistent riders that rely on Cylistic for a commute to work**. This is based off the peak hours in the day which correspond to morning and evening commuting times, more rides during the working week days, and having more rides during all months of the year including the winter months which dwarf the count of casual. **Casual riders on the other hand are more likely to be tourists**, as ride counts are much more active during the weekends and summer months.

The bottom left plot shows the distribution of rider counts for set lenghts of time. Notice that members overwhelmingly ride for less than 15 minutes which will support our theory on the majority of rides being centered around commuting trips. In addition, for longer rides that last for more than 30 minutes to over one hour, casual riders are more common. This also supports our theory on causal riders including tourists taking longer rides to view the city.

<img src="dashboard_casual.PNG" width="600">\
The above image shows the dashboard with a slicer filter on casual riders. Notice that a warmer month (September) and a weekend (Saturday) are recorded as the most popular month and day for casual riders.

<img src="dashboard_members.PNG" width="600">\
The above image shows the dashboard with a slicer filter on members. Notice that a weekday is recorded as the most popular day.

<img src="casual_rider_summer.PNG" width="600">\
A highlight based on the summer months for casual riders.

#### Ride Type ####
![Ride type view](electric.PNG)

The bottom center plot shows the distribution of ride types. Electric scooters are clearly not as popular. Why is that?
![Electric scooters are mainly present in September](electric_scooter_in_sep.PNG)
As shown above, it appears that electric scooters was a limited release in August and September. It is otherwise not present in any other month, so we removed it from further analysis.

Back to the origianl image above, we cans see the difference in use between members and casual riders with another variable in the ride type (classic and electric bike). Both members and casual riders tend to ride electric bikes over classic without any strong difference.

<img src="electric-casual classic.PNG" width="600">\
Something to note is that for longer rides, classic bikes start to gain more preference while shorter rides are mainly paired with electric bikes. Casual riders also adapt classic bikes earlier, as seen in the "16 to 30" minute column, which again support the theory of casual riders being visitors or perhaps riding for the exercise over commuting purposes.

### Summary and Recommendations ###
