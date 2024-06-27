# ELC2060 Project

## Overview

This repository contains the work for the ELC2060 project, which involves the design and analysis of NMOS transistors using a UMC 0.13µm technology. The project is divided into three main tasks, each with specific objectives and requirements.

### Task #1: NMOS Transistor Analysis
**Objective:**
- Analyze the characteristics of high-speed NMOS transistors (N_12_HS_L130E and N_LV_12_HS_L130E).

**Requirements:**
1. Sweep the width (W) of the NMOS while keeping the length (L) constant at minimum value (Lmin), then analyze various parameters:
   - Threshold voltage (VTH) vs. W/L.
   - Overdrive voltage (Vov) and saturation voltage (VDSAT) vs. W/L.
   - Transconductance times output resistance (gm.ro) vs. W/L.
2. Repeat the analysis for lengths L=2Lmin, L=4Lmin, L=8Lmin, and L=16Lmin.
3. Compare simulated results with long channel equations.
4. Discuss the advantages and disadvantages of N_LV_12_HS_L130E vs. N_12_HS_L130E, and recommend the best option for a high-gain amplifier.

### Task #2: Current Mirror Design
**Objective:**
- Design and compare two types of current mirrors using high-speed NMOS transistors and poly resistors.

**Requirements:**
1. Provide schematic diagrams with annotated dimensions and component values.
2. Annotate DC operating points at Vout=350mV to verify Vcomp specification.
3. Simulate to verify Iout and Rout specifications.
4. Estimate the area for both designs.
5. Suggest modifications if the area is too large, discussing the trade-offs.
6. Compare both designs in a table.
7. Discuss suitable applications for each design.
8. Draw and estimate the noise of both circuits, identifying dominant noise sources.

### Task #3: Class A Power Amplifier Design
**Objective:**
- Design a class A power amplifier using NMOS core high voltage RF transistor (N_33_RF).

**Requirements:**
1. Provide schematic diagrams with annotated dimensions and component values.
2. Annotate DC operating points.
3. Perform transient simulations to verify output specifications:
   - Plot Vout vs. time.
   - Plot the current flowing in the main device.
4. Calculate efficiency using simulations and compare with theoretical values.
5. Replace the ideal current source with a current mirror and analyze the impact on linearity.

## Assessment
- The total grade is 30 points.
- Maximum group size: 3 students.
- Deliverables include a detailed PDF report covering all required items.
- Penalties apply for late submissions and plagiarism.

## Repository Structure
- `/Task1/`: Contains files and simulations for Task 1.
- `/Task2/`: Contains files and simulations for Task 2.
- `/Task3/`: Contains files and simulations for Task 3.
- `README.md`: This file.

## Submission
- Submit the final PDF report and ensure all required items are included.
- Any missing requirement from the final report will be penalized in the final grading.
- Every day late = (-10%) from the assignment points.
- Any copied report will take ZERO.

---

### Notes
- Make sure to use the PDK of a UMC 0.13µm technology for all tasks.
- Pay close attention to the specifications and requirements for each task.
- Ensure all simulations are thoroughly documented and results are clearly presented.

Good luck with your project!
