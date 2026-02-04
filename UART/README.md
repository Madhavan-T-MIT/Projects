**UART Protocol Implementation on Xilinx ZedBoard**

This repository contains the implementation of a UART (Universal Asynchronous Receiver Transmitter) transmitter and receiver using Verilog HDL with a fixed baud rate. The design is based on a clock-per-bit timing method to ensure accurate and reliable serial data communication.

The UART transmitter and receiver are designed using a Finite State Machine (FSM) architecture. Each module consists of Idle, Start, Data, Stop, and Clean states, enabling proper framing, transmission, and reception of serial data. A top-level module integrates both the transmitter and receiver to form a complete UART communication system.

The design was synthesized, implemented, and tested on the Xilinx ZedBoard (Zynq-7000). Functional verification was carried out using a custom testbench, and simulation results were analyzed through DocLight waveform analysis, confirming correct operation of both transmission and reception.

**Features**

UART transmitter and receiver with fixed baud rate

Clock-per-bit timing implementation

FSM-based design (Idle, Start, Data, Stop, Clean)

Top-level module integration

Hardware implementation on Xilinx ZedBoard

Verified using testbench and DocLight

**Tools & Technologies**

Verilog HDL

Xilinx Vivado

Xilinx ZedBoard (Zynq-7000)

DocLight (Simulation & Waveform Analysis)
