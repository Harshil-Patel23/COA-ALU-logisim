# COA ALU Project

## Description

This project implements a 4-bit Arithmetic Logic Unit (ALU) designed using Logisim. The ALU supports various arithmetic and logic operations, including addition, subtraction, AND, OR, XOR, and shift operations. It was developed as part of a Computer Organization and Architecture (COA) course project.

## Features

- **Arithmetic Operations**: Addition and subtraction
- **Logic Operations**: AND, OR, XOR, NOT
- **Shift Operations**: Left shift and right shift
- **4-bit Data Width**: Operates on 4-bit inputs A and B
- **Operation Selection**: 4 select lines (S3 S2 S1 S0) to choose the operation
- **Output Flags**: Includes carry, zero, and other status flags

## Files

- `COA PROJECT.circ`: The main Logisim circuit file containing the ALU design
- `coa project report.pdf`: Detailed project report with design specifications and analysis
- `COA seminar.pptx`: Presentation slides for the project

## Requirements

- [Logisim](http://www.cburch.com/logisim/) - Digital logic simulator

## Usage

1. Download and install Logisim.
2. Open `COA PROJECT.circ` in Logisim.
3. Simulate the circuit by providing inputs to A (A0-A3), B (B0-B3), and select lines (S0-S3).
4. Observe the outputs F (F1-F2) and any flags.

## Operations Table

| S3 S2 S1 S0 | Operation        |
| ----------- | ---------------- |
| 0000        | Addition         |
| 0001        | Subtraction      |
| 0010        | AND              |
| 0011        | OR               |
| 0100        | XOR              |
| 0101        | NOT A            |
| 0110        | Left Shift       |
| 0111        | Right Shift      |
| ...         | Other operations |

## Contributing

This is an academic project. For suggestions or improvements, please contact the project maintainer.

## License

This project is for educational purposes.
