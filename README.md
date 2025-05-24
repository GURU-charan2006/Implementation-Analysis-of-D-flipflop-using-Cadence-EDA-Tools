## BADIMALA GURUCHARAN (212223060026)
## Aim
The aim is to design, implement, and analyze a D flip-flop using Cadence EDA tools, ensuring accurate sequential logic operation through waveform analysis and performance verification.

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
- Create a new schematic cell view for the D flip-flop design.

### 2. Schematic Design
- Select NMOS and PMOS transistors from the library.
- Design the D flip-flop circuit with key components such as clock signal input, D input, and Q output.
- Implement feedback connections to enable sequential behavior.
- Connect appropriate voltage sources for logic control and supply.

### 3. Simulation
- Verify the schematic design for connection errors.
- Launch the Analog Design Environment (ADE).
- Configure transient analysis to observe timing behavior and output transitions.
- Set simulation parameters such as clock frequency, voltage levels, and delay conditions.
- Use Spectre simulator to perform transient analysis and functional verification.

### 4. Waveform Analysis
- Observe the output waveform to confirm correct D flip-flop functionality.
- Ensure that the Q output follows the D input on the rising edge of the clock signal.

## Circuit Diagram

### 1. Tri State D Flip-Flop
![image](https://github.com/user-attachments/assets/ddf3603b-bdfd-41f2-8a98-4ad93862fd9f)

### 2. Schematic of D Flip-Flop
![Screenshot 2025-04-11 152811](https://github.com/user-attachments/assets/81533ec6-eb60-4b68-b437-f0bcd05f7020)



### 3. Transient Response Setup

![Screenshot 2025-04-11 152945](https://github.com/user-attachments/assets/473fbd43-a5dd-404c-8314-200589e8776c)


![Screenshot 2025-04-11 153143](https://github.com/user-attachments/assets/185eed4c-b76b-42bb-816a-591f723f43dd)


## Output

### 1. Transient Analysis Output
![Screenshot 2025-04-11 153244](https://github.com/user-attachments/assets/c6290bd5-c108-4bfb-8235-134e13a77955)



## Results
1. Successfully designed the D flip-flop schematic using Cadence EDA tools.
2. The simulation results verified the correct sequential logic behavior, ensuring that the Q output correctly follows the D input on the rising edge of the clock.
3. The waveform analysis demonstrated the expected timing behavior and performance of the D flip-flop circuit.
