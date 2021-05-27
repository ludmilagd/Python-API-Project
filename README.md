# Python and Weather API

## Objetive

To create a Python script to visualize the weather of more than 500 cities across the world. Weather information will retreived from the Web creating a connection to Weather API services. Finally create plots and perform Linar Regression Analysis between Latitude and other variables.

  The present Analysis presemts Scatter Plots to show relationship between:
    Temperature (F) vs. Latitude
    Humidity (%) vs. Latitude
    Cloudiness (%) vs. Latitude
    Wind Speed (mph) vs. Latitude 
 
  The scope of this project is to create Linear Regression analysis on the above relationships divided by hemisphere: 
    Northern Hemisphere - Temperature (F) vs. Latitude
    Southern Hemisphere - Temperature (F) vs. Latitude
    Northern Hemisphere - Humidity (%) vs. Latitude
    Southern Hemisphere - Humidity (%) vs. Latitude
    Northern Hemisphere - Cloudiness (%) vs. Latitude
    Southern Hemisphere - Cloudiness (%) vs. Latitude
    Northern Hemisphere - Wind Speed (mph) vs. Latitude
    Southern Hemisphere - Wind Speed (mph) vs. Latitude
    
Notes:

Randomly selected 500+ unique (non-repeat) cities based on latitude and longitude.
Performed a weather check on each of the cities using a series of successive API calls.


## Findings

Based on the colected information there is a clear correlation bewtween Tempeture and Latitude. The closer to 0 latitute the hotter is the City
Even though a correlationship between Humidity and Latitude might not be that strong, there is patter where for cities with latitute above 40, Humidity is high
Based on the graph Latitude vs Wind Speed, evenly distributed across all latitudes we can conclude that latitude does not affect wind speed
With a r-square of -.87 and a graph that clearly shows it, there is a strong negative correlationship beteen Tempeture and Latitute. 

In the Southern Hemisphere the correlation between Latitude and Temperature is less strong than in the Northern. With confidence of predicting the Temp in fucntion of Latitude of the City of 67%.

In the Northern Hemisphere, there is not enough information to conclude any relationship between HUmidity and Latitude. However, above latitude 40 all the cities have a 40% or higher Humidity.

In conclusion, the Wind Speed cannot be predicted based on Latitute of the city
There is a strong proven correlationship between Tempeture and Latitude. It is even stronger in the Nortther Hemisphere of the World, with a r-square of .87
Based on the information collected in this project, there is no evidence of relationship between Humidity and Latitude



## Google Places and Weather Data
G-maps and  Google Places to analyze weather data to plan future vacations

Create a heat map that displays the humidity for every city from the part I
Ideal weather condition for the Ortiz Family: 
        Max tempeture of 95 and a min of 70
        Wind speed less than 10 mph.
        Humidity should be 60% or les

Found 12 ideal cities to visit next Summer :) -> Definitly my next Vacation destination is Santa Ana, USA

### Snapshots to script and plots 
![image](https://user-images.githubusercontent.com/70984918/119898480-86ab9480-bf07-11eb-9752-1e91f731c3ee.png)
![image](https://user-images.githubusercontent.com/70984918/119898488-89a68500-bf07-11eb-8a88-e932fe174558.png)
![image](https://user-images.githubusercontent.com/70984918/119898494-8c08df00-bf07-11eb-98c9-38a7780a4cbc.png)
![image](https://user-images.githubusercontent.com/70984918/119898500-8f03cf80-bf07-11eb-9d3d-027b93f0085f.png)
![image](https://user-images.githubusercontent.com/70984918/119898517-92975680-bf07-11eb-9a43-3afb9d180810.png)
![image](https://user-images.githubusercontent.com/70984918/119898536-9b882800-bf07-11eb-8695-dc650f9dfe2a.png)


