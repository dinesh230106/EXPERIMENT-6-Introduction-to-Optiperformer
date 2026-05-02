
Exp 6 Simulation of Optical Communication System
## Introduction to OptiPerformer 
## Objective
Download and install OptiPerformer software on your computer and run a sample file.

---

## Overview

Optiwave introduces **OptiPerformer**, a free photonic design automation tool that harnesses the full power of OptiSystem and creates specific dynamic design scenarios for student use.

In this exercise, you will:
- Download and install OptiPerformer on your PC/laptop.
- Use your license to load and run OptiSystem simulations prepared for this course.

The first simulation file (`Introduction_OptiPerformer.osp`) models a basic fiber optic system consisting of:
- A transmitter
- A fiber
- A receiver

The system includes:
- An optical power meter at the receiver input (fiber output)
- A Bit Error Rate (BER) analyzer

---

## Instructions

1. Download and install OptiPerformer from [optiwave.com](https://optiwave.com).  
2. Copy the `Introduction_OptiPerformer.osp` file to your PC.  
3. Launch OptiPerformer.  
4. Use the **File** menu or **Open File** button to open the fiber optic system file.  
5. Study the layout:
   - **Transmitter** section includes:
     - Binary source (PRBS generator)
     - Electrical pulse generator
     - Laser diode
     - External modulator  
   - **Receiver** section includes:
     - Photodiode
     - Low-pass filter
     - Decision circuit with BER analyzer  
6. Run the simulation using the **Start** button.  
   - Progress will be displayed.
   - Message “Calculation Finished!” appears upon completion.  
7. Double-click the **optical power meter** and **BER analyzer** windows.  
   - Check “Show Eye Diagram” in the BER window.  
   - Optical power meter shows power in watts and dBm.  
   - BER window displays:
     - Eye diagram
     - Max Q Factor
     - Min BER  
8. The simulation runs 5 iterations with fiber length varying from 50 to 150 km.  
   - Use forward/reverse buttons to step through iterations.  
   - Observe changes in received power, BER, Q factor, and eye diagram.

---

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

---

## Tabulation

**Transmission Analysis Across Fiber Lengths**

| S.No | Fiber Length (km) | Optical Power (Watts) | Optical Power (dBm) | Max Q Factor | Min BER | Eye Height | Decision Instant (Max Q / Min BER) |
| ---- | ----------------- | --------------------- | ------------------- | ------------ | ------- | ---------- | ---------------------------------- |
| 1    | 50                |                       | -13.148             | 116.953      | 0       |            |                                    |
| 2    | 60                |                       | -15.218             |              |         |            |                                    |
| 3    | 70                |                       | -17.289             |              |         |            |                                    |
| 4    | 80                |                       | -19.079             |              |         |            |                                    |
| 5    | 90                |                       | -21.147             |              |         |            |                                    |
| 6    | 100               |                       | -23.079            |              |         |            |                                    |
| 7    | 110               |                       | -25.157             |              |         |            |                                    |
| 8    | 120               |                       | -27.290             |              |         |            |                                    |
| 9    | 130               |                       | -29.079             |              |         |            |                                    |
| 10   | 140               |                       | -31.079             |              |         |            |                                    |
| 11   | 150               |                       | -33.290             |              |         |            |                                    |

---

## Graphs

*(Insert plots of Optical Power, Q Factor, and BER vs. Fiber Length here)*

---

## RESULT

*(Summarize key findings from simulation and analysis)*
