# Sample networks repository

Sample networks in with ".csv" extension can be placed here. 

* Use the layout:

&nbsp;&nbsp;&nbsp; "### buses: id, name, coord_x, coord_y, sm (True:1 False:0), power, damping, inertia"

&nbsp;&nbsp;&nbsp; Parameters are: integer bus id starting from 0, bus name string, cartesian coordinates for graphical 
&nbsp;&nbsp;&nbsp; represeantation, boolean to differentiate synchronous machines (sm) from nodes with first order dynamics, 
&nbsp;&nbsp;&nbsp; power, damping, inertia (CAREFUL: leave inertia value empty if bus isn't a synchrnous machine)

&nbsp;&nbsp;&nbsp; "### lines: from, to, susceptance, status (True:1 False:0)"

&nbsp;&nbsp;&nbsp; integer bus ids of the nodes connected by the line, susceptance value, line status 1: connected, 0: disconnected

&nbsp;&nbsp;&nbsp; Make sure to include both header lines in the ".csv" file.

* Use \t to separate values.





 
