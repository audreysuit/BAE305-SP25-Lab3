# Laboratory Report for Lab 1 of BAE305 Spring 2025
# Lab 3 – Let's Switch : Transistors as Switches
* By: Abby Phillips and Audrey Suit
* Submitted: February 17th, 2025

# Summary
The goal of this lab is to learn how to use bipolar junction transistors (BJTs) as switches to control current in simple circuits. We built and tested circuits using diodes, LEDs, resistors, and a TIP31C transistor to observe its behavior as a switch. We measured resistor values with a digital multimeter and used voltage measurements to calculate current through various components. First, we connected an LED directly to a switch and recorded voltage drops. Then, we introduced a transistor to control the LED and analyzed its operation in different modes. Finally, we extended the circuit to control a small motor, adjusting its speed with a potentiometer. By the end of the lab, we had a better understanding of transistor switching behavior, the impact of circuit design on current flow, and how to use experimental data to evaluate transistor performance. Most measured values were within expected ranges, and the transistor functioned effectively as a switch.

# Materials

Resistors: 2.2Ω, 270Ω, 1kΩ, LED, Sliding Switch, Electric Motor, NTE 125 Diode, 1kΩ Trimmer Potentiometer, TIP31C Transistor  




# Assembly Procedures


# Test Equipment
1. DC Power Supply

# Test Procedures


# Test Results


**Resistor Values Table**  
| Color Code        | Expected Value (Ω) | Tolerance (%) | Measured Value (Ω) | Within Tolerance |
|-------------------|--------------------|--------------|--------------------|------------------|
| Red Violet Brown | 270Ω               | 10           | 267.7Ω             | Yes              |
| Brown Black Red  | 1kΩ                | 10           | 993Ω               | Yes              |
| Red Red Gold     | 2.2Ω               | 10           | 2.7Ω               | No               |


Circuit 1

### **Test Point Voltages**
| Test Point | Voltage (Switch On) | Voltage (Switch Off) |
|------------|---------------------|----------------------|
| T2         | 1.878V              | 5.00V               |
| T3         | 0.001V              | 3.698V              |

### **Component Voltage Drops**
| Component | Voltage Across (Switch On) | Voltage Across (Switch Off) |
|-----------|----------------------------|-----------------------------|
| R1        | 3.128V                     | 0V                          |
| LED1      | 1.875V                     | 0.063V                      |
| S1        | 0V                          | 0V                          |

### **Current Measurements**
| Component | Current Through (Switch On) | Current Through (Switch Off) |
|-----------|-----------------------------|------------------------------|
| LED1      | 11.65 mA                     | 0.01 mA                      |


Circuit 2


### **Test Point Voltages**
| Test Point | Voltage (Switch On) | Voltage (Switch Off) |
|------------|---------------------|----------------------|
| T2         | 1.889V              | 4.99V               |
| T3 (VCE)   | 0.016V              | 3.683V              |
| T5 (VBE)   | 0.695V              | 0V                  |
| T6         | 5.00V               | 0V                  |

### **Component Voltage Drops**
| Component | Voltage Across (Switch On) | Voltage Across (Switch Off) |
|-----------|----------------------------|-----------------------------|
| R1        | 3.105V                     | 0V                          |
| LED1      | 1.873V                     | 0.035V                      |
| R2        | 4.30V                      | 0V                          |
| S1        | 0V                          | 0V                          |

### **Current Measurements**
| Component  | Current Through (Switch On) | Current Through (Switch Off) |
|------------|-----------------------------|------------------------------|
| LED1 (IC)  | 11.53 mA                     | 0.01 mA                      |
| R2 (IB)    | 4.33 mA                      | 0.02 mA                      |


Circuit 3

### **Test Point Voltages**
| Test Point | Voltage (Dim LED) | Voltage (Midpoint 1) | Voltage (Midpoint 2) | Voltage (Bright LED) |
|------------|------------------|------------------|------------------|------------------|
| T2         | 4.68V            | 1.947V           | 1.898V           | 1.892V           |
| T3 (VCE)   | 3.008V           | 0.076V           | 0.026V           | 0.016V           |
| T5 (VBE)   | 0.568V           | 0.63V            | 0.658V           | 0.694V           |
| T6         | 0.582V           | 0.858V           | 2.058V           | 4.98V            |

### **Component Voltage Drops**
| Component | Voltage Across (Dim LED) | Voltage Across (Midpoint 1) | Voltage Across (Midpoint 2) | Voltage Across (Bright LED) |
|-----------|--------------------------|--------------------------|--------------------------|--------------------------|
| R1        | 0.32V                    | 3.035V                   | 3.096V                   | 3.098V                   |
| LED1      | 1.662V                   | 1.864V                   | 1.873V                   | 1.874V                   |
| R2        | 0.015V                   | 0.228V                   | 1.396V                   | 4.30V                    |

