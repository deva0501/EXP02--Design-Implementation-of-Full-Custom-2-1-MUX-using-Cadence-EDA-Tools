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

## Circuit Diagram:

### 1. Schematic of Full Custom 2:1 MUX

![WhatsApp Image 2025-03-23 at 13 11 52_9f1b02e7](https://github.com/user-attachments/assets/2db3ff51-a093-4192-9546-e5e4aabc2223)


### 2. Transient Response Setup

![WhatsApp Image 2025-03-23 at 13 11 52_91ed31a5](https://github.com/user-attachments/assets/fccb31cb-4d01-444c-8b5a-d72f1417ce6e)


### 3. Transient Analysis Output

![WhatsApp Image 2025-03-23 at 13 11 52_58adb01e](https://github.com/user-attachments/assets/8802beb9-faca-48ab-b331-71f0a8ba12eb)

### 4. Output

![WhatsApp Image 2025-03-23 at 13 11 52_d40d4d9a](https://github.com/user-attachments/assets/fa96cf86-380e-4af7-b7d6-c8f81924ad50)

## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
