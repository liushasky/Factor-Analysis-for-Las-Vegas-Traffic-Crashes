# Factor-Analysis-for-Las-Vegas-Traffic-Crashes

This project is to analyze Las Vegas Traffic Crashes in Neo4j.

I imported csv file into Neo4j and identified the Neo4j schema. In order to analyze the traffic crashes, I have used the most seven relevant variables as my nodes and they are Crash, FirstDriver, SecondDriver, FirstVehicle, SecondVehicle, Environment and Agency. 

The relationships are as follows: 

Crash is caused by FirstDriver and SecondDriver; 
Crash occurs with FirstVehicle and SecondVehicle; 
Crash occurs under specific Environment; 
Crash is reported to Agency. 

In addition, I have run various neo4j queries for the dataset to understand the relationship between the nodes. 

The original dataset is pulled from City of Las Vegas. (2016). Traffic Crashes [Data file]. Retrieved from  https://opendata.lasvegasnevada.gov/d/w2h7-67ye![image](https://user-images.githubusercontent.com/63170640/119695006-c2693000-be1b-11eb-91f4-9a8c8e225ff6.png)
