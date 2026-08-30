# Week 12 Progress Report: Prototype Completion & System Integration

## Overview

- Focused on completing the first functional CNC prototype by integrating the servo-based etching mechanism with the existing CNC system.
- Explored multiple hardware and firmware approaches for controlling the servo motor.
- Successfully integrated and tested the laser, pump, and servo system to validate the complete CNC operation.

## Tasks Completed

- Tested multiple servo-control and wiring configurations.
- Investigated LaserGRBL/GRBL firmware modifications for additional PWM-based control.
- Integrated the etching pump and servo mechanism with the CNC system.
- Performed complete system testing to verify coordinated operation of the major CNC components.

## Challenges Faced

- Difficulty identifying a suitable PWM-capable output for direct servo control within the existing CNC controller configuration.
- Required evaluation of multiple hardware components and circuit configurations to achieve reliable operation.
- Existing Arduino UNO + CNC Shield V3 architecture provided limited outputs for additional peripherals.

## Key Outcomes

- Successfully completed the first functional CNC prototype.
- Verified the operation of the laser, stepper motors, pump, and servo mechanism.
- Tested and evaluated multiple hardware and firmware approaches for peripheral control.
- Established a working prototype that can serve as the foundation for the next-generation CNC control board.

## Next Steps

- Design and develop a custom CNC control PCB integrating the required motion, laser, pump, and servo-control circuitry.
- Study the STM32 microcontroller platform for improved PWM, GPIO, motion-control, and peripheral capabilities.
- Evaluate STM32 as a potential replacement for the Arduino UNO-based control architecture.
- Begin planning the circuit architecture and pin mapping for the custom CNC controller.
