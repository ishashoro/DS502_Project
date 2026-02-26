# Urban Ferry Speed Optimization for Fuel Consumption and Pollutant Emissions Reduction 

# Problem 
Ferries in Istanbul have fixed schedules; however, the traveling speed of the ferries may or may not be at the optimal level regarding energy efficiency. The fuel consumption and pollutant emissions increase nonlinearly with speed, creating a need to find an optimum speed value that will reduce the fuel consumption and pollutant emissions. 

The aim of this project is to optimize the speed profile of the ferries travelling between Beşiktaş and Kadıköy to minimize fuel consumption and pollutant emissions without changing the trip travel duration.

# Plan
Each ferry trip is divided into 6 to 7 segments, each segment has its own time difference and speed values. The speed in each segment will be treated as a decision variable. 

Fuel consmption and pollutant emisison models will be selected which relate to the the speed of the ferry cubically. The total fuel consmption and pollutant emisisons will be computed based on these models. The optimiation of speed will be then applied aiming to minizme the fuel usage and pollutant emissions without changing the original time constraints or passing the operational speed limits. The process will be applied on 75 ferry trips, with each trip dividied into 7 segemnts on average. 
