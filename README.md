# Ex No: 02 - Design & Implementation of Full Custom 2:1 MUX using Cadence EDA Tools

## Aim

The aim is to design and simulate a full custom 2:1 multiplexer (MUX) using Cadence EDA tools, ensuring accurate logic operation through waveform analysis and verification.

## Tools Required

### Cadence EDA Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library (e.g., 180nm, 45nm node)

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment
- Open the Cadence Virtuoso tool and set up the working library.
- Create a new schematic cell view for the 2:1 MUX design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Implement the following logic equation for the 2:1 MUX output:  
  **Y = (A · S′) + (B · S)**
- Connect the respective transistors to form the desired logic.
- Assign input voltage sources for control signal (S) and data inputs (A and B).

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe switching behavior.
- Set simulation parameters such as voltage levels, sweep range, and step size.
- Use Spectre simulator to perform the analysis.

### 4. Waveform Analysis
- Observe the output waveform to ensure correct MUX functionality.
- Confirm that the output reflects the selected input (A or B) based on the control signal (S).

## Circuit Diagram

### 1. 2:1 MUX USING CMOS
![image](https://github.com/user-attachments/assets/6fe3965a-47de-47d4-9dd1-0d52054de81b)


### 2. Schematic of Full Custom 2:1 MUX
<img width="1920" height="1200" alt="Screenshot 2025-08-30 115656" src="https://github.com/user-attachments/assets/232c99d7-c140-45d5-b3c7-154d9be9aeab" />


### 3. Transient Response Setup

<img width="500" height="761" alt="Screenshot 2025-08-30 121420" src="https://github.com/user-attachments/assets/fbc98a53-4267-47d9-82df-17597db29c95" />


<img width="1920" height="1200" alt="Screenshot 2025-08-30 121438" src="https://github.com/user-attachments/assets/ce92c610-c391-47d5-9008-7dccc61e0c8d" />

## Output

### 1. Transient Analysis Output
<img width="1920" height="1200" alt="Screenshot 2025-08-30 121039" src="https://github.com/user-attachments/assets/81186b95-7259-4696-be43-45b446f02ca0" />

## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
