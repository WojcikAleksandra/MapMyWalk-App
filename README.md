# MapMy...Walk!
![logo](./www/logo.png)

As a project group, we are pleased to present our web application **Map My Walk**.
It is a functional dashboard that processes data originating from the MapMyRun application, as well as the listening history of songs from Spotify.

Over the last two months, we systematically carried out measurements during our daily walks and recorded additional information such as air quality, the purpose of the walk, and whether or not we were listening to music on Spotify during a given walk.

The results of our work and analysis can be viewed in the completed application, which is available in this repository.
Below, we will briefly introduce our application by analyzing its various features.

## Basic features

The application allows us to switch between tabs, each of which analyzes a different aspect of our walks.

The menu on the left side allows us to select the person whose data we want to analyze, as well as to choose a date range, i.e. the days from which data should be included in the charts.

## Main panel (Panel Główny)

![screen1](./ScreenShoty/Panel_główny.png) 

In the main panel, we included all the most important introductory information for the user. Additionally, we included a map based on the *leaflet* library, which shows the 5 places most frequently visited by a given person within the selected time range.

## Activity

![screen2](./ScreenShoty/Aktywność.png) 

In the *Activity (Aktywność)* tab, we presented charts showing various relationships between the type of activity performed and the time spent on it or the distance covered. We also provided the option to choose the type of data presentation on the chart (total or daily average). In addition, we included a chart showing the distribution of the number of steps or distance per day within a given time period.

## Air

![screen3](./ScreenShoty/Powietrze.png) 

In the *Air (Powietrze)* tab, we included charts showing the relationship between air quality and when and how much we walked. Data regarding current air quality was obtained from the website air.plumelabs.com. We also included information explaining what the AQI index used to describe air quality is, the verbal air quality scale we use, and which time intervals correspond to individual times of day.

## Music

![screen4](./ScreenShoty/Muzyka.png) 

In the *Music (Muzyka)* tab, we focused on showing which tracks we listened to during walks and whether listening to music affected walking speed. The data was collected from the Spotify application, which we all use.

### Presentation recording
Download link for the recording: https://mega.nz/file/ItgGHJja#Y4QMA5iMe2ZXlrjI156BlmCyGKoLVfFfrurJzLMrWF0

Link to watch the recording: https://youtu.be/5F-_NUIdOLQ
