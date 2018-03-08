# Sample networks repository

Sample networks in with ".csv" extension can be placed here. 

* [Use the layout:

 "### buses: id, name, coord_x, coord_y, sm (True:1 False:0), power, damping, inertia"

 Parameters are: integer bus id starting from 0, bus name string, cartesian coordinates for graphical 
 represeantation, boolean to differentiate synchronous machines (sm) from nodes with first order dynamics, 
 power, damping, inertia (CAREFUL: leave inertia value empty if bus isn't a synchrnous machine)

 "### lines: from, to, susceptance, status (True:1 False:0)"

 Parameters are: integer bus ids of the nodes connected by the line, susceptance value, line status 1: connected, 0: disconnected

 Make sure to include both header lines in the ".csv" file.]

* [Use \t to separate values.]





 
