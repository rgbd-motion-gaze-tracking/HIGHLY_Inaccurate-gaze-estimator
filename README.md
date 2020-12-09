# HIGHLY_Inaccurate-gaze-estimator

## After Having Pupil Coordinates, Eye Image, Screen Dimentions and Distance from Face to Screen
<p align="center">
  <img width="460" src="img/Capture.PNG">
</p>

O(x,y) is the center of eye image
O'(x,y) is the center of the screen

## Scaling Factors are defined as:
<p align="center">
  <img width="200" src="img/unnamed (2).png">
</p>

<p align="center">
  <img width="200" src="img/APP_SCRIPT_DOCS_IMAGE.png">
</p>

where 'd' is the distance between the user and the screen.
Note: We can obtain this value with the help of depth component from a RGBD camera or just define some value. 

## Gaze Estimation:
<p align="center">
  <img width="260" src="img/unnamed (1).png">
</p>

<p align="center">
  <img width="200" src="img/APP_SCRIPT_DOCS_IMAGE (1).png">
</p>

where;
x_i and y_i are pupil coordinates in the eye image
x_m and x_m are estimated position on the screen


## References:
1. N. H. Cuong and H. T. Hoang, "Eye-gaze detection with a single WebCAM based on geometry features extraction," 2010 11th International Conference on Control Automation Robotics & Vision, Singapore, 2010, pp. 2507-2512, doi: 10.1109/ICARCV.2010.5707319.
2. OpenCV Tutorials

