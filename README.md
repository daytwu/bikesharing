# bikesharing

[Link to my story](https://public.tableau.com/profile/dayton.wu#!/vizhome/Challenge_16110860922250/BikeTripAnalysis?publish=yes)

## Overview of the statistical analysis:

The purpose of this analysis is to see if there can be any insights found on one cities bike sharing program (NYC CitiBikes) so that light can be shed on investment decisions for another city. This is done by analyzing the user datas for this program for a particular month of the year to see if any trends can be found.

## Results:

<img width="404" alt="Top Starting Location" src="https://user-images.githubusercontent.com/68725398/105097761-27300a80-5a77-11eb-8848-0eb85d788c8c.png">

The above image shows the starting locations of all the bike stations in our data. This is mapped with the stations longtitude and lattitude and then colored/enlarged by the size count of the rides itself. The image itself is Manhattan in NYC, this shows that dense metropolitan areas are a good start to look into when it comes to the initial steps of investment funding for bike stations for another dense metropolitan area.

<img width="742" alt="Checkout time by Users" src="https://user-images.githubusercontent.com/68725398/105098246-c9e88900-5a77-11eb-9bc2-062e907f252c.png">
<img width="757" alt="Checkout time by Gender" src="https://user-images.githubusercontent.com/68725398/105098268-d0770080-5a77-11eb-9ad8-0368ec8d4c92.png">

The above images is a deeper look into the ride durations for the Users as a whole and users split by genders. This shows that Males uers tends to have a longer ride duration compared to Females or the unknown genders, with 5 hours peaking for Males and total users. The "Checkout time by Users" visualization seems almost equal to the male users one on the gender split, this is most likely due to how dense the male user datas are within the dataset, which somewhat skewers the result to show a similar trend.

<img width="748" alt="August Peak Hours" src="https://user-images.githubusercontent.com/68725398/105099308-78d99480-5a79-11eb-87c5-9b2cffb8c9d1.png">

This image showcases the peak hours for the starting time during the month of August. According to the image, 7AM to 9AM is the most popular morning hours and 4PM to 7PM  is the most popular evening hours, with the evening hours being the more popular one with more people riding. On the other hand, 3AM and 4AM has the least amount of riders, which brings us to the next image.

<img width="588" alt="Bike Utilizations" src="https://user-images.githubusercontent.com/68725398/105099728-22208a80-5a7a-11eb-8852-d626194ae859.png">

This image showcases all the available Bike IDs within our data and displayed in a grouped count by the IDs itself. This is a quick and easy way to put focus on Bike Utilizations and can better prepare us in terms of which bike would require more maintenance due to higher usage.

<img width="751" alt="Trips by Weekdays" src="https://user-images.githubusercontent.com/68725398/105099973-8fccb680-5a7a-11eb-9366-452e25f09df2.png">
<img width="750" alt="Trips by Genders" src="https://user-images.githubusercontent.com/68725398/105099979-91967a00-5a7a-11eb-86f0-82580dcb9754.png">

These images showcases which days and hours of the week has more ride usages with one image by total users and another split by genders. This is another way to look at the peak hours, with the data being set into a heatmap format. 

A distinct story that the above "Trips by Weekdays" image shows that the peak hours doesn't show is that there are differences in popular hours when it comes to weekdays and weekends. Both Saturday and Sundays have a decent amount of usages spread out from 9AM till 7PM compared to the weekdays which had less usages during the non-peak hours of 10AM to 3PM (with Thurs and Fri showing a bit more increase compared to Mon - Wed). This could attribute to users generally needing whatever transportation that they can get a hold of to go from and to work or school during the weekdays compared to a more lax environment riding for pleasure in the weekends.

According to the by gender image, male users are still more common compared to female users. These images also reinforces the above that there are peak hours in both the morning and evening.


<img width="761" alt="Trips by Weekdays by Genders" src="https://user-images.githubusercontent.com/68725398/105102743-45006e00-5a7d-11eb-8950-e438e00224b1.png">

The last image showcases the trips by Gender and Weekdays, split across the user types in the dataset. This gives a very insightful look into what categories of users would most likely yield profit from subscribing to the service instead of being just a customer (most likely a pay per ride customer). According to the image, male users heavily subscribe to the service instead of being a pay per ride customer, with it seeminly double to triple the amount of females during the weekdays. 

The other observation is that unknown gender users probably do pay per ride, preferring without the hassle to have a profile through the subscription services and setting up an account that way. Unknown gender users that subscribe are little to none compared to the ones that are just a regular customer.

## Summary:

According to the data images, male users seems to heavily favor subscribing compared to pay-per-ride and weekdays seems to be more popular compared to weekends with the hours peakng from 7AM to 9AM and 4PM to 7PM. These looks like prime data to go start development in, starting with having bike stations in the most dense areas of a city. 

The data, however, is lacking in terms of any of the financial aspects that an investor will probably want to look into. With this amount of data when it comes to looking at peak hours, it is equally important to see the price per ride and price per subscription of the services itself to correctly determine if profits can be made or for the business to be sustainable. Des Moines might not have the same level of density compared to NYC, which will inevitably affect a lot of the data here if this bikeshare program starts up in that city. 

With that said, one additional visualizations that can be made would be the pricing amount from rides for regular customers compared to the pricing on the subscriptions for the users, to see which category is more popular. Another visualization would be an analysis on the total prices during the peak hours of a week compared to non-peak hours, this would most definitely yield meaningful results for investments when it comes to comparing costs vs revenues for this programs services.

