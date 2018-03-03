# jumbotail-weather-assignment
Simple yet effective weather app

# Features
1. Display Weather and City features like City,Temperature,Time,Wind,Pressure,Humidity,Visibility,Min Temp,Max Temp,Sunrise      time,Sunset Time
2. Search feature which will help you to search for any city in the world
3. Detect Current location and display features mention above
4. Display 5 days forecast in trending form i.e. viewpager
5. Weather Map for rain,wind and temperature
6. Graph feature which display predicted graphs for temperature,rain and pressure
7. Deep link feature which help you to display data on the basis of parameters of deep link

# Preparing the Project
Let's put some bullets on what good architectures should be:

1. Independent
2. Testable
3. Re-usable
4. Extendable

# Building with Gradle
It’s also a good idea to put all links to maven and all global dependencies into buildscript right, i have added fab-reveal menu, william chart library ,cardview.

# Web services
I have created GenericRequestTask for genericness for the code which is extending AsyncTask and load the data in the background

# Deep Links Test

1. http://jumbotail.com/app/weather?city=delhi
2. http://jumbotail.com/app/weather?city=allahabad
3. http://jumbotail.com/app/weather?city=moradabad
4. https://mani.com/test?city=Amsterdam
5. https://mani.com/test?lat=28.7041&long=77.1025

# Challenges

1. Fetching data and maintaining proper Api structure
2. Thinking of proper architecture and flow
3. How to make UI and UX interactive
4. Deep linking feature,although finally code was easy but new feature to play for me
5. Changes made in location correspondingly showing changes in the chart 
