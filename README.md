
Adaptive Traffic Light Controller (Verilog)

A priority-based, 4-way adaptive traffic light controller written in synthesizable Verilog HDL with a self-checking testbench.

Key Features

Dynamic Timing: Extends green intervals based on real-time vehicle sensor inputs.

Priority Preemption: Strict priority arbitration (Emergency > Pedestrian > Vehicle).

Starvation-Free: Round-robin scheduling ensures all waiting lanes get served.

Fail-Safe Design: Validated with assertions to guarantee conflicting greens never occur.
