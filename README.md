# DAND_final_project
Final Project for Udacity's Data Analyst NanoDegree

Flights Project
For my final udacity project, I chose the flights data to analyse delayed flights.

I downlaoded the data from http://stat-computing.org/dataexpo/2009/the-data.html. I downloaded three years worth of data: 2008, 2000 and 1992. The files were rather huge so I knew I had to do a bit of cleaning before I proceeded to the analysis section. These are the steps I followed to make my my file smaller, and thus make the processing/analysis easier.

Read the bz2 file and save it as csv to have a backup of the datasets.
Join the datasets
Drop the unneccesary columns not needed for my analysis
Only look at rows that have a breakdown of delay as that is what I will focus on
Make a seperate file for 2008 data for non-time series analysis
After getting some feedback from a colleague, I changed the color scheme of the facetgrid and the heatmaps so bright colors were not used as that was not the main takeaway of the graph. Minor changes were also made to the titles and the labels of the graphs.

Summary of Findings
After cleaning the data, I used some exploration to find the average delay times over the three years. While the average delay time went down, the percentage of delayed flights went had gone up. Sunday had the longest average delays while July and December stood out for the delay by months. The total number of delays was also the largest in July.To have some more granular analysis , I looked at the how many times each airline had a delay. Southwest stood out as the airline with most delays, while Alaska Airlines had the biggest percentage of Carrier Delays compared to other types of delays.

Presentation Insights
Histogram and Boxplot were used to show the distribution of the data set across the three years. Heatmaps were used to investigate the most common reasoning for delays and the spread over different days and months. A FacetGrid was used to show the airlines performance at different airports which varied as different airlines have different hubs. I used a swarmplot to show the different types of delay, and how each airlines ranks in comparison.
