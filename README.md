# riser16_ : 16-Bit-Computer
![Riser16 (2)](https://github.com/chauhansumitdev/16-Bit-Computer/assets/103536827/b68b2290-3f3a-49e1-9ec6-5a8121f6a081)
![Riser16](https://github.com/chauhansumitdev/16-Bit-Computer/assets/103536827/11642982-4abb-4438-a7db-8bbe702a5566)

[Watch showcase here](https://www.linkedin.com/posts/chauhansumitdev_i-made-a-custom-computer-introducing-riser16-activity-7210911977756327936-PNaN?utm_source=share&utm_medium=member_desktop)

## About

**riser16** is a 16-bit computer project that visualizes the low-level workings of computers. This project follows a Von Neumann architecture, using a common bus for both data and addressing. The complete description of its architecture and specifications are as follows:


![Screenshot 2024-06-22 025528](https://github.com/user-attachments/assets/b005c05b-beb9-4716-baab-cb7ac539a3b0)

## Hardware Specifications:
- **Architecture**: Von Neumann with a common data and address bus.
- **Word Size**: 16-bit.
- **ALU (Arithmetic Logic Unit)**: 8 modes.
- **Flag Registers**: 2 flags - Carry and Zero.
- **General Purpose Registers**: 2 registers - X and Y.
- **RAM Size**: 64KB (2^16).
- **Microinstruction Cycle**: Maximum 16 cycles for NOP (No Operation) and minimum 3 cycles for SKIP.
- **Display**: Two types - Hex display and 256x128 pixel display.
- **Instruction Set Capacity**: Complex instruction set with 256 (2^8) possible instructions.
- **Turing Complete**: Yes.

## Features:
- **Von Neumann Architecture**: This architecture allows both data and instructions to be stored in the same memory space, simplifying the design and operation of the computer.
- **16-bit Word Size**: Enables the processing of larger amounts of data in a single operation compared to smaller word sizes.
- **ALU**: The 8-mode ALU provides flexibility in performing various arithmetic and logic operations.
- **Flag Registers**: Carry and Zero flags are essential for arithmetic operations and branching decisions.
- **General Purpose Registers**: X and Y registers offer data storage for operations.
- **Large Memory**: 64KB RAM provides ample space for programs and data.
- **Efficient Microinstruction Cycle**: Optimized for both simple and complex operations, balancing speed and functionality.
- **Dual Display**: The Hex display and pixel display enhance the visualization of data and operations.
- **Complex Instruction Set**: Supports a wide range of operations, making it suitable for complex computational tasks.
- **Turing Completeness**: Capable of performing any computation given enough time and resources, demonstrating its power and flexibility.

## How to run this project?
To run the riser16 project, you will need Logisim, an educational tool for designing and simulating digital logic circuits. Follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/chauhansumitdev/16-Bit-Computer.git
   cd 16-Bit-Computer
   ```

2. **Open in Logisim**:
   - Launch Logisim.
   - Open the project file (`riser16.circ`).

3. **Explore the Components**:
   - Examine the CPU, ALU, registers, memory, and display modules.
   - Run simulations to see the 16-bit computer in action.

## Instruction Set
For a comprehensive guide to the instruction set, refer to the [Instruction Set Documentation](instruction-set.md).

## License
This project is licensed under the MIT License - see the [LICENSE](link-to-license) file for details.
