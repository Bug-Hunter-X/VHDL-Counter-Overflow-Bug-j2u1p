# VHDL Counter Overflow Bug

This repository demonstrates a common bug in VHDL code: counter overflow. The original `counter.vhdl` file contains a simple counter that increments on each clock edge. However, it lacks bounds checking, leading to potential overflow when the counter reaches its maximum value (15 in this case).

The corrected code in `counter_fixed.vhdl` addresses this issue by adding a check to prevent overflow.  This example highlights the importance of carefully considering boundary conditions when designing digital systems.