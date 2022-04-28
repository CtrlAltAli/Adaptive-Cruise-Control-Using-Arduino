
# Adaptive Cruise Control Using Arduino
Implement Adaptive Cruise Control Using Arduino Kit - Windsor university project

# Project requirements
 - Arduino Kit ( I have used ELEGOO UNO Project Super Starter Kit )
or
-   Arduino Board
-   Ultrasonic Sensor
-   LCD 16x2
-   Buttons
-   Resistors
You need to matlab software too.

# Implements

At the first step you need to design your circuit like this:

## step 1 - circuit
![Using the rotary button is not mandatory. You should connect your kit this way](https://github.com/seyedalifazel/Adaptive-Cruise-Control-Using-Arduino/blob/main/Circuit_Design.jpeg)

## step 2 - description

We will implement our project with 5 buttons:

**Increase_speed**  : one button for increasing the speed.

**Decrease_speed**  : one button for decreasing the speed.

**Set_speed / cruise_control**  : one button for enabling the cruise control mode. when you push this button your speed will be constant.

*  Increase_speed and Decrease_speed buttons can be used during this mode.

**Adaptive_speed/ Adaptive_ cruise_control**  : This button will enable the adaptive cruise control mode which is used to automatically sense the distance of the vehicle moving ahead and increase or decrease the speed of the vehicle with the respective distance. Increase_speed and Decrease_speed will be dysfunctional and pressing the cancel button will disable the cruise control. Display should continuously blink while adjusting the speed.

**Cancel**  : Pressing the button, cancels the Cruise control and resets the speed to 0.

The respective buttons are connected to the Arduino Pins which are provided below:

increase_speed - D13  
decrease_speed – A2  
cruise_control – A1  
Adaptive_ cruise_control – D9  
cancel – D11

## if you have any question about this project or need any help, don't hesitate to contact me
My email address is: sydalifazel@gmail.com
