# Interactive_swing

Simple electric network dynamic simulator for interactive transient visualization (swing dynamics for synchronous machines and Kuramoto dynamics for loads). This simulator displays live frequency and voltage phases plots. Gui interactions allow to modify transmission line and bus parameters.

<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{array}{cl}&space;m_i\ddot{\theta}_i&space;=&space;d_i\dot{\theta}_i&space;&plus;&space;P_i&space;&plus;&space;\sum_j&space;b_{ij}\sin(\theta_i-\theta_j)&space;&&space;\quad&space;i\in\{\textrm{Synch.&space;Mach.}\}&space;\\&space;[3mm]&space;d_i\dot{\theta}_i&space;=&space;P_i&space;&plus;&space;\sum_j&space;b_{ij}\sin(\theta_i-\theta_j)&space;&&space;\quad&space;i\in\{\textrm{Load}\}&space;\end{array}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{array}{cl}&space;m_i\ddot{\theta}_i&space;=&space;d_i\dot{\theta}_i&space;&plus;&space;P_i&space;&plus;&space;\sum_j&space;b_{ij}\sin(\theta_i-\theta_j)&space;&&space;\quad&space;i\in\{\textrm{Synch.&space;Mach.}\}&space;\\&space;[3mm]&space;d_i\dot{\theta}_i&space;=&space;P_i&space;&plus;&space;\sum_j&space;b_{ij}\sin(\theta_i-\theta_j)&space;&&space;\quad&space;i\in\{\textrm{Load}\}&space;\end{array}" title="\begin{array}{cl} m_i\ddot{\theta}_i = d_i\dot{\theta}_i + P_i + \sum_j b_{ij}\sin(\theta_i-\theta_j) & \quad i\in\{\textrm{Synch. Mach.}\} \\ [3mm] d_i\dot{\theta}_i = P_i + \sum_j b_{ij}\sin(\theta_i-\theta_j) & \quad i\in\{\textrm{Load}\} \end{array}" /></a>

The folder "/network_data" contains a non exhausitve set of sample networks (in *.csv format) to choose from.

To run: "python swing_app.py"

Runs on: Python 2.7

Module requirements: numpy = 1.14.0, scipy = 0.17.0, networkx = 2.0, pyqtgraph = 0.10.0, PyQt4

