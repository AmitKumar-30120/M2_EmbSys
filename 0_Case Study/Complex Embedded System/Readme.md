## Requirements

 * Before elaborating High level and low level requirement of Obstacle 

    avoidance robot, first i would like to list here its components 
 
    required.

 ### Components Required :

 *   AVR- ATmega328 microcontroller

 *   HC-SR04 Ultrasonic Sensor

 *   LM298N Motor Driver Module

 *   5V DC Motors

 *   Battery

 *   Wheels

 *   Chassis

 *   Jumper Wires

 ## High Level Requirement

| ID    |                                   DESCRPTION                                      |Status |  
|-------|-----------------------------------------------------------------------------------|-------|
| HR01  |  The System should able to calculate the distance of obstacle in its way.         |       |
| HR02  |  The System should able to move ahead.                                            |       |
| HR03  |  The System should able to move back when obstacle detected.                      |       |
| HR04  |  The System should able to find  direction when obstacle detected.                |       |
| HR05  |  The System should move forward when no obstacle detected.                        |       |
| HR06  |  The System should get turn off.                                                  |       |


## Low Level Requirement 

| ID    |                                       DESCRPTION                                         | HLR ID|   STATUS  |
|-------|------------------------------------------------------------------------------------------|-------|-----------|
| HR01  |  The System should able to calculate the distance of obstacle by using below formula     |  HR01 |           | 
|       |            Distance = (Time x SpeedOfSound) / 2                                          |                   |                                               
| HR02  |  The System should able to move ahead by rotating wheel in clockwise direction.          | HR02  |           |
| HR03  |  The System should able to move back a little when obstacle detected by rotating the     | HR03  |           |
|       |        wheel in anti-clockwise direction.                                                |                   |             
| HR04  |  The System should able to find direction when obstacle detected by taking turns in its  | HR04  |           |
|       |                  way using servo motor for directions checking.                          |                   |
| HR05  |  The System should able to move forward after taking turns in its way                    | HR05  |           |     
| HR06  |  The System should get turn off when user toggle input switch so that the system         |HR06   |           | 
|       |                coulde be power efficient.                                                |       |           |      



