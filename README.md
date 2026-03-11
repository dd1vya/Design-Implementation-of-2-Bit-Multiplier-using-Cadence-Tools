# Ex No: 06 - Design & Implementation of 2-Bit Multiplier Using Cadence Virtuoso

## Aim
The aim is to design and implement a **2-bit Multiplier** using **Cadence Virtuoso** and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the **2-bit Multiplier** design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **2-bit Multiplier circuit** using **AND and ADDER logic gates**.
- Connect the inputs (**A1, A0, B1, B0**) and outputs (**P3, P2, P1, P0**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the multiplication logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram

![image](https://github.com/user-attachments/assets/a56c4672-c7a5-44a8-908f-860243dc365d)


## Truth Table for 2-Bit Multiplier

![image](https://github.com/user-attachments/assets/fdb01f7d-60c1-4605-8462-c4dd954c5602)


## Schematic Diagram

### Schematicand Symbol of 2-Input AND Gate:

<img width="1600" height="910" alt="image" src="https://github.com/user-attachments/assets/5be685c9-50e2-4d82-99be-9aaed952bc38" />



<img width="1600" height="903" alt="image" src="https://github.com/user-attachments/assets/fdc5535b-7813-4cf0-8f24-9004a420cf2c" />


### Schematicand Symbol of 2-Input EX-OR Gate:

<img width="1600" height="904" alt="image" src="https://github.com/user-attachments/assets/3344a8cf-ee15-4bdd-afbf-118790f4a934" />


<img width="1052" height="707" alt="image" src="https://github.com/user-attachments/assets/ba4987dd-76da-4b68-adae-668e1b2c2007" />

### Schematicand Symbol of Half Adder:

<img width="1486" height="871" alt="image" src="https://github.com/user-attachments/assets/395e053d-731c-4f10-9ada-3b666e37562d" />


<img width="1178" height="964" alt="image" src="https://github.com/user-attachments/assets/f67350ab-46be-42d1-8d5b-77e8ad33dfe1" />


### Schematic of 2-Bit Multiplier:
<img width="1455" height="865" alt="image" src="https://github.com/user-attachments/assets/4391fe88-8353-47bd-b7c5-448bf6eff47b" />


## Output
### Transient Analysis Output:
<img width="1049" height="929" alt="image" src="https://github.com/user-attachments/assets/c7591576-22ad-4a8d-a340-c02604f067e4" />


<img width="1055" height="282" alt="image" src="https://github.com/user-attachments/assets/d638c1b0-274f-4929-831d-8f5c9a53e9ac" />



<img width="1199" height="678" alt="image" src="https://github.com/user-attachments/assets/d7a3a55c-bede-4eca-8329-528da11bb310" />


Run Time : 200ns

## Results
1. Successfully designed the **2-bit Multiplier** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Multiplier**.
3. Observed **correct multiplication behavior** in response to input signals.
