# RSIC-V

### Introdcution to ***Instruction Set Architeture (ISA)***
An Instruction Set Architecture (ISA) is the interface between the hardware and the software. It describes how excatly the hardware funtions according to the software.  
It gives us a view of -   
- What are the various instructions are available?
- What is the function of each instruction?
- How does the particular instruction acheive the specified task?

A few famous ISAs include - 
- **x86**: Developed by Intel and AMD, x86 is one of the most widely used ISAs in personal computers and servers. It has a complex instruction set (CISC) and is known for its *compatibility with a large number of software applications*.

- **ARM**: ARM (Advanced RISC Machines) is a family of **RISC**-based ISAs that are popular in mobile devices, embedded systems, and IoT devices. ARM processors are known for their *power efficiency and scalability*.

- **MIPS**: MIPS (Microprocessor without Interlocked Pipeline Stages) is a **RISC**-based ISA that was used in a variety of applications, including embedded systems, networking equipment, and gaming consoles.

- **Power Architecture**: Developed by IBM, the Power Architecture is used in a variety of systems, including servers, workstations, and gaming consoles. It's known for its *performance and scalability.*

- **SPARC**: SPARC (Scalable Processor Architecture) is an ISA developed by Sun Microsystems (now Oracle). It was widely used in servers and *high-performance computing systems*.

- **RISC-V**: RISC-V is an open-source ISA known for its *modularity, flexibility, and customization*. It's gaining traction across various domains due to its *openness and adaptability*.

- **Itanium (IA-64)**: Developed by Intel and Hewlett-Packard, Itanium was aimed at high-performance computing but saw limited adoption due to various factors.

- **Alpha:** Developed by Digital Equipment Corporation (DEC), Alpha was known for its *high performance* and was used in some workstations and servers.

- **IBM System/360 and System/370**: These historical mainframe architectures were highly influential in the development of modern computer systems.

- **z/Architecture (z/OS)**: IBM's mainframe architecture used in their System z series of mainframes, known for *reliability, security, and scalability*.

Each of these ISAs has its own strengths and is used in various applications depending on factors like *performance, power efficiency, software compatibility,* and more. The choice of ISA often depends on the specific requirements of the target system or application.

---------
### Introduction to RISC 
RISC stands for Reduced Instruction Set Computer. The instructions in this architecture are basic and are all of the same size.   
CISC stands for Complex Instruction Set Computer. The instructions in this architecture are complex and of high computation.  
The differences between RISC and CISC are shown  
| CISC | RISC | 
|------|------|
| Many instructions are available which include basic and complex operations | Lesser number of instructions available for operations (basic ones) | 
| Instructions can be of variable size | Fixed length of all instructions. Makes operation of ProgramCounter easier |
| Many addressing modes available for instructions | Very Few addressing modes available (lesser opcodes) |
| Manipulation done directly in memory | Load and Store method used for operations, hence works only on specified registers |
| MUL 2:2,3:3 | LOAD A,2:2 <br /> LOAD B,3:3 <br /> PROD A,B <br /> STORE 2:2,A |  
--------
The whole system can be understood as three parts    
- *Application Software* - The C code written for the app. ( ex - The c code for a stop watch app)  
- *System Software* - The code which interprets the Application software to produce machine level instructions as the final output
- *Hardware* - The Processor (actual circuit)
  
The System Software can be elaborated as three major parts  
- Operating system (OS) - Delas with tasks of process management, memory allocation etc
- Complier - It converts the application software to instructions that 

