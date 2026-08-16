# Week 10 Progress Report: Etching System Integration & Firmware Exploration

## Overview

- Focused on integrating the etching system with the CNC machine.
- Connected a coolant pump for PCB etching using an N-channel MOSFET for electronic ON/OFF control.
- Continued PCB engraving tests using different passes and engraving parameters.
- Studied the GRBL firmware architecture and source code to explore additional PWM control options.

## Tasks Completed

- Integrated the etching pump with the CNC system using an N-channel MOSFET.
- Tested pump speed variation by manually adjusting the voltage regulator.
- Engraved additional PCB samples using different numbers of passes and machine parameters.
- Studied GRBL firmware and its PWM/spindle control implementation.
- Investigated the possibility of using an available Arduino PWM pin for independent pump-speed control.

## Challenges Faced

- Pump-speed adjustment through the voltage regulator is manual and not easily repeatable.
- The Arduino UNO with CNC Shield V3 provides limited dedicated PWM functionality, with the existing spindle/laser PWM output already being utilized.
- Additional firmware and hardware modifications are required to achieve computer-controlled variable pump speed.

## Key Outcomes

- Successfully integrated the pump into the PCB etching system.
- Established MOSFET-based electronic control for the pump.
- Evaluated different engraving passes and parameters for improved PCB fabrication.
- Developed a better understanding of GRBL firmware and PWM control.
- Identified a potential approach for adding independent computer-controlled pump-speed control using an available PWM pin.

## Next Steps

- Implement software-controlled pump speed instead of manual voltage adjustment.
- Modify and test GRBL to support an additional PWM-controlled output.
- Verify reliable synchronization between laser engraving and etching operations.
- Study STM32-based CNC control as a possible future upgrade for improved I/O and control flexibility.
