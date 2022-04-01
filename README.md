# Portable-Charging-System
MATLAB Simulation for bidirectional EV (Electric Vehicle) charger.

## Documentation:-

### Overview
This is the MATLAB Simulation for bidirectional EV (Electric Vehicle) charger. This works on the princlple of bidirectional buck-boost converter. It is used as both G2V(grid to vehicle) and V2G(vehicle to grid) charger.

### Summary
It is an advcanced model for EV charging by using Rectifier and Buck-Boost Regulator


### Functionality
If the battery of the EV is discharged then we can charge the battery with the help of this model. By this model we can charge the battery with either direct voltage or alternating voltage. That means it can be used as portable charging system. When the discharged vehicle is near to the grid then we can charge the vehicle with the help of rectifier circuit and boost-buck regulator. If the vehicle is not near the grid then we can charge the EV battery by another battery through the Buck-boost regulator. 
Another advantage of this model is also EV battery can be used as additional battery source. Thus it will supply voltage to the consumer through the boost-buck regulator


### Operation-
It is based on bidirectional converter.
If the EV Battery voltage is less than the grid voltage then SOC( State-of-charge) of the EV battery gets increased as seen in the scope. This is called G2V( Grid to Vehicle) system. But in this case the EV Battery voltage should must be greater than the Battery reference( in the Buck-boost regulator). We can manually control it. Else if the EV battery voltage is greater than the grid voltage then SOC of the EV battery gets decreased that means it supply voltage to the grid. This is called as V2G( Vehicle to grid) system.


## Skills:-
+ Matlab and Simulink
+ Power Electronics
+ Control System

### Language-
+ ***MATLAB Simulink***
