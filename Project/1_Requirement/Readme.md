# Description

* This project is on distance measurement system using ultrasonic sensor. This system provides an efficient way on 

    measuring small distances precisely without any actual contact with the physical world. 

    It is used in several applications like automobile to assist in car-parking or anti-collision systems and in measuring

    liquid level and many more.

    __Future Scope__  of this project could be Obstacle avoidance vehicle/robot, this obstacle avoidance robot is based 

    on the principle of ultrasonic sensor as well. The basic principle of ultrasonic sensor based on the principle of echo

    . When sound waves are transmitted in the environment by the ultrasonic sensor then waves return back to the origin 

    as echo after striking on the obstacle in its path. 

## Features 

*   Used to measure the obstacle distance.

*   This system can be used in automobile parking sensors and anti-collision systems.

*   Used in terrain monitoring robots.

*   It can be used in Obstacle avoidance robot to monitor where human interaction is not possible.

## Defining the System

Distance measurement using HC-SR04 and ATMEGA328p. In this project i have measured distance in centimeters, with the help of HC-SR04 Ultrasound sensor, ATMEGA328p micro-controller, LCD Display via I2C bus.

Principle:

Timer2 of ATMEGA328p is used to generate a Trigger pulse of 20uS, the ultrasonic module sends out a 8cycle burst of 40khz which hits the object surface and returns back to raise an echo pulse. The pulse-width of this pulse is proportional to the distance between the module and Object.

Input capture module of the ATMEGA was used to capture the time between rising and falling edges of the echo pulse. The prescaler of this unit was chosen, such that the resolution of pulse-width is 16uS.

The display in use is LCD which has an integrated chip that converts serial data (via I2C bus) into parallel stream of bits for the LCD.

## 4W's and 1'H

WHAT:

Distance is a numerical measurement of how far apart objects or points are.Ultrasonic sensor provides an easy way in distance measurement.

WHY:

Ultrasonic sensors are great tools to measure distance and detect objects without any actual contact with the physical world. It is used in several applications.

WHERE:

Measuring liquid level, checking proximity and even more popularly in automobiles to assist in self-parking or anti-collision systems.

WHEN: 

The ultrasonic sensor emits a high-frequency sound pulse and calculates the distance depending upon the time taken by the echo signal to travel back after reflecting from the desired target. The speed of sound is 341 meters per second in air. After the distance is calculated, it will be displayed on the LCD display.

How:

This project, we have used the HC-SR04 Ultrasonic Sensor with ATMEGA328 to determine the distance of an obstacle from the sensor. The basic principle of ultrasonic distance measurement is based on ECHO.

## S.W.O.T analysis

The following image represents the swot analysis that i have done.

![diagram](https://github.com/AmitKumar-30120/M2_EmbSys/blob/main/Project/6_ImagesAndVideos/Swot_Image.png)

## High Level Requirements

| ID | Description |
| --- | --- |
| LR01 |The Timer count (OCR2A) of Timer2 was chosen |
| LR02 |Timer2 of ATMEGA328p is used to generate a Trigger pulse of 20uS,  |
| LR03 |The prescaler of this unit was chosen, such that the resolution of pulse-width is 16uS. |

## Low Level Requirements

| ID | Description |
| --- | --- |
| HR01 |Enable ICP Interrupt |
| HR02 |Enable rising edge detection,noise cancellation|
| HR03 |Enable internal pullups on PORTC PINS  SDA(PC4) ,SCL(PC5) |
| HR04 | I2C and LCD |


