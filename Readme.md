# M2_EmbSys

## Distance measurement system

# Table of content
1. About the Distance measurement system
    1. Description
    1. Features
    1. 4W's & 1H and S.W.O.T analysis
1. Requirements
    1. High level requirements
    1. Low level requirements
1. Block Diagram and Blocks explanation
    1. Block Diagram
    1. Sensors
    1. Actuators
1. Test plan and Output
    1. High level test plan
    1. Low level test plan
1. Application


## About the Distance measurement system :- 

* This project is on distance measurement system using ultrasonic sensor. This system provides an 

    efficient way on measuring small distances precisely without any actual contact with the physical 
    
    world. 

    It is used in several applications like automobile to assist in car-parking or anti-collision 
    
    systems and in measuring liquid level and many more.

## Features 

*   Used to measure the obstacle distance.

*   This system can be used in automobile parking sensors and anti-collision systems.

*   Used in terrain monitoring robots.

*   It can be used in Obstacle avoidance robot to monitor where human interaction is not possible.

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

# Block Diagram And Explanation :

![diagram](https://github.com/AmitKumar-30120/M2_EmbSys/blob/main/Project/2_Architecture/block_diagram1.png)

*   __AVR- ATmega328 Microcontroller:-__ ATmega328 is an Advanced Virtual RISC (AVR) microcontroller. 

    It supports 8-bit data processing. ATmega328 has 32KB internal flash memory and 1KB Electrically 
    
    Erasable Programmable Read-Only Memory (EEPROM). This property shows if the electric supply 
    
    supplied to the micro-controller is removed, even then it can store the data and can provide 
    
    results after providing it with the electric supply. Moreover, ATmega328 has 2KB Static Random 
    
    Access Memory (SRAM).

##  Sensors:-   

*   __HC-SR04 Ultrasonic Sensor:-__ The sonic waves emitted by the transducer are bounced back by   

    an object and received back in the transducer. After having emitted the sound waves, the 
    
    ultrasonic sensor will switch to receive mode. The time elapsed between emitting and receiving is 
    
    proportional to the distance of the object from the sensor.

    Distance can be calculated using : D = (time * Speed of sound )/2

*   __Transmiiter(Trigger Pin) :-__ The trigger pin of ultrasonic sensor is used to transmit or send 

    the waves into the environment.

*   __Receiver(Echo Pin) :-__ The transmitted waves return back and received by the echo pin when   

    they get collided to the obstacle.

## Actuators:-

*   __Buzzer:-__ When the ultrasonic sensor calculates the distance of the obstacle then it starts 

    beeping in the environment indicating that process has been completed.


*   __LCD Display :-__ A typical 16*2 lcd display is used to produce the output distance calculated 
 
    by the ultrasonic sensor on the screen.

*   __Power Supply :-__ A power supply rail and ground is used to enrgize the circuit in the simulide 

    for the simulation purpose.

## Applications :-

*   It Used to measure the obstacle distance precisely.

*   This system can be used in automobile parking sensors and anti-collision systems.

*   It can be used in remote control robot projects for surveillance.

*   It can be used in Obstacle avoidance robot to monitor where human interaction is not possible.


## Future Scope  
    
*   Future scope of this project could be __Obstacle avoidance robot__ this obstacle 
    
    avoidance robot is based on the principle of ultrasonic sensor as well. The basic principle of 
    
    ultrasonic sensor based on the principle of echo. When sound waves are transmitted in the 
    
    environment by the ultrasonic sensor then waves return back to the origin as echo after striking 
    
    on the obstacle in its path. 

![](https://miro.medium.com/max/583/1*TMIAsl5FOo3DRYsqqe404w.png)

## FOLDER STRUCTURE INSIDE PROJECT

|       Folder              |           Description              |
|---------------------------|------------------------------------|
|1_Requirements             |Documents detailing requirements    |
|2_Architecture             |Detail about design and uml diagrams|
|3_Implementation           |All the codes are written here      |
|4_TestPlan                 |Documents with Test plan and output |
|5_Report                   |Generated Report file               |
|6_ImagesAndVideos          |images and videos files are attached|
