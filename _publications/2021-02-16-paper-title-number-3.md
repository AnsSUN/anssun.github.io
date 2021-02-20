---
title: "EVALUATION OF CONTROL ALGORITHMS ON MOBILE ROBOTS FOR COLLISION AVOIDANCE"
collection: publications
permalink: /publication/2020-controls_pub_autonomous_driving
excerpt: 'This paper describes the implementation of various algorithms to control the distance between a lead vehicle and a following (ego) vehicle. The ego robot equipped with a monocular camera and a rotating laser sensor(LDS). The outputs of the camera and laser sensor(LDS) were fused to obtain accurate distance measurements for the lead vehicle. Kalman Filter was used to implementing sensor fusion by combining perception data from the monocular camera and LDS for accurate position and velocity estimation. The results show that the Model Predictive Control (MPC) yields faster response times when compared to Proportional (P) control and Proportional-Integral (PI) control. These algorithms evaluated during constant velocity and constant acceleration of the lead vehicle.'
date: 2020 November
venue: 'ASME 2020 International Mechanical Engineering Congress and Exposition (IMECE2020)'
paperurl: 'https://asme.pinetec.com/imece2020/'
citation: 'Sungra, Anshul (2019). &quot;Different control strategies for Mobile Robots. &quot;'
---
In this research, the ego vehicle was maintaining a safe relative distance by varying the velocity to catch up with the lead vehicle. A rotating Laser Distance Sensor (LDS) and an RGB camera were used to detect the objects in the environment. To localize the ego vehicle, a detection clustering algorithm and a Kalman filter was used to estimate the relative distance between the two vehicles. Different controllers such as Proportional, Proportional-Integral, and Model Predictive Control were implemented and validated through experiment on the turtlebot3-burger robot.

[Download paper here](https://asme.pinetec.com/imece2020/)

Recommended citation: Sungra, Anshul  (2019). Different control strategies for Mobile Robots".

