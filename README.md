# Car Parking System using iverilog 

**Course: UE22CS251A (Digital Design and Computer Organisation)**

*This has been designed as a part of the laboratory mini-project for the course.*

## Description

- This Verilog module car_parking_system represents a simple car parking system with eight parking spaces.
- The module takes an 8-bit input vector sensors, where each bit corresponds to a sensor for a particular parking space.
- The module outputs an 8-bit vector parking spaces, indicating the occupancy status of each parking space.
- The testbench includes multiple test cases covering various scenarios, such as no cars present, cars in specific spaces, and all spaces occupied. Each test case sets the sensor inputs accordingly and observes the expected output in terms of parking space occupancy.
- Simulation results are captured in a VCD (Value Change Dump) file, and the GTK Wave is employed for visualizing and analyzing the simulation waveforms.

## How to Run

*Compile verilog code*

```iverilog -o car_parking_system_tb car_parking_system_tb.v car_parking_system.v```

*Run Simulation*

```vvp car_parking_system_tb```

*View Simulation Waveform*

```gtkwave car_parking_system_tb.vcd```
