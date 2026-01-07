# AND Gate using Verilog

This project implements a basic AND gate using Verilog HDL and verifies it using Icarus Verilog and GTKWave.

# Files
- and_gate.v:AND gate design
- tb_and_gate.v:Testbench
- and.vcd:Waveform output

# How to Run
```bash
iverilog -o and and_gate.v tb_and_gate.v
vvp and
gtkwave and.vcd
