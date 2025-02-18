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

Using the Fluke digital multimeter, we measured the actual resistance of the 270 Ω, 1 kΩ, and 2.2 kΩ resistors by attaching the multimeter probes to their terminals with alligator clips. The labeled resistance was verified using the resistor color code. After verifying the resistor values, we proceeded to construct the circuit illustrated in Figure 1.1 and 1.2 below on a standard prototyping breadboard.

![image](https://github.com/user-attachments/assets/7efe37d6-9e24-40b1-ad59-e12995962bc7)
<p align="left"><em>Figure 1.1: Schematic of Circuit 1. An LED directly connected to a switch. </em></p>

![image](https://github.com/user-attachments/assets/54aa4002-e577-45a0-b0a3-bfef55357ac6)
<p align="left"><em>Figure 1.2: Image of Circuit 1. An LED directly connected to a switch represented by the red wire which could be connected and disconnected as needed for switch on/switch off measurements. </em></p>


After taking measurements of Circuit 1, detailed in the Test Procedures section of this lab report, we built the next circuit illustrated in Figure 2.1 and 2.2 below on the breadboard.

![image](https://github.com/user-attachments/assets/fd9ed978-ba90-4d89-986d-15f4de22a728)
<p align="left"><em>Figure 2.1: Schematic of Circuit 2. An LED driven by a transistor with a fixed current. </em></p>

![image](https://github.com/user-attachments/assets/7ccadc78-e362-483d-b361-cde290b46e78)
<p align="left"><em>Figure 2.2: Image of Circuit 2. An LED driven by a transistor with a fixed current. The switch is shown via the red wire in the bottom right in the off position. </em></p>

After taking measurements for Circuit 2, also detailed in the Test Procedures, we built the circuit illustrated in Figure 3.1 and 3.2 below on the breadboard.

![image](https://github.com/user-attachments/assets/51b995fb-a0f5-4d96-a954-46b94395d2f3)
<p align="left"><em>Figure 3.1: Schematic of Circuit 3. Controlling LED current using a transistor. </em></p>

![image](https://github.com/user-attachments/assets/456bafd9-6106-4d6a-8e6e-d11c306d3dbc)
<p align="left"><em>Figure 3.2: Image of Circuit 3. An LED driven by a transistor with a fixed current.  </em></p>

As the potentiometer has a resistance of 1kΩ, it is represented on the schematic with "R3" and a resistor symbol. A small screwdriver is required to adjust the potentiometer, and thus the circuit to create varying levels of LED brightness. 


### Part 2 : Motor Driving Circuit

After completing part one, we built the motor driving circuit shown below.

![image](https://github.com/user-attachments/assets/aedef844-4d57-484c-b99d-41064e64cf6c)
<p align="left"><em>Figure 4.1: Schematic of Circuit 4. Controlling motor current and speed using a transistor. </em></p>

![image](https://github.com/user-attachments/assets/f90f95a9-7dff-4269-944c-252461786d44)
<p align="left"><em>Figure 4.2: Image of Circuit 4. Controlling motor current and speed using a transistor. </em></p>

We rested the motor on our wire-holding plastic case so it would be level with the circuit and keep it from straining the wires attaching it to the breadboard. This also stabilized it while it was turned on.
As with the LED brightness, the motor speed was controlled by using a small screwdriver to adjust the potentiometer.


# Test Equipment
1. DC Power Supply
2. Fluke Digital Multimeter

# Test Procedures
## Part 1: LED Driving Circuits
### Step 1: Measure Resistor Values
1. We verified the resistor values using the steps below, and recorded the measurements in Table 1. This is important to have an accurate reference for expected values in lab.
2. Turn on the Fluke DMM and set it to the resistance (Ω) mode.
3. Connect the DMM probes to the opposite ends of the resistor (the terminals).
4. Record the actual resistance values in Table 1.

### Step 2: Build the Circuit (Figure 1)
1. We followed the below steps to get measurements for a circuit with an LED directly connected to a switch
2. Assemble the circuit as shown in Figure 1.1 & 1.2.
3. Power the circuit using a DC power supply set to 5V. We confirmed T1 was close to 5V. Our value was exactly 5V.
4. Use the DMM in voltage mode (V) to measure voltages at each test point (T2, T3, etc.). We placed the black (common) probe on the ground (labeled T4 in figure 1.1) and placed the red probe on the test points listed above. 
5. Using the DMM, also measure voltage across R1, LED1, and S1 by attaching probes to each terminal of the respective component.  
7. We recorded the above values in Table 2. We recorded all measurements with the switch on and off, by disconnecting the wire between T3 and T4 for off and connecting it for on.
8. Calculate the current through R1 using Ohm’s Law and the measured resistor and voltage values: V=IR. A component with a known resistance must be used to calculate current.  We also measured the current by interrupting the circuit and connecting the DMM in series in current (mA) mode.

### Step 3: Build the Circuit (Figure 2)
1. Construct the circuit as shown in Figure 2.1 and 2.2.
2. Power the circuit with 5VDC and confirm T1 and T7 are close to 5V. Our values were exactly 5V.
3. Measure the voltages at each test point (T2, T3, T5, T6) with respect to ground (T4) by placing the black probe on T4 and the red probe on the test points.
4. Calculate the currents through the resistors using measured voltages. We also measured the current by interrupting the circuit and connecting the DMM in series in current (mA) mode.
5. Record the voltage and current values in Table 3. We recorded all measurements with the switch on and off, by disconnecting the wire between T7 and T6 for off and connecting it for on.
6. Determine the voltage drop across the transistor (VCE) and compare it with the datasheet.
7. Adjust the power supply to verify transistor saturation behavior. Current should increase with increasing voltage

## Part 2 - Controlling LED Current Using a Transistor
### Step 1: Build the Circuit (Figure 3)
1. Assemble the circuit as per Figure 3.1 and 3.2.
2. To test the function of the potentiometer, we used a screwdriver to change the resistance and saw the LED turn on and off
3. We took measurements at 4 levels: Dim LED, Midpoint 1&2, and Bright LED. Dim LED was the point at which the LED is just barely visible. Bright LED is when the LED just reached full brightness.
4. To take measurements, we set the Fluke DMM to voltage mode (V) and measure voltages at T2, T3, T5, and T6 with respect to ground. Also measure the voltage accross R1, LED1 and R2. 
6. Record the values at four different brightness levels in Table 4.
7. We also measured current by interrupting the circuit before LED1 and R2 by using the DMM in series set to Current mode (mA). Calculate gain using: Gain= Ic/Ib
    a. Create a graph showing IB, IC, Gain, and VCE vs. input voltage. We did this in excel. See figure 5

## Part 3 - Motor Driving Circuit
### Step 1: Build the Circuit (Figure 4)
1. Assemble the circuit with the motor shown in figure 4.1 and 4.2.
2. To test the function of the potentiometer, we used a screwdriver to change the resistance and saw the motor move faster and slower.
3. Again, we took measurements at 4 levels: slow motor, Midpoint 1&2, and fast motor. Slow motor was the point at which the motor is just barely moving. Fast motor was at the point in which it just reached its max speed.
4. To take measurements, we set the Fluke DMM to voltage mode (V) and measure voltages at T2, T3, T5, and T6 with respect to ground. Also measure the voltage accross R1, M1 and R2.
5. Adjust the potentiometer to change the motor speed. We also measured current by interrupting the circuit before M1 and R2 by using the DMM in series set to Current mode (mA). Calculate gain using: Gain= Ic/Ib
6. Record voltage and current values in Table 5.
7. Create a graph showing IB, IC, Gain, and VCE vs. input voltage. We did this in excel. See Figure 6.

# Test Results


**Resistor Values Table**  
| Color Code        | Expected Value (Ω) | Tolerance (%) | Measured Value (Ω) | Within Tolerance |
|-------------------|--------------------|--------------|--------------------|------------------|
| Red Violet Brown | 270Ω               | 10           | 267.7Ω             | Yes              |
| Brown Black Red  | 1kΩ                | 10           | 993Ω               | Yes              |
| Red Red Gold     | 2.2Ω               | 10           | 2.7Ω               | No               |
<p align="left"><em>Table 1: Measured, real values of the resistors used in the lab. The 270Ω and 1kΩ resistors are in tolerance. The 2.2Ω resistor is not. </em></p>

### Circuit 1 ---------------------------------------------------------------------------------------------            

### **Test Point Voltages**
| Test Point | Voltage (Switch On) | Voltage (Switch Off) |
|------------|---------------------|----------------------|
| T2         | 1.878V              | 5.00V               |
| T3         | 0.001V              | 3.698V              |
<p align="left"><em> Table 2.1: Test point measurements of Circuit 1 with an LED directly connected to a switch. Both T2 and T3 voltage measurements increase when the switch is off since there is no current through the circuit. </em></p>

### **Component Voltage Drops**
| Component | Voltage Across (Switch On) | Voltage Across (Switch Off) |
|-----------|----------------------------|-----------------------------|
| R1        | 3.128V                     | 0V                          |
| LED1      | 1.875V                     | 0.063V                      |
| S1        | 0V                         | 0V                          |
<p align="left"><em> Table 2.2: Component voltage drop measurements of Circuit 1 with an LED directly connected to a switch. The voltage drop accross both R1 and LED1 both decrease to about zero when the switch is off since no current is flowing in the circuit. </em></p>

### **Table 2.3: Current Measurements**
| Component | Current Through (Switch On) | Current Through (Switch Off) |
|-----------|-----------------------------|------------------------------|
| LED1      | 11.65 mA                     | 0.01 mA                      |
<p align="left"><em> Table 2.3: Current through the LED of Circuit 1 with an LED directly connected to a switch. The current in through the LED goes to about zero when the switch is off since the switch creates an open circuit. </em></p>

### Circuit 2 -----------------------------------------------------------------------------------------------------------------


### **Table 3.1: Test Point Voltages**
| Test Point | Voltage (Switch On) | Voltage (Switch Off) |
|------------|---------------------|----------------------|
| T2         | 1.889V              | 4.99V               |
| T3 (VCE)   | 0.016V              | 3.683V              |
| T5 (VBE)   | 0.695V              | 0V                  |
| T6         | 5.00V               | 0V                  |
<p align="left"><em> Table 3.1: Test point measurements of Circuit 2 with an LED connected through a transistor. Both T2 and T3 voltage measurements increase when the switch is off, however, T5 and T6 decrease to zero. More current is moving across T1 and T2, but zero current is moving through T6 and T5 since the switch creates an open circuit through that part. </em></p>

### **Table 3.2: Component Voltage Drops**
| Component | Voltage Across (Switch On) | Voltage Across (Switch Off) |
|-----------|----------------------------|-----------------------------|
| R1        | 3.105V                     | 0V                          |
| LED1      | 1.873V                     | 0.035V                      |
| R2        | 4.30V                      | 0V                          |
| S1        | 0V                          | 0V                          |
<p align="left"><em> Table 3.2:  Component voltage drop measurements of Circuit 2 with an LED connected through a transistor. Both T2 and T3 voltage measurements increase when the switch is off, however, T5 and T6 decrease to zero. More current is moving across T1 and T2, but zero current is moving through T6 and T5 since the switch creates an open circuit through that part. </em></p>

### **Table 3.3: Current Measurements**
| Component  | Current Through (Switch On) | Current Through (Switch Off) |
|------------|-----------------------------|------------------------------|
| LED1 (IC)  | 11.53 mA                     | 0.01 mA                      |
| R2 (IB)    | 4.33 mA                      | 0.02 mA                      |


### Circuit 3 -----------------------------------------------------------------------------------------------------------------

### **Table 4.1: Test Point Voltages**
| Test Point | Voltage (Dim LED) | Voltage (Midpoint 1) | Voltage (Midpoint 2) | Voltage (Bright LED) |
|------------|------------------|------------------|------------------|------------------|
| T2         | 4.68V            | 1.947V           | 1.898V           | 1.892V           |
| T3 (VCE)   | 3.008V           | 0.076V           | 0.026V           | 0.016V           |
| T5 (VBE)   | 0.568V           | 0.63V            | 0.658V           | 0.694V           |
| T6         | 0.582V           | 0.858V           | 2.058V           | 4.98V            |

### **Table 4.2: Component Voltage Drops**
| Component | Voltage Across (Dim LED) | Voltage Across (Midpoint 1) | Voltage Across (Midpoint 2) | Voltage Across (Bright LED) |
|-----------|--------------------------|--------------------------|--------------------------|--------------------------|
| R1        | 0.32V                    | 3.035V                   | 3.096V                   | 3.098V                   |
| LED1      | 1.662V                   | 1.864V                   | 1.873V                   | 1.874V                   |
| R2        | 0.015V                   | 0.228V                   | 1.396V                   | 4.30V                    |

### **Table 4.3: Current Measurements**
| Component  | Current Through (Dim LED) | Current Through (Midpoint 1) | Current Through (Midpoint 2) | Current Through (Bright LED) |
|------------|--------------------------|--------------------------|--------------------------|--------------------------|
| LED1 (IC)  | 1.22 mA                   | 11.3 mA                   | 11.45 mA                  | 11.53 mA                  |
| R2 (IB)    | 0.04 mA                   | 0.24 mA                   | 1.42 mA                   | 4.35 mA                   |

### **Table 4.4: Gain (IC / IB)**
| Condition | Gain (IC / IB) |
|-----------|---------------|
| Dim LED   | 30.5          |
| Midpoint 1| 47.1          |
| Midpoint 2| 8.07          |
| Bright LED| 2.65          |

![image](https://github.com/user-attachments/assets/ca9bce63-e80a-481a-a248-2aa69c8049f8)
<p align="left"><em>Figure 5: Graph showing IB, IC, VCE, and Gain for vairous input voltages of a LED.  </em></p>

### Circuit 4 -----------------------------------------------------------------------------------------------------------------

### **Table 5.1: Test Point Voltages**
| Test Point | Voltage (Slow Motor) | Voltage (Midpoint 1) | Voltage (Midpoint 2) | Voltage (Fast Motor) |
|------------|----------------------|----------------------|----------------------|----------------------|
| T2         | 4.76V                | 4.72V                | 4.68V                | 4.61V                |
| T3 (VCE)   | 3.23V                | 2.22V                | 0.802V               | 0.211V               |
| T5 (VBE)   | 0.646V               | 0.665V               | 0.69V                | 0.706V               |
| T6         | 1.315V               | 1.488V               | 1.83V                | 2.585V               |

### **Table 5.2: Component Voltage Drops**
| Component | Voltage Across (Slow Motor) | Voltage Across (Midpoint 1) | Voltage Across (Midpoint 2) | Voltage Across (Fast Motor) |
|-----------|----------------------------|----------------------------|----------------------------|----------------------------|
| R1        | 0.210V                     | 0.256V                     | 0.304V                     | 0.328V                     |
| M1        | 1.52V                       | 2.63V                      | 3.926V                     | 4.44V                      |
| R2        | 0.669V                      | 0.822V                     | 1.138V                     | 1.882V                     |

### **Table 5.3: Current Measurements**
| Component  | Current Through (Slow Motor) | Current Through (Midpoint 1) | Current Through (Midpoint 2) | Current Through (Fast Motor) |
|------------|----------------------------|----------------------------|----------------------------|----------------------------|
| M1 (IC)    | 91.3 mA                     | 117.2 mA                    | 149.3 mA                    | 158.7 mA                    |
| R2 (IB)    | 0.67 mA                     | 0.89 mA                     | 1.17 mA                     | 1.87 mA                     |

### **Table 5.4: Gain (IC / IB)**
| Condition  | Gain (IC / IB) |
|------------|---------------|
| Slow Motor | 136.3         |
| Midpoint 1 | 131.7         |
| Midpoint 2 | 127.6         |
| Fast Motor | 84.9          |


![Image](https://github.com/user-attachments/assets/49b81638-3beb-4bb9-aa5b-0e468af136e4)
<p align="left"><em>Figure 6: Graph showing IB, IC, VCE, and Gain for vairous input voltages of a motor.  </em></p>




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
