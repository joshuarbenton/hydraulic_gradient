# Hydraulic Gradients - Three Point Problem Time Series
This program calculates the horizontal gradient and direction of groundwater flow by assuming a linear change in water level between three wells defining a geometric plane.  

Required inputs: 

1.) A time-series of water levels from three wells (example files: Well_#.csv). Water levels must be expressed relative to the same datum between each well.
2.) Cartesian coordinates (XY) of each groundwater well. Units must be the same as water level units. 

Output:

1.) A time-series "Hydraulic_Gradients.csv" of maximum hydraulic gradients (slope of the plane), and direction of maximum gradients (inferred direction of groundwater flow), and the corresponding water levels for each calculation. Gradient is unitless (L/L) and direction is reported in degrees from the positive Y-axis (or degrees from north if the well coordinates are in UTM).  

Instructions:

1.) Update the water levels and Date & Time columns within each of the example Well_#.csv time-series file. Keep the date format and file names the same.
2.) Open the "Three_Point_Problem.Rmd" file. Update the XY cooridinates (Lines 22-32) with the horizontal spatial coordinates of each well. Coordinates must be the same units as the water level units. 
3.) Run the "Three_Point_Problem.Rmd" file. 
