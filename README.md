# balance-robot
<h2>Hardware</h2>
1. Arduino board
2. MPU-6050 3 Axis Accelerometer/Gyro Module
3. L298N DC Motor Controller

<h2>Connection</h2>

![Maker Tutor](https://1.bp.blogspot.com/-KDL984adcJ0/XB3PIuoE9YI/AAAAAAABMgI/lNtDQOqw3FoS03KgieEGUIVa_oGUkbcIwCLcBGAs/s1600/Screen%2BShot%2B2561-12-22%2Bat%2B12.35.52.png)

![Maker Tutor](https://3.bp.blogspot.com/-boL7oUHyLKI/XB3PQJTvvuI/AAAAAAABMgM/rxQHi9ax728Xd5rfHR5paHERvkZ5FJRzACLcBGAs/s1600/u3.png)

Tune the PID values manually instead. 

1.Make Kp, Ki, and Kd equal to zero.

2.Adjust Kp. Too little Kp will make the robot fall over, because there's not enough correction. Too much Kp will make the robot go back and forth wildly. A good enough Kp will make the robot go slightly back and forth (or oscillate a little).

3.Once the Kp is set, adjust Kd. A good Kd value will lessen the oscillations until the robot is almost steady. Also, the right amount of Kd will keep the robot standing, even if pushed.

4.Lastly, set the Ki. The robot will oscillate when turned on, even if the Kp and Kd are set, but will stabilize in time. The correct Ki value will shorten the time it takes for the robot to stabilize.
