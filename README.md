Charlieplexing-the-Arduino
==========================
 Charliplexing 6 LEDs

Row 1 (R1): Arduino Pin 13

Row 2 (R2): Arduino Pin 12

Row 3 (R3): Arduino Pin 11



variable    pinMode      state
 L           OUTPUT       LOW 
 
 H           OUTPUT       HIGH
 
 Z           INPUT        LOW
 


     R1 (Pin 13)      R2 (Pin 12)     R3 (Pin 11)
     
L1    L                 H                Z

L2    H                 L                Z

L3    Z                 L                H

L4    Z                 H                L

L5    L                 Z                H

L6    H                 Z                L 

LED    Cathode      Anode

1         R2          R1

2         R1          R2

3         R3          R2

4         R2          R3

5         R3          R1
6         R1          R3 
