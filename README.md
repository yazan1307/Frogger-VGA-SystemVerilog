# Frogger VGA Game (FPGA SystemVerilog)

A real-time Frogger-style arcade game built entirely in SystemVerilog for FPGA.  
Features a 640×480 VGA display, animated sprites, lane logic, collision detection, and background music — all implemented with hardware logic and finite-state machines.

---

## Overview
This project recreates the classic Frogger gameplay in hardware using a modular SystemVerilog design.  
Each element (player, cars) is rendered via dedicated VGA bitmap modules connected to a synchronization controller.

---

## Key Features
- VGA 640×480 pixel rendering  
- Modular design with object multiplexing  
- Smooth animation via timing counters  
- Music playback using programmable notes   

---

## Technologies
SystemVerilog · FPGA · VGA Timing · FSM · Digital Design

---

## Modules
| File | Function |
|------|-----------|
| CarsMatrixBitMap.sv | Renders moving cars |
| smiley_move.sv | Player motion and control logic |
| CarssMatrixBitMap.sv | Displays player lives |
| objects_mux.sv | Combines display layers |
| JukeBox1.sv | Background melody generator |
