# FactoryOptimization
Visualization and optimization of KPIs for a virtual factory in a game environment

Tasked with visualizing virtual data from a factory in the game 'Satisfactory' and optimizing OEE

Provided with various endpoints with access to factory data like machines, mining points, belts and resource consumption

Also given access to real time production data monitoring software

In code "Live Data", the parameters from various server endpoints are extracted and visualized using pandas

In code "Factory Layout", the coordinates of all machines, mining stations and belts are extracted and plotted using matplotlib

The machines with low production/consumption from live data are then identified on the map using their specific coordinates

Machines are correlated with their respective production figures using process flow diagrams
