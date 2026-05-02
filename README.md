
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
## LAYOUT
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/808a3cdb-4659-42e5-80ef-b925b757d321" />

## Report

1. Cover sheet (as per attached example).  
2. Tabulation of received power, Q factor, and BER for 5 fiber lengths.  
3. Plot of received power, Q factor, and BER vs. fiber length.  
4. Description of eye diagram changes with increasing fiber length.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/42c1462d-d1a7-4048-91fe-23ea1db76382" />


---




## Tabulation

**Transmission Analysis Across Fiber Lengths**

| S.No | Fiber Length (km) | Optical Power (Watts) | Optical Power (dBm) | Max Q Factor | Min BER | Eye Height | Decision Instant (Max Q / Min BER) |
| ---- | ----------------- | --------------------- | ------------------- | ------------ | ------- | ---------- | ---------------------------------- |
| 1    | 50                |  48.441 E-6           | -13.148             | 116.953      | 0       |9.74806 E-05| 0.546875                           |
| 2    | 60                |  30.072 E-6           | -15.218             | 85.4419      |  0      |6.09831 E-05| 0.546875                          |
| 3    | 70                |  18.664 E-6           | -17.289             | 69.1773      | 0       |3.81636 E-05|  0.546875                           |
| 4    | 80                |  12.364 E-6          | -19.079             | 65.6179       |  0      | 2.37011 E-05|  0.546875                          |
| 5    | 90                |  7.676 E-6            | -21.147             | 50.7887     | 0       | 1.49748 E-05|   0.546875                           |
| 6    | 100               | 4.922 E-6           | -23.079             |   44.1989    |  0      |   9.3408 E-05  |  0.546875                          |
| 7    | 110               | 3.056 E-6            | -25.157             | 32.5119   | 0       |5.76769 E-05 |  0.546875                            |
| 8    | 120               |1.866 E-6              | -27.290             |29.1719      | 0       |3.60406 E-05  |  0.546875                     |
| 9    | 130               |1.236 E-6             | -29.079             | 26.6955   | 5.733062 E-192        | 2.25873 E-05 | 0.546875                             |
| 10   | 140               |780.089 E-9    | -31.079             |24.5565         |   1.8218 E-241 |1.40068 E-06         | 0.546875                             |
| 11   | 150               |    484.406 E-9 | -33.290             |  19.5098            |4.92689 E-108     |  8.6075 E-07          |  0.546875                            |

---
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/9818eaa1-084b-4955-8629-6b4c692c2cf6" />


## Graphs

## Optical Power vs. Fiber Length 
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/b63b91a5-72a2-457e-a38d-9a67ebf7cc40" />

## Q Factor vs. Fiber Length 
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/944f1509-a4cb-4b87-af2d-023cd5b224ee" />

## BER vs. Fiber Length
<img width="960" height="1280" alt="image" src="https://github.com/user-attachments/assets/d10c2e27-e5be-4a4f-8179-26db4907526f" />



---

## RESULT

As fiber length increases, received power and Q-factor decrease, while BER increases. The eye diagram becomes more closed, showing signal quality is reduced.
