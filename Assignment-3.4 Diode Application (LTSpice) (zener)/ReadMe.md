Zener Diode Voltage Limiting

Objective
To observe how a Zener diode maintains a nearly constant output voltage under different load conditions.

Circuit Description
The circuit consists of a 16V DC source, a 1k ohm series resistor, a 10V Zener diode (BZX84C10L), and a load resistor.
The Zener diode is connected in reverse bias to regulate the output voltage across the load.

Schematic


Simulation Results

Case 1: R2 = 100 k ohm


Vout approximately 10.23 V

Case 2: R2 = 10 k ohm


Vout approximately 10.20 V

Case 3: R2 = 1 k ohm


Vout approximately 8.00 V

Observation
For large load resistance values such as 100 k ohm and 10 k ohm, the output voltage remains close to 10V.
When the load resistance is reduced to 1 k ohm, the output voltage drops significantly.

Conclusion
The Zener diode keeps the output voltage nearly constant when the load current is low.
When the load current increases, the available current is not enough to keep the Zener diode in breakdown, so the output voltage decreases.

Files Included
Draft9.asc
Screenshot_1.png
Screenshot_2.png
Screenshot_3.png