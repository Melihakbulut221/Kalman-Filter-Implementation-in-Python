# Kalman-Filter-Implementation-in-Python
I designed Kalman Filter algorithm on Python programming language. This repository will be extended later through Extended Kalman Filter and Unscented Kalman Filter.

Kalman filter has basically 2 step.
1) Update Step 
2) Measurement Step

In update step;
Next step is predicted using the previous step. We can indicate this step wih --> xhat-
"-" means a priori estimate.

In measurement step;
Next step is predicted using new measurements and a priori estime(xhat-). We can indicate this prediction with --> xhat

Also there is one more thing to estimate which is covarience. Covariance is important because it indicates how the prediction is disturbed. Covariance basically indicates the sharpness of the probability density function.

Also we need to set initial state estimates in kalman filter. For example; if we use kalman filter to fuse IMU and Camera initial states can be drones' departure coordinates. 

I take this graph from MATLAB Kalman filters video: 
![image](https://user-images.githubusercontent.com/57303760/215336384-38aaa822-067c-4795-9b1d-b2baebb76a21.png)
