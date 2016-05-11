# GUN_PLOT_FOR_DATA_EVALUATION

The shell scripts are used to extract data from the syslog of the linux system.

File: Data_Delay

This file is used to extract data from syslog and save it to another new file using the following command

grep -rZ -E "$time.*TCP_OUT" $syslog > mptcp_cwnd // Used to grap time.*TCP_OUT from syslog and save in mptcp_cwnd file

awk '{print $7, $10}' cwnd_sf1_with_id > cwnd_sf1_new

File: Data_Plot

This script is used to plot results in GNUplot

Inorder to understand the concept of GNUplot, one should follow the links below:

http://www.mathematik.hu-berlin.de/~lamour/WR_I_WR_II_Num_I/gnuplotkurs.html

http://www.gnuplotting.org/tag/multiplot/
