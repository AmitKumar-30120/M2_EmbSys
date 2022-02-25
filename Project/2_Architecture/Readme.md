# Behavioral Diagrams :

## High Level Diagram

![diagram](https://github.com/AmitKumar-30120/M2_EmbSys/blob/main/Project/2_Architecture/Behavioral%20Diagrams/behavioral_diagram1.png)


## Low Level Diagram

![diagram](https://github.com/AmitKumar-30120/M2_EmbSys/blob/main/Project/2_Architecture/Behavioral%20Diagrams/behavioral_diagram2.png)

# Structural Diagram

![diagram](https://github.com/AmitKumar-30120/M2_EmbSys/blob/main/Project/2_Architecture/Structural%20Diagrams/structural_diagram1.png)

# Block Diagram And Explanation :

![diagram](https://github.com/AmitKumar-30120/M2_EmbSys/blob/main/Project/2_Architecture/block_diagram1.png)

*   AVR- ATmega328 microcontroller:- ATmega328 is an Advanced Virtual RISC (AVR) microcontroller. It 

    supports 8-bit data processing. ATmega328 has 32KB internal flash memory and 1KB Electrically 
    
    Erasable Programmable Read-Only Memory (EEPROM). This property shows if the electric supply 
    
    supplied to the micro-controller is removed, even then it can store the data and can provide 
    
    results after providing it with the electric supply. Moreover, ATmega328 has 2KB Static Random 
    
    Access Memory (SRAM).

*   HC-SR04 Ultrasonic Sensor:- The sonic waves emitted by the transducer are bounced back by an    

    object and received back in the transducer. After having emitted the sound waves, the ultrasonic 
    
    sensor will switch to receive mode. The time elapsed between emitting and receiving is 
    
    proportional to the distance of the object from the sensor.

      Distance can be calculated using : D = (time * Speed of sound )/2

*   Transmiiter(Trigger Pin) :- The trigger pin of ultrasonic sensor is used to transmit or send the 

    waves into the environment.

*   Receiver(Echo Pin) :- The transmitted waves return back and received by the echo pin when they 

    get collided to the obstacle.

*   LCD Display :- A typical 16*2 lcd display is used to produce the output distance calculated by 

    the ultrasonic sensor on the screen.

*   Power Supply :- A power supply rail and ground is used to enrgize the circuit in the simulide for 

    the simulation purpose.