### **Current Measurements**
| Component  | Current Through (Dim LED) | Current Through (Midpoint 1) | Current Through (Midpoint 2) | Current Through (Bright LED) |
|------------|--------------------------|--------------------------|--------------------------|--------------------------|
| LED1 (IC)  | 1.22 mA                   | 11.3 mA                   | 11.45 mA                  | 11.53 mA                  |
| R2 (IB)    | 0.04 mA                   | 0.24 mA                   | 1.42 mA                   | 4.35 mA                   |

### **Gain (IC / IB)**
| Condition | Gain (IC / IB) |
|-----------|---------------|
| Dim LED   | 30.5          |
| Midpoint 1| 47.1          |
| Midpoint 2| 8.07          |
| Bright LED| 2.65          |

Circuit 4

### **Test Point Voltages**
| Test Point | Voltage (Slow Motor) | Voltage (Midpoint 1) | Voltage (Midpoint 2) | Voltage (Fast Motor) |
|------------|----------------------|----------------------|----------------------|----------------------|
| T2         | 4.76V                | 4.72V                | 4.68V                | 4.61V                |
| T3 (VCE)   | 3.23V                | 2.22V                | 0.802V               | 0.211V               |
| T5 (VBE)   | 0.646V               | 0.665V               | 0.69V                | 0.706V               |
| T6         | 1.315V               | 1.488V               | 1.83V                | 2.585V               |

### **Component Voltage Drops**
| Component | Voltage Across (Slow Motor) | Voltage Across (Midpoint 1) | Voltage Across (Midpoint 2) | Voltage Across (Fast Motor) |
|-----------|----------------------------|----------------------------|----------------------------|----------------------------|
| R1        | 0.210V                     | 0.256V                     | 0.304V                     | 0.328V                     |
| M1        | 1.52V                       | 2.63V                      | 3.926V                     | 4.44V                      |
| R2        | 0.669V                      | 0.822V                     | 1.138V                     | 1.882V                     |

### **Current Measurements**
| Component  | Current Through (Slow Motor) | Current Through (Midpoint 1) | Current Through (Midpoint 2) | Current Through (Fast Motor) |
|------------|----------------------------|----------------------------|----------------------------|----------------------------|
| M1 (IC)    | 91.3 mA                     | 117.2 mA                    | 149.3 mA                    | 158.7 mA                    |
| R2 (IB)    | 0.67 mA                     | 0.89 mA                     | 1.17 mA                     | 1.87 mA                     |

### **Gain (IC / IB)**
| Condition  | Gain (IC / IB) |
|------------|---------------|
| Slow Motor | 136.3         |
| Midpoint 1 | 131.7         |
| Midpoint 2 | 127.6         |
| Fast Motor | 84.9          |







# Discussion

2a-Do the instruments agree with the expected value?

Each capacitor value fell within the expected range for its capacitance, except for capacitor 3 and 4 which were out of range. This could be due to an innacurate reading of the capacitance, a damaged capacitor, or errors in DMM measurement. All resistance values fell within tolerance.

2b- Does polarity affect the measurement of the electrolytic capacitor?

Polarity did not affect the measurement. If anything, it was a negligible amount that could be attributed to measurement error. This indicates that the capacitors were likely non-polarized since we could connect the DMM leads in either direction with no affect on the result.

Discussion Question 1: Do the instruments agree with each other in part 3? Why?

They agreed with each other as the voltage output shown on the D.C. Power Supply's screen matched the measured value from the Fluke DMM. Thus, the Fluke DMM verified that the D.C. Power Supply was delivering its reported voltage.

Discussion Question 2: Do the instruments agree in part 4 for the oscilliscope/function generator? Why?

When measuring the amplitude and frequency, the instruments didn't produce the exact same values. However, the difference was so small, it could be counted as negligible and it can be determined that the values were more or less the same. The only measurable difference was in the DMM amplitude reading, which was innacurate since it cannot depict a sine wave. Additionally, as we increased the frequency values, the amplitude of the sine wave decreased, when it should have remained the same since the voltage source did not change.

In addition to the discussion questions, we learned the importance of identifying and connecting the right ports when using the Fluke DMM and testing resistance and capacitance values. This is important so the correct values are being measured, and so you do not damage any of the equipment by short circuiting it. Safety is essential, so we must be aware of the circuits we are creating and how they are connected. Finally, measuring equipment can be prone to error, so it is important to check and verify results using multiple, or the most precise methods.

# Conclusion

In summary, this lab aimed to incorporate commonly used circuit components and devices into a test procedure. We verified values for components like resistors and capacitors and devices like the Function Generator. By using many different tools, we are now familiarity with the usage and purpose of the Oscilloscope Tektronix TS2012, Fluke DMM, D.C. Power Supply, and Function Generator. The completion and learning attained by this lab will help us in future labs as we expand on the usage of these instruments with more complex projects and purposes. Most resistors and capacitors were in tolerance, the voltage output of the DCPS was close to the set values, and the function generator set values were similar to those collected by the 4 different measurement methods.

