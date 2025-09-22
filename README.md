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
![WhatsApp Image 2025-09-22 at 10 22 31_667bd75a](https://github.com/user-attachments/assets/554975b6-0c71-4520-82fc-29ce3dc6298a)



### 3. Transient Response Setup

![WhatsApp Image 2025-09-22 at 10 22 30_c8cf32ec](https://github.com/user-attachments/assets/12be371d-0c83-4e8a-9b1c-0dbca51fc27b)


![WhatsApp Image 2025-09-22 at 10 22 29_91d24ea3](https://github.com/user-attachments/assets/e9282cab-ef73-46be-b3f4-aa54958d0147)


## Output

### 1. Transient Analysis Output
![WhatsApp Image 2025-09-22 at 10 22 30_c3ca02aa](https://github.com/user-attachments/assets/4268541d-a948-4d12-a57f-98c6c593eda0)


## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
