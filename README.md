<h1 align="center">Nano Processor</h1>


## Overview

As part of the **CS1050 - Computer Organization and Digital Design** module, this project involves designing and developing a 4-bit processor capable of executing four specific instructions. By completing this project, you will be able to implement:

- Design and develop a 4-bit arithmetic unit that can add and subtract signed integers.
- Decode instructions to activate necessary components on the processor.
- Design and develop k-way b-bit multiplexers or tri-state buses.
- Verify the functionality of the processor through simulation and implementation on a development board.

## Components

- **4-bit Add/Subtract Unit**
  - This unit should be capable of adding and subtracting numbers represented using 2’s complement.
  
- **3-bit Adder**
  - This unit is used to increment the Program Counter.
  
- **3-bit Program Counter (PC)**
  - The Program Counter needs to be reset to 0 when required. Build it using D Flip-Flops with a clear/reset input.
  
- **k-way b-bit Multiplexers**
  - A k-way b-bit multiplexer can take in k inputs, each with b bits, rather than a single bit. The output is a group of b bits. There are log<sub>2</sub> k control bits, and these control bits are used to select one of the k groups of b bits rather than a single bit.
  
- **Register Bank**
  - Contains 8, 4-bit registers (named R0 to R7).
  - Hardcode value of R0 to all 0s.
  
- **Program ROM**
  - This stores our Assembly program.
  
- **Buses**
  - Used 3, 4, and 12-bit buses to connect components. This greatly simplified our design rather than running so many wires around. We used labels such as D(3 downto 0), I(11 downto 0), M(3 downto 0), and R(3 downto 0).
  
- **Instruction Decoder**
  - The Instruction Decoder circuit is responsible for activating necessary components based on the instructions the user wishes to execute.

The following table contains the list of functions the shell should support alongside a brief description of what they are supposed to do.

<img src="Screenshot 1.png" alt="README Template" />

Block diagram of the nanoprocessor is given below:

<img src="Screenshot  2.png" alt="README Template" />

## Practical Operation

See `Instructions For Practical Operations.txt` for ways to get started.

## Report and Documentation

See `Project Report.pdf`

## Demo

Watch the `Demo_video.mp4` 

## License

This project is licensed under the [MIT](https://opensource.org/licenses/MIT) license.



