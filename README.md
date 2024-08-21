# Uno 14500

The Uno 14500 is a demonstration and training system built around the Motorola MC14500BCP Industrial Control Unit.

Its design borrows heavily from several sources including the Motorola ICU Handbook, Usagi Electric's MC14500 SBC, Nicola Cimmino's PLC14500, and my original Uno computer, a CMOS CPU I wire wrapped in college.

The system has 256 bytes of program memory, an 8 bit scratch register, an 8 bit output register, and an 8 bit input mux.

Program Input is primarily through toggle switches on the front panel, though memory boards with external ROMs are planned for the future. Switch and LED I/O is built into the console, and an external I/O connector is provided to use other peripherals.

I/O and memory mapping is designed to be compatible with either the MCU demonstration system from the Motorola ICU Handbook and the PLC14500 and the mapping of RR into I/O space is jumper selectable on the "Config" header. This header also houses jumpers to enable usage of the JMP and F flags from the CPU for returning to the reset vector and halting the system respectively

This repo, and the system, are still very much works in progress so check back as things are added.
