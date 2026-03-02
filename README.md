# Traffic Light Controller using Verilog

## Overview

This project implements a 6-state Moore Finite State Machine (FSM) based Traffic Light Controller in Verilog HDL.

The controller manages traffic signals for:
- Main Road 1
- Main Road 2
- Main Turn
- Side Road

State transitions are controlled using a counter-based timing mechanism.

---

## Design Details

- FSM Type: Moore Machine
- States: S1 to S6
- Clock: Positive edge triggered
- Reset: Asynchronous reset
- Timing: Counter-controlled

---

## Light Encoding

Each traffic signal uses 3-bit representation:

- 3'b001 → Green  
- 3'b010 → Yellow  
- 3'b100 → Red  

---

## Files Included

- `traffic_light_controller.v` – RTL design  
- `traffic_light_controller_tb.v` – Testbench
- design 
- results

---

## Tools Used

- xilinx Vivado

## Description

The design cycles through six states to control multiple road signals with predefined timing values. The present state (ps) and counter (count) are used to manage state transitions and ensure proper signal sequencing.

---

