# Cal Poly ME-405
## Lab 02
Jacob Bograd, Nick De Simone, Horacio Albarran

---
#### This lab is a closed loop controller and step response test system
    The controller works by getting a proportional gain constant (kp) over UART
    The controller will then calculate a suitable PWM signal to have the motor 
    go to the right value. 
    Then it will update the encoder value and rerun the PWM calculation to get closer to the endpoint
    Once the endpoint is reached all of the data is sent back to the computer where it is plotted

---

![Kp = 0.5](Images/K_p%200.5.png)![Kp = 0.6](Images/K_p%200.6.png)
![Kp = 0.7](Images/K_p%200.7.png)![kp = 3  ](Images/K_p%203%20we%20had%20to%20hold%20it.png)
    **NOTE**
    3 was too big of a KP for the flywheel kept going past the setpoint
    To solve this issue for the test run we held the flywheel to allow it
    to stop on the stopoint. 


