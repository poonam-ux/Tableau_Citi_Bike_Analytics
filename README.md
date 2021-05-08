# Citi_Bike_Analytics

### Background

As the new lead analyst for the New York Citi Bike Program, you are now responsible for overseeing the largest bike sharing program in the United States. In your new role, you will be expected to generate regular reports for city officials looking to publicize and improve the city program.

Since 2013, the Citi Bike Program has implemented a robust infrastructure for collecting data on the program's utilization. Through the team's efforts, each month bike data is collected, organized, and made public on the Citi Bike Data webpage.

However, while the data has been regularly updated, the team has yet to implement a dashboard or sophisticated reporting process. City officials have a number of questions on the program, so your first task on the job is to build a set of data reports to provide the answers.

### Task

Using Tableau aggregate the data found in the Citi Bike Trip History Logs and find two unexpected phenomena. 

    * A 51 years old customers had the most number of trips, 44,020.
    * March 2021 has the biggest percent change in the ridership, 256.8%. This could be because of the warm spring months.

Design 2-5 visualizations for each discovered phenomena (4-10 total). You may work with a timespan of your choosing. Optionally, you may merge multiple datasets from different periods. Build a data dashboard, story or report. The following are some questions you will need to tackle.

* How many trips have been recorded total during the chosen period?
    * 255,345 total trips from July 2020 to April 2021

* By what percentage has total ridership grown?
    * Ridership changed by -87.78% from July 2020 (nice summer days) to February 2021 (cold winter days). But it is going up since then, as the spring days are coming.

![](https://github.com/poonam-ux/Tableau_Citi_Bike_Analytics/blob/main/images/Viz_monthly_trips.png)

* How has the proportion of short-term customers and annual subscribers changed?
    * Customers have 145.52% change in total trips from July 2020 to April 2021 with a dip in the months of December and January. Subscribers, on the other hand have a huge dip of 96.37% in the total trips. This could be because of the COVID-19 Pandemic, or cold winter months.

![](https://github.com/poonam-ux/Tableau_Citi_Bike_Analytics/blob/main/images/customers_vs_subscribers.png)

* What are the peak hours in which bikes are used during summer months?
    * 6pm and 7pm are the peak Starttime hours for summer months.

![](https://github.com/poonam-ux/Tableau_Citi_Bike_Analytics/blob/main/images/Analysis2.png)

* What are the peak hours in which bikes are used during winter months?
    * 1pm, 3pm, 4pm are the peak Starttime hours for winter months.

* Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)
    * Groves St PATH - 16584 trips
    * Newport Pkwy- 16068
    * Liberty Light Rail- 12653
    * Hamilton Park- 10811
    * Marin Light Rail- 10760
    * Newport Path- 10446
    * Sip Ave- 10298
    * Columbus Dr at Exchange- 9040
    * JC Medical Center- 8976
    * Harborside- 8938

    The data shows the above stations had the most number of trips starting there.

* Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)
    * Groves St PATH - 18343 trips
    * Newport Pkwy- 16177
    * Liberty Light Rail- 12759
    * Hamilton Park- 11205
    * Marin Light Rail- 10785
    * Newport Path- 10645
    * Columbus Dr at Exchange- 9399
    * Sip Ave- 9169
    * JC Medical Center- 9162
    * Harborside- 8919

![](https://github.com/poonam-ux/Tableau_Citi_Bike_Analytics/blob/main/images/Analysis_top_bottom_stations.png)

* Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why)
    * Oakland Ave- 1774
    * Glenwood Ave- 1583
    * Riverview Park- 1448
    * 5 Corners Library- 1327
    * Christ Hospital- 1232
    * Dey St- 1196
    * Jackson Square- 1093
    * Union St- 1071
    * Leonard Gordon Park- 811
    * JCBS Depot- 1

* Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)
    * Central Park & 6 Ave- 1
    * Broadway & W 160 St- 1
    * Broadway & W 122 St- 1
    * Broadway & Battery Pl- 1
    * Barrow St & Hudson St- 1
    * Barclay St & Church St- 1
    * 6 Ave & Broome St- 1
    * 5 Ave & E 88 St- 1
    * 1 Ave & E 5 St- 1
    * 1 Ave & E 16 St- 1

* Today, what is the gender breakdown of active participants (Male v. Female)?
    * 49.32%  riders are male, while female riders are 20.97%. The 29.71% riders' gender is unknown.

* How does the average trip duration change by age?
    * Riders in 23 - 51 age group have an average trip duration between 825 - 2366.
    * 52 and 70 year old riders show the increase in the average trip duration.
    * Riders in the age group 25 - 41 took the total trips of more than 5000.
    * The data shows that the 51 and 52 year old riders took the highest number of trips.

![](https://github.com/poonam-ux/Tableau_Citi_Bike_Analytics/blob/main/images/Analysis3.png)

![](https://github.com/poonam-ux/Tableau_Citi_Bike_Analytics/blob/main/images/Viz_age.png)

* How variable is the utilization by bike ID?
    * Most bikes are ridden for the duration of 500,000. Some bikes have durations of more than 2000K. The bike 

Use your visualizations (does not have to be all of them) to design a dashboard for each phenomena.

![]()

![]()

![]()

![]()

The dashboards should be accompanied with an analysis explaining why the phenomena may be occuring.

![]()

Additionally, city officials would like to see the following visualizations:

* Basic: A static map that plots all bike stations with a visual indication of the most popular locations to start and end a journey with zip code data overlaid on top.

![](https://github.com/poonam-ux/Tableau_Citi_Bike_Analytics/blob/main/images/Analysis_map.png)

* Advanced: A dynamic map that shows how each station’s popularity changes over time (by month and year). Again, with zip code data overlaid on the map.

![](https://github.com/poonam-ux/Tableau_Citi_Bike_Analytics/blob/main/images/viz_map_popular_station_start.png)

![](https://github.com/poonam-ux/Tableau_Citi_Bike_Analytics/blob/main/images/viz_map_popular_station_end.png)

* The map you choose should also be accompanied by a write-up unveiling any trends that were noticed during your analysis.

### Considerations

Remember, the people reading your analysis will NOT be data analysts. Your audience will be city officials, public administrators, and heads of New York City departments. Your data and analysis needs to be presented in a way that is focused concise, easy-to-understand, and visually compelling. Your visualizations should be colorful enough to be included in press releases, and your analysis should be thoughtful enough for dictating programmatic changes.
