# Arduino-controlled Peristaltic Pump  
Peristaltic pump used as a mixologist.
Used finite state machine so that two systems (each with two motors - 1 driver board - 1 LED - 1 button) could be run in parallel. 
Drink struct defined each element that needed to be defined to create a "system."
Functions were generalized (stop motor, run motor) for future port to ESP32 to be controlled via app.
