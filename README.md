# 32Bit-ALU_Synthesis

## Aim:

Synthesize 32 Bit ALU design using Constraints and analyse area and Power reports.

## Tool Required:

Functional Simulation: Incisive Simulator (ncvlog, ncelab, ncsim)

Synthesis: Genus

### Step 1: Getting Started

Synthesis requires three files as follows,

◦ Liberty Files (.lib)

◦ Verilog/VHDL Files (.v or .vhdl or .vhd)

### Step 2 : Performing Synthesis

The Liberty files are present in the library path,

• The Available technology nodes are 180nm ,90nm and 45nm.

• In the terminal, initialise the tools with the following commands if a new terminal is being
used.

◦ csh

◦ source /cadence/install/cshrc

• The tool used for Synthesis is “Genus”. Hence, type “genus -gui” to open the tool.

• Genus Script file with .tcl file Extension commands are executed one by one to synthesize the netlist.

#### Synthesis RTL Schematic :

![Screenshot (233)](https://github.com/user-attachments/assets/f3d2a869-aa80-472a-abed-7789ebe697cf)

#### Area report:

![WhatsApp Image 2024-11-26 at 07 36 17_d5b5b9fc](https://github.com/user-attachments/assets/f640144d-7c6d-49cc-b787-4d9326a70b61)


#### Power Report:

![WhatsApp Image 2024-11-26 at 07 36 36_48103fdd](https://github.com/user-attachments/assets/57a57b9c-2b84-4e7f-853a-a0ff27a6a3e4)

#### Result: 

The generic netlist of 32 bit ALU  has been created, and area, power reports have been tabulated and generated using Genus.
