# Optimizing-Carry-Look-Ahead-Adder-for-Energy-Efficient-Applications
## Project Overview
This project focuses on the design and implementation of an optimized Carry Look Ahead Adder (CLA) using MTCMOS technology to reduce power consumption. The primary objective of this project is to enhance the power efficiency of digital systems by implementing a CLA optimized with MTCMOS technology. The CLA is a critical component in digital systems, particularly in the Arithmetic Logic Unit (ALU), where it significantly impacts the overall system performance and power consumption.
      ![l2](https://github.com/shivam221997/Optimizing-Carry-Look-Ahead-Adder-for-Energy-Efficient-Applications/assets/156662255/09fe6ec0-4b41-41a7-ad4f-1ed386ecd651)


## Introduction
The project addresses the need for low-power design techniques in VLSI chip designs, especially with the increasing demand for portable electronic devices. By integrating MTCMOS technology, the project aims to minimize the sub-threshold leakage current, thereby reducing the overall power consumption without compromising the operational speed of the CLA.

## Optimization Technique: MTCMOS
MTCMOS (Multi-Threshold CMOS) technology is employed to achieve low-leakage power consumption. This technique involves using transistors with different threshold voltages to manage power efficiently:

![l1](https://github.com/shivam221997/Optimizing-Carry-Look-Ahead-Adder-for-Energy-Efficient-Applications/assets/156662255/a6e7f4cf-53cf-4c04-8b1c-588cb05cced3)

### Active Mode: 
Low threshold voltage transistors are used for fast operation.
### Sleep Mode:
High threshold voltage transistors isolate low threshold voltage transistors from the power supply, reducing leakage current.

## Implementation
The implementation involves the following components:

### AND Gate Schematic
![l3](https://github.com/shivam221997/Optimizing-Carry-Look-Ahead-Adder-for-Energy-Efficient-Applications/assets/156662255/a3e3b1b2-c8e2-49c2-99f1-000cd38769c0)

### OR Gate Schematic
![l4](https://github.com/shivam221997/Optimizing-Carry-Look-Ahead-Adder-for-Energy-Efficient-Applications/assets/156662255/61232772-8fce-4998-b603-e856574ea7a5)

### Propagate Block
![l5](https://github.com/shivam221997/Optimizing-Carry-Look-Ahead-Adder-for-Energy-Efficient-Applications/assets/156662255/fb906ab7-12e3-4c05-a679-3cc9666e33d2)

### Generate Block
![l7](https://github.com/shivam221997/Optimizing-Carry-Look-Ahead-Adder-for-Energy-Efficient-Applications/assets/156662255/ab7127ff-1746-4c75-a4f7-0db88112ea57)

### Carry Blocks
![l8](https://github.com/shivam221997/Optimizing-Carry-Look-Ahead-Adder-for-Energy-Efficient-Applications/assets/156662255/a822af8e-9053-409e-93a7-48e6ca100419)

### Sum Block
![l11](https://github.com/shivam221997/Optimizing-Carry-Look-Ahead-Adder-for-Energy-Efficient-Applications/assets/156662255/1967d254-dbb6-460c-a800-ff905089fc27)

Each component is carefully designed and simulated using the Cadence software with the gpdk 45 library.

## Results
The project results demonstrate the following:

The optimized CLA shows a trade-off between power and performance, with a slight increase in delay but a significant reduction in power consumption.
Static power consumption in the optimized CLA is drastically reduced compared to the normal CLA, indicating a successful reduction in leakage currents.

## Conclusion
The optimized CLA takes slightly more time to produce the output compared to the normal CLA, indicating a power-performance trade-off.
Static power reduction is significant in the optimized CLA, confirming the effectiveness of the MTCMOS technique in minimizing leakage currents.
![l16](https://github.com/shivam221997/Optimizing-Carry-Look-Ahead-Adder-for-Energy-Efficient-Applications/assets/156662255/88424355-466f-479c-a555-da336754a3e6)

![l17](https://github.com/shivam221997/Optimizing-Carry-Look-Ahead-Adder-for-Energy-Efficient-Applications/assets/156662255/33b32018-b7fc-4045-bbe0-485a635e0d72)

## Achievements
Successfully implemented a 4-bit CLA using Cadence with the gpdk 45 library.
Successfully implemented an optimized 4-bit CLA using MTCMOS technology.
Comparative analysis shows reduced static power in the optimized CLA.

## References
Ch. Daya Sagar, T. Krishna Moorti, “Design of low power flip-flop using MTCMOS Techniques,” International Journal of Computer Application and Information Technology, Vol.1, No.1, July 2012.
Hematha S, Dhawan A, and Kar H, “Multithreshold CMOS Design for low power digital circuits,” TENCON 2008-2008 IEEE Region 10 Conference, pp.1-5, 2008.
K. Roy, S. Mukhopadhyay, and H. Mahmoodi-Meimand, “Leakage current mechanisms and leakage reduction techniques in deepsubmicrometer CMOS circuits,” Proc. IEEE, vol.91, no. 2, pp. 305-327, Feb. 2003.
Pawar Chander, Pokala Santhosh, Prasad Kurhe, “VLSI DESIGN OF FULL SUBTRACTOR USING MULTI-THRESHOLD CMOS TO REDUCE LEAKAGE CURRENT AND GROUND BOUNCE NOISE,” ISSN, Volume-2, Issue-2, 2015.
## Co- Authors
Nikhil Devkar 

Dikshant Bhatt 
