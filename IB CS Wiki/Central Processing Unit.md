# Central Processing Unit (CPU)

[[System Fundamentals Index|← Back to System Fundamentals Index]]

The Central Processing Unit (CPU) is the "brain" of the computer. It processes instructions and performs calculations. The CPU contains several important components that work together to execute programs.

## Main Components of the CPU

### Arithmetic Logic Unit (ALU)

The **ALU** (Arithmetic Logic Unit) is responsible for performing mathematical and logical operations.

**Functions:**
- Performs arithmetic operations (addition, subtraction, multiplication, division)
- Performs logical operations (AND, OR, NOT, comparisons)
- Processes data according to instructions from the Control Unit
- Outputs results back to registers or memory

### Control Unit (CU)

The **CU** (Control Unit) manages and coordinates all the activities of the CPU.

**Functions:**
- Fetches instructions from memory
- Decodes instructions to determine what operations are needed
- Controls the timing and flow of data between the CPU and other components
- Sends control signals to other parts of the CPU (like the ALU)
- Manages the fetch-decode-execute cycle

### Memory Address Register (MAR)

The **MAR** (Memory Address Register) holds memory addresses.

**Functions:**
- Stores the address of the memory location that needs to be accessed
- Points to where data should be read from or written to in memory
- Works with the MDR to transfer data between the CPU and memory
- Contains the address of the next instruction to be fetched

### Memory Data Register (MDR)

The **MDR** (Memory Data Register) holds the actual data being transferred.

**Functions:**
- Stores data that has been read from memory or is about to be written to memory
- Acts as a buffer between the CPU and main memory
- Temporarily holds data during transfer operations
- Works together with the MAR to complete memory operations

## How They Work Together

1. The **Control Unit** coordinates the entire process
2. The **MAR** holds the address of where to find data or instructions
3. The **MDR** holds the actual data or instruction retrieved from that address
4. The **ALU** performs calculations on the data when needed
5. Results are stored back in registers or memory

---

[[System Fundamentals Index|← Back to System Fundamentals Index]]
