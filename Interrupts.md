# What is the need for interrupts?
*  A program counter(PC) is a register in the CPU. It holds the address of the next instruction to fetch. 
*  A jump instruction causes the PC to change the address to a new value. Sometimes it causes the value to go back, causing a loop
*  An interrupt is required when the PC needs to change its address without executing a jump instruction.
## Types of interrupts
### Hardware interrupts
*  An interrupt may be caused due to an item of hardware such as a keyboard or mouse activating and causing the PC to swap to a new set of instructions. This is called a __hardware interrupt__
*  A hardware interrupt may also be caused due to an error in the hardware such as a printer running out of paper.
### Software Interrupts
*  These happen when software have issues and send interrupts to the CPU.
*  For example, when a web page takes too long to load\
### Extra:
*  Interrupts are used when two programs are supposed to run simultaneously, the CPU swaps between the two sets of instructions constantly

The OS constantly scans signals from the hardware and software and if it recieves an interrupt, the CPU interrupts the current program
