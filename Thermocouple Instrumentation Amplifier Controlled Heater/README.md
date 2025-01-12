# Thermocouple Instrumentation Amplifier Controlled Heater

In this project, I designed and simulated a thermocouple-based instrumentation amplifier to control the temperature of a heater. The system uses a K-type thermocouple to measure temperature, with the output amplified by an instrumentation amplifier to achieve the required sensitivity. The heater's resistance is controlled by a switch, which is activated when the temperature falls below a target set point, calculated as TS = 30 + mod(BilkentID, 40) °C.

The system includes an ON/OFF controller for the heater, driven by a comparator with hysteresis to ensure stable switching. The heater's status is visually indicated by an LED, which turns ON when the heater is active and OFF when it is not. The design meets the required specifications of output voltages at room temperature and at the target temperature.

I completed the design and simulation using LTSpice, ensuring all specifications were satisfied, including the necessary feedback and control characteristics. A schematic and PCB layout were designed using Diptrace, with careful attention to component placement and board size.

