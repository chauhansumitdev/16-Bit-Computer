| Instruction | Opcode | Description                                                                                          |
|-------------|--------|------------------------------------------------------------------------------------------------------|
| `NOP`       | 0h     | No operation. The CPU does nothing for this instruction.                                             |
| `DISPINIT`  | 0100h  | Initializes the display.                                                                             |
| `DRAWPIX`   | 0200h  | `<coordinate>` Draws a pixel at the specified coordinate.                                            |
| `SKIP`      | 0300h  | Works like NOP but takes less time to execute.                                                       |
| `JMP`       | 0400h  | `<address>` Jumps to the specified address.                                                          |
| `LDX`       | 0500h  | `<value>` Loads the specified value into the X register.                                             |
| `LDY`       | 0600h  | `<value>` Loads the specified value into the Y register.                                             |
| `ADD`       | 0700h  | Adds the values in the X and Y registers and stores the result back into the X register.             |
| `OUT`       | 0800h  | Displays the value in the X register on the hex display.                                             |

### Detailed Descriptions:

1. **NOP (0h)**
   - **Operation**: No operation is performed.
   - **Use Case**: Used to create delays or synchronize timings.

2. **DISPINIT (0100h)**
   - **Operation**: Initializes the display hardware.
   - **Use Case**: Must be called before any display operations to ensure the display is ready for use.

3. **DRAWPIX (0200h `<coordinate>`)**
   - **Operation**: Draws a pixel at the specified coordinate.
   - **Use Case**: Used to render graphics on the display.

4. **SKIP (0300h)**
   - **Operation**: Similar to NOP but with a shorter execution time.
   - **Use Case**: Used to create very short delays or to fine-tune timing without a significant delay.

5. **JMP (0400h `<address>`)**
   - **Operation**: Jumps to the specified address in memory.
   - **Use Case**: Used for branching and loop control in programs.

6. **LDX (0500h `<value>`)**
   - **Operation**: Loads the specified value into the X register.
   - **Use Case**: Used to set the X register to a specific value for subsequent operations.

7. **LDY (0600h `<value>`)**
   - **Operation**: Loads the specified value into the Y register.
   - **Use Case**: Used to set the Y register to a specific value for subsequent operations.

8. **ADD (0700h)**
   - **Operation**: Adds the values in the X and Y registers and stores the result back into the X register.
   - **Use Case**: Used for arithmetic operations.

9. **OUT (0800h)**
   - **Operation**: Displays the value in the X register on the hex display.
   - **Use Case**: Used to output data to the hex display for debugging or user interaction.

> Working on adding more instructions.