# MOS

A multiprogramming operating system allows multiple programs to run on a computer simultaneously. It aims to maximize CPU usage and throughput.
      
## Advantages:
- Higher CPU Utilization: The CPU is kept busy executing tasks, maximizing its utilization.
- Improved Throughput: Multiple programs running concurrently mean more work is done in the same amount of time.
- Better Resource Utilization: System resources like memory and I/O devices are utilized more efficiently.
      
## Phase 1:
- The guide presents the structure and operations of a Multiprogramming Operating System (MOS) project, particularly its initial version.
- Assumptions are outlined, including error-free job input, sequential job processing, and a single program loaded into memory at a time.
- Notation clarifies symbols like memory (M), Instruction Register (IR), and Service Interrupt (SI).
- In MOS master mode, service requests (SI) are handled, involving reading data (READ), writing output (WRITE), and termination (TERMINATE).
- The loading process (MOS/LOAD) loads programs from an input file into memory.
- MOS/STARTEXECUTION initializes program execution, while in slave mode, programs are executed according to fetched instructions (IR), with operations like load (LR), store (SR), compare (CR), branch if true (BT), input (GD), output (PD), and halt (H).
