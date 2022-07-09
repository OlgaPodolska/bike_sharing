# bikesharing
Using Tableau to visualize bike-sharing data CitiBike to apply to Des Moines

# Overview of the Analysis

The purpose of this analysis is to help investors determine whether they should invest in a bike-sharing program in Des Moines. I used Citi Bike data that has been released to the public for my analysis and used Tableau to visualize bike-sharing data. I found out which data could be apply to Des Moines, drawing on both the data expertise and my critical thinking skills. To solidify the proposal, I created the detailed bike trip analysis.

Pandas
Tableau

Originally data was stored in the csv file:

![img0.png](/images/img0.png) 

# Results

For this analysis, I used Pandas to change the "tripduration" column from an integer to a datetime datatype:

![img1.png](/images/img1.png) 

I exported the new file without the index column as csv file:

![img2.png](/images/img2.png) 

Then, using the converted datatype, I created a set of visualizations.

Tableau link: <a href="https://public.tableau.com/app/profile/olga4859/viz/CitiBikeDataAnalysis_16573227002880/FinalDataAnalysis-Aug2019?publish=yes">CitiBike Final Data Analysis - Aug'2019</a>

*	I showed the total counts of bike rides for all riders in August 2019 

![img3.png](/images/img3.png) 

*	I showed the count of bike rides by starting and ending points on the map for all riders 

![img4.png](/images/img4.png) 

*	I showed the length of time that bikes are checked out for all riders 

![img5.png](/images/img5.png) 

*	I showed the length of time that bikes are checked out for all genders 

![img6.png](/images/img6.png) 

*	I showed the number of bike trips for all riders for each hour of each day of the week 

![img7.png](/images/img7.png) 

*	I showed the number of bike trips for all genders for each hour of each day of the week

![img8.png](/images/img8.png) 

*	I showed the number of bike trips for each type of user and gender for each day of the week

![img9.png](/images/img9.png) 


## Summary

Obtained results of analysis shows that overall bike sharing is very popular in NY, and can be successful in another places with relatively young, male-dominated population as Des Moines. Men used bikes more than woman, young people used them more than older, and there is quait difference between day times when bikes used. It could be useful for the investors, because allows to plan the bike repiring in the less popular times.

We can discover some additional points, if compare day times by user tipes and bike utilization.

*	I showed the most popular time of the day by user type

![img10.png](/images/img10.png) 

*	I showed the most popular bike utilization time per bike

![img11.png](/images/img11.png) 

This information needs additional analysis, but we can clearly see, that most popular duration of trip not too large, and subscribers have more pronounced differences between different day times.

Tableau link: <a href="https://public.tableau.com/app/profile/olga4859/viz/CitiBikeDataAnalysis_16573227002880/FinalDataAnalysis-Aug2019?publish=yes">CitiBike Final Data Analysis - Aug'2019</a>

