# Laboratory Report for Lab 1 of BAE305 Spring 2025
# Lab 3 – Let's Switch : Transistors as Switches
* By: Abby Phillips and Audrey Suit
* Submitted: February 17th, 2025

# Summary
The goal of this lab is to learn how to use bipolar junction transistors (BJTs) as switches to control current in simple circuits. We built and tested circuits using diodes, LEDs, resistors, and a TIP31C transistor to observe its behavior as a switch. We measured resistor values with a digital multimeter and used voltage measurements to calculate current through various components. First, we connected an LED directly to a switch and recorded voltage drops. Then, we introduced a transistor to control the LED and analyzed its operation in different modes. Finally, we extended the circuit to control a small motor, adjusting its speed with a potentiometer. By the end of the lab, we had a better understanding of transistor switching behavior, the impact of circuit design on current flow, and how to use experimental data to evaluate transistor performance. Most measured values were within expected ranges, and the transistor functioned effectively as a switch.

# Materials

Resistors: 2.2Ω, 270Ω, 1kΩ, LED, Sliding Switch, Electric Motor, NTE 125 Diode, 1kΩ Trimmer Potentiometer, TIP31C Transistor, Screwdriver




# Assembly Procedures

### Part 1: LED Driving Circuits

Using the Fluke digital multimeter, we measured the actual resistance of the 270 Ω, 1 kΩ, and 2.2 kΩ resistors by attaching the multimeter probes to their terminals with alligator clips. The labeled resistance was verified using the resistor color code. After verifying the resistor values, we proceeded to construct the circuit below on a standard prototyping breadboard.

![image](https://github.com/user-attachments/assets/7efe37d6-9e24-40b1-ad59-e12995962bc7)

Instead of using a physical switch, we connected a wire that we could plug and unplug as needed for testing. 

After taking measurements detailed in the Test Procedures section of this lab report, we built the next circuit below on the breadboard.

![image](https://github.com/user-attachments/assets/fd9ed978-ba90-4d89-986d-15f4de22a728)

We again used a wire as a switch.

After taking measurements also detailed in the Test Procedures, we built the circuit below on the breadboard.

![image](https://github.com/user-attachments/assets/51b995fb-a0f5-4d96-a954-46b94395d2f3)

A small screwdriver is required to adjust the potentiometer, and thus the circuit to create varying levels of LED brightness.

### Part 2 : Motor Driving Circuit

After completing part one, we built the motor driving circuit shown below.

![image](https://github.com/user-attachments/assets/aedef844-4d57-484c-b99d-41064e64cf6c)

We rested the motor on our wire-holding plastic case so it would be level with the circuit and keep it from straining the wires attaching it to the breadboard. This also stabilized it while it was turned on.
As with the LED brightness, the motor speed was controlled by using a small screwdriver to adjust the potentiometer.


# Test Equipment
1. DC Power Supply
2. Fluke Digital Multimeter

# Test Procedures


# Test Results


**Resistor Values Table**  
| Color Code        | Expected Value (Ω) | Tolerance (%) | Measured Value (Ω) | Within Tolerance |
|-------------------|--------------------|--------------|--------------------|------------------|
| Red Violet Brown | 270Ω               | 10           | 267.7Ω             | Yes              |
| Brown Black Red  | 1kΩ                | 10           | 993Ω               | Yes              |
| Red Red Gold     | 2.2Ω               | 10           | 2.7Ω               | No               |


### Circuit 1 -----------------------------------------------------------------------------------------------------------------

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


### Circuit 2 -----------------------------------------------------------------------------------------------------------------


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


### Circuit 3 -----------------------------------------------------------------------------------------------------------------

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

### Circuit 4 -----------------------------------------------------------------------------------------------------------------

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

### LED Driving Circuits

Discussion Question 1: How does the current through the LED compare between circuits 1 and 2? 
In Circuit 1, the current through the LED with the switch on was 11.65 mA. In Circuit 2, the current through the LED was the switch was on was 11.53 mA. The values are separated by a very small value, just 0.13 mA. With small errors, it could be approximated that the circuits produce the same value across the LED when the switch is on.

Discussion Question 2: The datasheet mentions a maximum voltage drop (VCE) of 1.2V at saturation. We would like a much smaller value, such as the fraction of a volt that you measured in the first circuit across the switch, S1, when it is on. How does your measured VCE compare to the one listed in the datasheet? Do you think we are operating this transistor in the saturation region? 
Our voltage drop was 0.016V, which is smaller than the maximum voltage drop of 1.2 V. We also saw a high current, 11.53mA, so we are in the saturation region.

### Motor Driving Circuits

Discussion Question 1: What is the voltage drop (VCE) across the transistor (Q1) when the motor is in the Fast setting? How does this compare with the circuit that drove the LED? 
The VCE across the transistor Q1 was 0.211V when the motor was in the "fast" setting. This voltage drop is higher than the one across the LED, as the current is much higher.

Discussion Question 2: How much current is going through the motor in the Fast setting? How does this compare to the current that the LED circuit used? If the switch was only just barely able to meet the current requirements of the LED, could it support the motor directly or would the transistor switch be required? 
When the motor was in the "fast" setting, the current going through it was 158.7 mA. Comparitively, the LED circuit used 11.53 mA when the LED was in the "bright" setting. The switch would not be able to support the motor directly and the transistor switch would be required to ensure enough current would be supplied to run the motor.

# Conclusion
