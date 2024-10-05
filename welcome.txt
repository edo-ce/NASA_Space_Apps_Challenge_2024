Welcome, Space Apps challengers, to “Seismic Detection across the Solar System”. 

Today, we challenge YOU to parse through seismic data collected on the Moon and Mars and figure out how to detect moonquakes and marsquakes! 
To get you started on the data, we present to you a training set containing the following:

1. A catalog of quakes identified in the data
2. Seismic data collected by the Apollo (one day segments) or InSight (one hour segments) missions in miniseed and CSV format. 
3. Plots of the trace and spectrogram for each day a quake has been identified. 

Using these tools, your task is to come up with an algorithm to identify these signals (using the catalog as a benchmark) and then 
apply your algorithm to the seismic data in the "test" folder (Apollo 12, 15, and 16 for the Moon and other InSight events for Mars). 

Each trace included in the test folder has a quake in it, there are no empty traces. 

This main folder also has a Jupyter notebook that will help you get started on the data.

** IMPORTANT **
Please make sure that your output catalog has at least the following headers:
filename
time_abs(%Y-%m-%dT%H:%M:%S.%f) or time_rel(sec)

If not, your output catalog may not be scored!!
** IMPORTANT **

Good luck!!! If you have any questions, our team leaders will be around to help during the hackathon weekend!  