# memory-verification-system-Verilog
Self-checking memory verification project using System Verilog

## Description
This project verifies a synchronous memory design using SystemVerilog.
A self-checking testbench is developed to validate read and write operations.

## Testbench Architecture
- Transaction class
- Generator
- Driver (BFM)
- Monitor
- Scoreboard
- Coverage
- Environment
- DUT
- Mailbox-based communication

## Testcases Implemented
- 1 Write (1WR)
- 1 Read (1RD)
- 5 Writes and 5 Reads
- N Writes and N Reads

## Tools Used
- SystemVerilog
- Siemens Questa / VCS (any simulator)

## How to Run
1. Compile RTL and testbench files
2. Set the test name
3. Run simulation
4. Observe matching and mismatching count

## Author
Ankita Sangame
Design Verification Fresher

