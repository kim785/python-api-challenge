# python-api-challenge

GitHub created for homework submission (due August 5, 2021)

In this homework, our task was to analyze the weather of 500+ cities by importing data from Open Weather API. Based on this data, we pin-marked about 10 places that we would like to visit by importing gmaps and location searches. Three trends in the weather data are:

1) Maximum temperature (F) vs. Latitude graph is an upside-down parabola. The max temperature is the highest near the equator (latitude = 0), and it decreases as we move away from the equator. The humidity vs. Latitude graph shows a somewhat similar trend. The range of humidity is narrower in cities near the equator, only ranging approximately from 60 to 90 %, compared to those of other cities (between 10 to 100 %). This observation goes along with what we have learned in earth science courses back in high school. 

2) The correlation between weather measures (cloudiness, humidity, and wind speed) and latitude does not seem to exist, judging from the low R-values. Thus, it is hard to predict the weather of cities based only on their coordinates. Other factors, such as terrains or time of the year, should be considered as well.

3) My ideal weather conditions for the best vacation spot are >30 % humidity, > 85 F temperature, and > 8 mph wind speed. Filtering the cities based on these conditions, I ended up with places that I never really thought of visiting, nor have I heard of them as popular destinations. It could imply that weather condition plays an unimportant role in making decisions of vacation spots.
