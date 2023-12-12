# Rain-prediction: 
Problem Statement: Create a Machine Learning model using various Classification Models to predict rainfall.
You have given the weather information of Sydney from 2008 to 2017 ()
The dataset contains 18 columns:
Date:The date of observation
Location:The common name of the location of the weather station
MinTemp:The minimum temperature in degrees celsius
MaxTemp:The maximum temperature in degrees celsius
Rainfall:The amount of rainfall recorded for the day in mm
Evaporation:The so-called Class A pan evaporation (mm) in the 24 hours to 9am
Sunshine:The number of hours of bright sunshine in the day
Humidity 9am:Humidity (percent) at 9am
Humidity3pm:Humidity (percent) at 3pm
Pressure 9am:Atmospheric pressure (hpa) reduced to mean sea level at 9am
Pressure 3pm:Atmospheric pressure (hpa) reduced to mean sea level at 3pm
Cloud 9 Am:Fraction of sky obscured by cloud at 9am. This is measured in “oktas”, which are a unit of eighths. It records how many eighths of the sky are obscured by clouds. A 0 measure indicates completely clear sky whilst an 8 indicates that it is completely overcast.
Cloud3pm:Fraction of sky obscured by clouds (in "oktas": eighths) at 3pm. See Cload9am for a description of the values
Temp 9am:Temperature (degrees C) at 9am
Temp3pm:Temperature (degrees C) at 3pm
RainToday:Boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0
RainTomorrow:Boolean: next day rain Classification
you are given the task to create a ML model to predict the rainfall on the next day.
