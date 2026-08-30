## Week 13 Progress Report: Custom CNC Control Board Development

# Overview:

-Focused on developing the custom control board for the CNC machine.
-Reviewed and updated the circuit schematic based on the required voltage levels, components, protection, and control interfaces.
-Finalized the initial Bill of Materials (BOM) and component footprints for PCB design.

# Tasks Completed:

-Prepared the Bill of Materials (BOM) for the custom CNC control board.
-Assigned appropriate PCB footprints to the selected components.
-Reviewed the power architecture, including 12V input and 5V regulation.
-Evaluated components such as the ATmega328P, LM358, AMS1117, TMC2209, MOSFETs, TVS/flyback protection, and connectors.
-Planned I²C header pins, ISP connector, serial interface, limit-switch connections, and control outputs.
-Added provisions for microstepping selection and future hardware flexibility.
-Reviewed protection requirements for the pump and other inductive loads, including flyback diode and fuse connections.

# Challenges Faced:

-Finalizing the correct components and footprints for reliable PCB implementation.
-Verifying the ATmega328P pin assignments and additional GPIO requirements.
-Determining suitable PWM/control pins for the laser, pump, servo, and safety functions.
-Ensuring adequate protection against voltage spikes, current overload, and inductive switching.

# Key Outcomes:

-Established the initial custom CNC control-board architecture.
-Completed the BOM and PCB footprint assignment for the selected components.
-Identified key hardware requirements for motor control, laser control, pump operation, safety interlocks, and sensors.
-Improved the schematic based on the requirements identified during prototype testing.
-Prepared the design for the next stage of PCB layout and hardware implementation.

# Next Steps:

-Finalize and verify the complete schematic and component selection.
