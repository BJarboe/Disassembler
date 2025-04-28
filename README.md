# Disassembler
## SICXE Object Code Interpreter

This project provides a basic **disassembler** that translates SIC/XE object (hex) code back into human-readable assembly instructions.

## Features
- Converts object code to corresponding SIC/XE assembly instructions.
- Handles symbol and literal tables.
- Supports format 3 and 4 instruction decoding.
- Properly formats and outputs readable assembly listings.
## Tools/Technologies
- G++
- Make
## Key Components/Functions
- **disassemble()**: Main function that parses object code and writes corresponding assembly code.
- **declareMapping()**: Initializes the opcode-to-mnemonic map.
- **declareTables()**: Loads symbol and literal tables.
- **hexToInt() / intToHex()**: Utility functions for hex-integer conversions.
- **caps()**, **removeLeadingZeros()**, **hexToBinary()**, etc.: Helper functions to format and process input data.


## Author
Bryce Jarboe — RedID 825033151  
Date: 10/30/2023
