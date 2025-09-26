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
<img width="850" height="569" alt="427964746-6fe3965a-47de-47d4-9dd1-0d52054de81b" src="https://github.com/user-attachments/assets/79cf3b11-ed18-4512-bf4b-5676eb5769df" />




### 2. Schematic of Full Custom 2:1 MUX
<img width="1919" height="1072" alt="489388918-95c1dbe6-c6e4-4619-9909-0da7da1088b3" src="https://github.com/user-attachments/assets/a670635f-fb1c-4802-a3a0-570efed3047d" />



### 3. Transient Response Setup

*![image](https://github.com/user-attachments/assets/47f7be45-4763-4d32-9eae-c417d1b7d501)*


<img width="1919" height="1079" alt="489388775-561c87ae-ab69-483d-92af-ee90416ea08a" src="https://github.com/user-attachments/assets/7ff9fdd0-9656-4a69-9550-b0b9ff128bb5" />


## Output

### 1. Transient Analysis Output
*![image](https://github.com/user-attachments/assets/557307b6-a35f-4e94-90e4-59bdb361c676)*

## Results
1. Successfully designed the full custom 2:1 MUX schematic using Cadence EDA tools.
2. The simulation results verified the correct MUX functionality, where the output accurately followed the selected input based on the control signal.
3. The waveform analysis demonstrated proper switching behavior for different control signal states.
