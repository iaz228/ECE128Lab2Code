# ECE128Lab2Code

This repository contain Verilog code for the design of an 1 bit Full adder and 4 bit full adders. It is meant for lab 2 for ECE128. It contains a 4 bit Ripple Carry Adder and 4 bit Carry Look ahead adder.

Instructions:

1.Create project in Vivaldo using correct FPGA selected
2.Move FA code into source file. Also add RCA and CLA adder into sources. Can also swap these out each testing case
3.Assign inputs to switches on FPGA and outputs to LEDs usings provided file
4.Add the test bench scripts as constraints in Vivid
5.Run Simulation to check wave form (Test bench should show appropriate addition in hexadecimal)
6.Run synthesis and check resulting gate level results
7.Create bit stream
8.Program FPGA
9.Test FPGA if all test cases work (Example test case: A = 3 (0011) and B = 5(0101) with C_in = 0 should result in Sum = (1000))
