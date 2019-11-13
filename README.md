# State-Estimation-and-Localization

Error State Extended Kalman filter is implemented in this project for the SelfDrivingCars Course provided in Coursera by University of Toronto.

The Results are plotted here :

<img src="data/images/o1.png" width="400"/> <img src="data/images/o2.png" width="400"/>

Error tolerance : x, y, z

<img src="data/images/o3.png" width="800"/>

The coding is found in the es_ekf.py file.

The concepts used are provided below(Materials were in the course provided by University of Toronto)

<img src="data/images/EKF_overview.png">

1) INITIALIZATION

The state and the input model were initialized in the following format

<img src="data/images/1.png">

2) PREDICTION STEP

<img src="data/images/2.png">

3) ERROR STATE INITIALIZATION

<img src="data/images/3.png">

4) UNCERTAINITY PROPAGATION

<img src="data/images/4.png">

5) MEASUREMENT UPDATE

<img src="data/images/5.png">

<img src="data/images/6.png">
