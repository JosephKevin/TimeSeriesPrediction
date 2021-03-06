README

The objectives of this project is to 
1. Visualize sensor data:

	Locate the table called “exec” and plot the following data points as a time-series chart: “depth”, “rate1s”, and “rate5s”. The time value is in the “ts” column. Note that the values for “rate1s” and “rate5s” are embedded in a JSON dictionary in the “rate” column of the table. 
	Locate the table called “tcplife” and plot the following data columns as time series plots and their histograms:  “rx”, “tx”, “dur”, “lport”, and “rport”.

2. Data Statics:

	2.1 Perform a study of descriptive statistics of 'dur' values in the 'tcplife' table.
	2.2 Are any of the values of “dur” are anomalous ?  Which ones ? use concepts of robust statistics to demonstrate which values, if any

3. Data Modeling

    3.1 Now, all your work has led up to the final part !  At this point, you probably have a good “feel” for the data so this part won’t be difficult, and it should be fun :)

    3.2 Take the time series data for “dur” in 3 above.  Predict the next 25 values in the time series based on the previous data.  Justify and explain your predictions and your approach.  Again, please show your work and code.

    3.3 Take the time series data for “lports” in the “tcplife” datatable.  Predict the next 25 values in the time series
    based on the previous data.  Justify and explain your predictions and your approach.  Again, please show your work and code.

4. What do you think the data in the “tcplife” and “exec” tables represent ?
