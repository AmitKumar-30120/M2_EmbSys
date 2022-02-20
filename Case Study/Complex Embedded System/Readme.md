# Requirements

 *    Before elaborating High level and low level requirement of Obstacle avoidance robot, first i would like to list 
 
      here its components required.

 ## Components Required :

 *   AVR- ATmega328 microcontroller:- ATmega328 is an Advanced Virtual RISC (AVR) microcontroller. It supports 8-bit data 
 
      processing. ATmega328 has 32KB internal flash memory and 1KB Electrically Erasable Programmable Read-Only Memory 
      
      (EEPROM). This property shows if the electric supply supplied to the micro-controller is removed, even then it can
      
      store the data and can provide results after providing it with the electric supply. Moreover, ATmega328 has 2KB 
      
      Static Random Access Memory (SRAM).

 *   HC-SR04 Ultrasonic Sensor:- The sonic waves emitted by the transducer are bounced back by an object and received 

      back in the transducer. After having emitted the sound waves, the ultrasonic sensor will switch to receive mode. 
      
      The time elapsed between emitting and receiving is proportional to the distance of the object from the sensor.

      Distance can be calculated using : D = (time * Speed of sound )/2

 *   LM298N Motor Driver Module:- L293D is a typical motor driver or motor driver IC which allows DC motor to drive on 
      
      either direction. It is a 16-pin IC which can control a set of two DC motors simultaneously in any direction. It 
      
      means that it can control two DC motor with a single L293D IC.

 *   DC Motors:- A DC motor in simple words is a device. An Electric DC motor is a machine which converts electric energy 
      
      into mechanical energy. This DC or direct current motor works on the principal, when a current carrying conductor 
      
      is placed in a magnetic field, it experiences a torque and has a tendency to move.This is known as motoring action. 
      
      If the direction of current in the wire is reversed, the direction of rotation also reverses.

 *   Battery:- A typical 9V battery is used to energizes the circuit and ready to work.

 *   Wheels:- A pair of wheels are used to move the robot in back and forward directions.

 *   Chassis:- A car model chassis is used to fabricate all the components on that.

 *   Jumper Wires:- Jumper wires are used for the connections in between the components altogether.

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
|       |                could be power efficient.                                                |       |           |      

## Applications : - 

*  Obstacle avoiding robots can be used in almost all mobile robot navigation systems

   They can be used for household work like automatic vacuum cleaning
   
   They can also be used in dangerous environments, where human penetration could be fatal

