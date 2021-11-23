# Hydraulic Gradients
Define the direction of groundwater flow in 2-dimensions by solving the three point problem
This program assumes a linear change in water level between each well and expresses the water table as a plane.

User inputs: 
1.) A time-series of water levels from each well (see example files). Water levels must be expressed relative to the same datum between each well.
2.) Cartesian coordinates (XY) of each groundwater well. Units must be the same as water level units. 

Output: 
1.) A time-series "Hydraulic_Gradients.csv" of maximum hydraulic gradients (slope of the plane), and direction of maximum gradients (inferred direction of groundwater flow), and the corresponding water levels for each calculation. Gradient is unitless (L/L) and direction is reported in degrees from the positive Y-axis (or degrees from north if the well coordinates are in UTM).  
