![image](https://user-images.githubusercontent.com/72242597/121619263-f54f2d00-ca85-11eb-904d-73ff4eb6a3bc.png)

After adding the tool to the device view, the Visualiser add a ‘predict now’ button into the view, along with a few editable data fields. The editable fields are explained below

Prediction points: This number tells the Visualiser how many future data points need to be predicted. By default, the Visualiser spaces the points with the data collection time in the hardware configuration of the product. So if you set the product to collect data every 5 minutes, and select 6 prediction points, the Visualiser will predict the trend and show 6 points up to 30 minutes into the future.
No. Polynomial coefficients: Polynomial Visualiser processes the given input time-dependent data, and outputs the coefficients of the function of the form shown below, which most closely resembles the trend in the input data. This number tells the Visualiser how many elements should be present in the function i.e. the value of n.

![image](https://user-images.githubusercontent.com/72242597/121619300-00a25880-ca86-11eb-9581-9ded187dfbf7.png)

Frame Size: These are the number of previous data points the Visualiser will use to predict the trend of the data. For example, if you set this value to 5, the Visualiser will use the previous 5 points to predict the trend.
When you click the 'Predict' button, the prediction history (Red line) and the next predicted trend (Yellow line) are added to the graph.The prediction history is a graph of points the Visualiser would have predicted, at the time with the data before that point in time, using the current settings.  

![image](https://user-images.githubusercontent.com/72242597/121619328-0ac45700-ca86-11eb-9f9a-1997ba5143c4.png)
