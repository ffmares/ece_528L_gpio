# ECE 528/L - Robotics and Embedded Systems with Lab
**CSU Northridge**

**Department of Electrical and Computer Engineering**

## GPIO Lab

### Overview

The General Purpose Input/Output Lab is an introduction to GPIO functions on the MSP432 LaunchPad. This lab effectively introduces simple logic, such as, reading input from the two switches and controlling LED outputs. 

By the completion of this lab, we were able to:
* Configure the I/O ports on the MSP432 LaunchPad using the C programming language
* Utilze the built-in user buttons and LEDs attached to the LaunchPad
* Manipulate the peripheral modules (PMODs) by physical connection to the I/O ports
* Create LED patterns and analyze the I/O ports by viewing the memory-mapped registers

### Components Used

| Description | Quantity | Manufacturer |
| ----------- | -------- | ------------ |
| MSP432 Launch Pad | 1 | Texas Instruments |
| USB-A to Micro-USB Cable | 1 | N/A |
| PMOD 8LD | 1 | Diligent |
| PMOD SWT | 1 | Diligent |
| Jumper Wires | 4+ | N/A |

### Author Contribution
                   
| Lab Report Contributions| Group Member | Implementation Contributions | Group Member |
| ---- | ------------ | ------- | ------- |
|Overview | Feranmi | Source Code | Feranmi |
| Components Used | Feranmi | Robot Demonstration | Brandon |
| Analysis and Results | Brandon |
| Known Issues and Limitations | Brandon 
| Author Contribution | Brandon & Feranmi |
| References | Feranmi |

### References
[1] Digilent, “Pmod SWT Reference Manual.” Accessed: Oct. 9, 2026. [Online]. Available: Pmod SWT reference manual.

[2] Digilent, “Pmod 8LD Reference Manual.” Accessed: Oct. 9, 2026. [Online]. Available: Pmod 8LD reference manual.

[3] Texas Instruments, Code Composer Studio User’s Guide, ver. 20.2.0. Accessed: Oct. 9, 2026. [Online]. Available: Code Composer Studio documentation.

[4] Microsoft, “Documentation for Visual Studio Code.” Accessed: Oct. 9, 2026. [Online]. Available: Visual Studio Code documentation.

[5] Texas Instruments, MSP432P401R SimpleLink Microcontroller LaunchPad Development Kit (MSP-EXP432P401R) User’s Guide, SLAU597F, Mar. 2018. Accessed: Oct. 9, 2026. [Online]. Available: MSP432 LaunchPad user’s guide.

[6] Texas Instruments, Robot Systems Learning Kit (TI-RSLK) User Guide, SEKP166, 2019. Accessed: Oct. 9, 2026. [Online]. Available: TI-RSLK user guide.



(Professor Notes) The GPIO lab interfaces with the following:

* User buttons and LEDs of the TI MSP432 LaunchPad
* PMOD SWT (4 Slide Switches) - [Product Link](https://digilent.com/reference/pmod/pmodswt/start)
* PMOD 8LD (8 LEDs) - [Product Link](https://digilent.com/shop/pmod-8ld-eight-high-brightness-leds/)
