# Medical-Data-Visualizer
Short program that uses multiple different plots to view medical correlations. 
In this project, I made some visualization and calculations from medical examination data using matplotlib, seaborn, and pandas. 

 I added an extra column, "overweight". To determine if a person is overweight, I calculated their BMI by dividing their weight in kilograms by the square of their height in meters. If that value is > 25 then the person is overweight. The value 0 is for NOT overweight and the value 1 is for overweight

I normalized the data by making 0 always good and 1 always bad. If the value of cholesterol or gluc is 1, I made the value 0. If the value is more than 1, I made the value 1.

I also cleaned the data for the diastolic and systolic pressure.
The incorrect data fell under these circumstances: 

<pre>
 diastolic pressure is higher than systolic
 height is less than the 2.5th percentile
 height is more than the 97.5th percentile
 weight is less than the 2.5th percentile
 weight is more than the 97.5th percentile
</pre>
