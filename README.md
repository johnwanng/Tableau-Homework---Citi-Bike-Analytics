# Tableau-Homework---Citi-Bike-Analytics
# Objective
Analyze CitiBike data that were recorded in the whole of 2019 from January to December for trends and build a dashboard and story using Tableau Public. Here is the link of my tableau story - https://public.tableau.com/profile/john5724#!/vizhome/CitiBikeHomework_16208893772470/CitiBikeStory?.

# How data are gathered and cleansed
I have gathered the 2019 citibike data and cleansed data having null starting and ending station records. I have also excluded records having null birth_year values.

# Description of each Dashboard
The first dashboard City Official Map. The chart on the top is a static map indicating the usage of each starting station in 2019. Dots having larger circles are more popular than the smaller one. The chart on the bottom is a dynamic map indicating the usage of each starting station for each chosen month from the dropdown on the right. User can also press the right play button and the map will navigate through each of the month of 2019 in ascending order the opposite effect will occur when the left play button is pressed. 

The second dash board is Gender vs User Type. There were more male than female riders throughout every months of 2019. There were more riders’ participation in the warmer months than the colder ones. The User Type chart on the left shows there were more subscribers riders than customer type. The bottom chart shows the breakdown of both male and females against customer and subscriber user type. Citibike official should target and invest more advertisement to encourage more people to participate in cycle riding in the colder months of the season. Perhaps building more sheds or shelters where weather would not affect people from riding bikes to and from work.

The third dashboard is Top and Bottom 10 starting and ending stations. The top left display the Top 10 starting and top left display the Top 10 ending and bottom left displays the Bottom 10 starting and bottom right display the Bottom 10 ending stations, respectively. There is a trend where there were a lot of popular start as well as ending stations like Sip Ave, Newport Path, City Hall, Grove Street Path as these areas are closed to metro and west side of the harbor. Where the bottom 10 ending stations were located around Avenue street and Broadway related areas. I would suggest adding more bikes to these popular top 10 starting and ending stations will allow more users to have a bike available as well as preventing the same bikes from enduring heavy usage which might increase repair fees, or worse, the chance of rider’s injury.

The fourth dashboard is Summer and Winder Peak Starting Hours. During summer day time, the peak starting hour are between 7:00 and 8:00 a.m. (work) and night time, the peak hours are between 5:00 and 6:00 p.m. (off work). It was exactly the same trend for winter months as well. Again as suggested in the earlier - by adding more bikes to those popular starting and ending stations during those 2 set of peak periods would allow more users to have a better chance in getting hold of a bike.

The fifth dashboard is Riders' Ages, Trips and Duration. Age 50 is the most popular group riding in 2019 which made up 6.5% of the population. I have already excluded data with null birth_year and the first phenomenon appears to be someone who was beyond the age of 100 was still riding in 2019. What was even more interesting is the longest trip duration was 117.4 achieved by a 114 old person. Here in order to collect the age specific data more accurately, it would be advisable to reference against to the birth_year of the subscribers or customer users information or carry out more robust age checking mechanism instead of allowing them to enter the year of birth freely without any validation.
 
The sixth dashboard is Bike, Trip and Duration. The chart on the left is contains a table of total number of trips and their average trip in minutes for all the bikes ridden in 2019. These columns can be sorted in ascending and descending order according to their column headings. Another phenomenon discovered is for bike id 21078, it was only ridden once, i.e. Total No. Of Trips = 1, but had a trip duration of 18059 minutes, i.e. almost 300 days. This bike could have been broken or stolen. Fortunately, there were not other bike statistic information which was as drastic as such. The top chart on the right indicates the top 20 bikes that were likely need repair based on highest total number times that were ridden in 2019. The top chart on the left indicates the top 20 bikes that were likely need repair based on highest total trip duration that were ridden in 2019.
