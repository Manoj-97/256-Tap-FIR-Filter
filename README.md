# 256-Tap-FIR-Filter
Dual Channel - Low Power - Mini Stereo Digital Audio Processor for hearing aid application

-> This Project starts of with architecture modelling in C++ to verify the functionality of add/shift alogrithm.
-> Behavioural Modelling of the design is carried out in Verilog to ensure specs are implemented and functionality is verified through simulation.
-> Based on the Design architecture, RTL implementation is carried out to finalize our Hardware.
-> The Design is later synthezised after verification. (Ensuring there is no Setup/Hold violation)
-> IC Design compiler is used to implement the floorplan of the design, using synthesized netlist to perform place and route, clock-tree synthesis and I/O planning.
-> Final Design with best utilization is chosen as our golden design

# Design Specs:
-> Serial Input channels, Parallel output channels
-> active-low reset
-> active-low frame
-> active-high start flag
-> System clock freq: 27Mhz
