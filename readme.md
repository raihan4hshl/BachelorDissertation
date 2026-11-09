Implementation goal: A dual-core RISC-V SoC embedded flight contrl system for Unmanned Aerial Vehicle. 
UAV dynamics, sensor feeds, landing pad, noise factors to be simulated in Hardware In Loop using Matlab Simulink.
The FPGA implementation looks like following:
1. Core 0: Safety-critical deterministic landing core  
2. Core 1: AI-vision processing core
3. Shared memory and controlled inter-core communication
4. Hardware timers and performance counters
5. Interfaces to the HIL computer
6. FPGA-based AI accelerator
7. Runtime safety monitor
