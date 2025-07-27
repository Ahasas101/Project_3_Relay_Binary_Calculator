# RELAY-BASED BINARY CALCULATOR

This project is a 4-bit binary calculator capable of performing addition and subtraction using only electromechanical relays. It relies entirely on relay logic, without the use of microprocessors, transistors, or any modern semiconductor devices. The design is inspired by early computers built before the invention of BJTs, MOSFETs, and CMOS technology.

## Demo Video

[Watch the demo on YouTube](https://youtu.be/0r_467PNGEw)

## Features

- 4-bit binary operation
- Supports addition and subtraction using the 2’s complement method
- Built entirely with relays (no microcontrollers or transistors)
- Memory and logic constructed from relay-based circuits

## Components Used

- 30 Single Pole Double Throw (SPDT) relays
- 33 1N4007 diodes
- 12 SPDT switches
- 4 NOT gates
- 3 Full adders
- 1 Half adder
- 4 One-bit memory registers (using SR latches)
- LEDs for output display
- Resistors
- 12V DC power supply

## Design Overview

- Logical operations (NOT, half adder, full adder) are implemented entirely with relay logic.
- SR latches act as 1-bit memory elements for storing intermediate results.
- Subtraction is achieved using the 2’s complement method.
- The design mimics the architecture of early electro-mechanical computers.


## Author

**Ahasas Yadav**  
B.Tech, Electronics and Communication Engineering  
Indian Institute of Information Technology, Una
