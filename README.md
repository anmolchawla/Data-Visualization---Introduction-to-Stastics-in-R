# INF 554 Assignment 10

The aim of this assignment was to demonstrate the use of basic stastical plots in R. 

The data that was chosen was Uber API data. The start latitude and longitude along with the end Latitude and Longitude was sent to the Uber API. 
In return UBER API responded with the following fields
1) Type of UBER's available (Ranging from UBER X, Pool to UBER Lux)
2) The Highest cost estimate
3) The Lowest cost estimate
4) The average cost range estimate
5) The distance between the two points
6) The currency of the location
7) The language of one of the cabs (Espanol)


1)Basic Stastical Plots that were included were:

 1)Scatterplot		(Uber name  vs highest cost estimate)
 2)Text	        	(Uber name  vs highest cost estimate)
 3)Bar chart		(Uber name  vs highest cost estimate)
 4)Line chart	        (Estimate vs date)
 5)Area chart		(Estimate vs date)
 6)Dot plot		(highest cost estimate)
 7)Histogram		(highest cost estimate)
 8)Frequency polygon 	(highest cost estimate)	
 9)Box plot	        (Uber name  vs Extrapolated cost estimate (eg: 8-10 became 8,9,10))
 10)Violin plot		(Uber name  vs Extrapolated cost estimate (eg: 8-10 became 8,9,10))

2) A faceted plot	(Uber name  -  highest cost estimate - lowest cost estimate)

3) A ggmap plot		(Start Lat long to End lat Long)	

4)Plotly bar plot       (Uber name  vs highest cost estimate)

The use of ggplot2, ggmap and plotly was demonstrated in the R studios.
A copy of the notebook was published at Rpubs (Link: http://rpubs.com/AnmolChawla/436253)
An R project with a seperate data folder was created and incremnetal git commits were made to ensure good practice.
Notebook was properly formatted with R Markdown



