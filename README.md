# sqlalchemy-challenge

## Georgia Tech Data Analytics Bootcamp - Module 10 Challenge

With this module, we were challenged to analyze provided weather data using Python and SQLAlchemy. In this part of the challenge, we connected to
an existing SQLlite database, identify  the most recent 12 months of data on hand, and plot the amount of precipitation in inches over that time period.

In the second part of this challenge, we identified the most active station that accumulated these measurements, and calculate the minimum, maximum, and average temperatures
recorded at this station. Furthermore, we designed a query to gather the temperature data from the most active station, and create a histogram of the number
of observations for each bin/range of temperatures recorded in the last year of measurements.

Lastly, we created an application through Flask to do a few things through the defined routes. The first was to return a JSONified-dictionary of precipitation data in the last
12 months of measurements. Secondly, we would return a JSON of the list of stations that recorded all measurements. Next, we return a JSON list of the minimum, average,
and maximum temperatures recorded at the most active station. And finally, the last route is a dynamic one that retrieves a user's input for a start date, and
end date (end date is optional), and returns a list of the minimum, average, and maximum temperatures recorded between those two dates (or up until the end of
our data, should the user not provide an end date).
