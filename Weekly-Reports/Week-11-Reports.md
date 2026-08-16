## Week 11 Progress Report: Firmware Evaluation & PWM Signal Analysis

# Overview

- Focused on evaluating and modifying the LaserGRBL control system to support an additional PWM-controlled output.
- Investigated available PWM signals on the Arduino UNO with CNC Shield V3 using an oscilloscope.
- Tested different spray-paint coatings to determine their suitability for laser engraving PCB traces.
- Troubleshot and resolved a low-laser-power issue observed during engraving.

# Tasks Completed

- Checked PWM outputs from different pins available on the CNC Shield V3.
- Used an oscilloscope to verify PWM signal generation and behavior.
- Investigated the possibility of assigning an additional PWM output for pump-speed control.
- Resolved the previously observed low laser-power problem and verified improved laser operation.
- Tested engraving quality and examined the resulting trace patterns.
- Evaluated different spray-paint coatings for improved laser engraving performance.

# Challenges Faced

- No suitable additional PWM output was identified apart from the Z-axis-related output available on the CNC Shield V3.
- Firmware modification was limited by the available hardware pin configuration.
- The A0 pin, although available on the Arduino UNO, is configured as an analog input and required additional firmware/hardware consideration before being used for PWM control.
- Integrating an additional independently controlled PWM output without affecting existing CNC functions remains a challenge.

# Key Outcomes

- Successfully verified PWM signals from the CNC Shield V3 using an oscilloscope.
- Improved understanding of GRBL PWM generation and Arduino pin mapping.
- Resolved the laser low-power issue and achieved more consistent laser output.
- Successfully evaluated engraving traces and laser power during testing.
- Identified the limitations of the current Arduino UNO + CNC Shield V3 architecture for additional PWM control.
- Narrowed down the requirements for a future controller upgrade.

# Next Steps

- Test double-layer spray-paint coating for improved PCB trace engraving.
- Optimize laser power, speed, and number of passes for clean trace formation.
- Continue investigating firmware-based additional PWM control.
- If the current GRBL/UNO architecture cannot provide the required functionality, evaluate STM32 as a potential CNC controller for expanded PWM, I/O, and motion-control capabilities.
