# Homework 2 - How do Taxis move in NYC?
In this assignment we perform an analysis of Taxis in NYC. In particular, we are curious to answer to some specific research questions (RQs) that may help Taxi drivers in planning their movements throughout the city and the Taxi's users to have hints about the convenience of enjoying this service.

For this purpose we use the open data of Taxi's trips in NYC. In order to answer to the RQs we take into account the data related to Yellow cab for the year 2018.

![](https://camo.githubusercontent.com/458eaaf3d4b918ec4a72a5177c0a6efa95f42ce6/68747470733a2f2f7777772e627269636b756e64657267726f756e642e636f6d2f73697465732f64656661756c742f66696c65732f7374796c65732f626c6f675f7072696d6172795f696d6167652f7075626c69632f626c6f672f696d616765732f343835393137373035335f633366623139303931375f6f2e6a7067)

## Script descriptions

1. __`DEFINTIVE.ipynb`__: 
      >[RQ1]: The relationship among NYC zones, periods of the year and the number of trips was described. Explained the main features of the written code and presented al the necessary plots and tables.

      >[RQ2]: The time intervals when the number of passengers is the highest are studied. The whole analysis also is provided for each borough separately. Then all results are visualized with corresponding plots.

      >[RQ3]: The plots are computed for each months and for each Boroughs. From the selected data can be described correlation between duration and trip distance.

      >[RQ4]: The most popular payment way is discovered. The number of payments for each type and for each borough is presented in dataframe and via bar plot. The chi^2 test is provided in order to find out if there is any correlation between boroughs and payment ways.

      >[RQ5]: The correlation between the length of the distances of trips and durations of the trips is reviewed. Provided a plot of their dependence. The Pearson Coefficient is computed and are made all the necessary comments.

      >[CRQ1]: The price per mile is computed in two ways for each trip, also the mean and the standart deviation is computed for that. The t-test is done for all the possible pairs of distribution of different boroughs. All the necessary plots is presented. Division by Duration of the variable P=Fare amount/Distance has managed to mitigate the effect of traffic and we saw that there is not difference in costs of taxis through borough.

      >[CRQ2]: The number of trips that starts in each zone is visualized on a chropleth map. Another map allows to count the races that end up in the single zone. All the discoveries are commented. All the necessary plots you can find in the folder [PLOTS](https://github.com/marcovicentini/HW2ADM/tree/master/PLOTS) in this repository.

2. __`PLOTS`__:
      > Consists of the plots for [CRQ2]
