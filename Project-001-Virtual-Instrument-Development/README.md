# Project 001 – LabVIEW Virtual Instrument Development

## Overview

This project focuses on the creation of three Virtual Instruments (VIs) using National Instruments LabVIEW. The lab was designed to reinforce fundamental programming concepts and data manipulation techniques through numerical calculations, unit conversion, algebraic calculations, and conditional logic.

The three VIs developed in this project are:

1. Four-input Sum and Average Calculator
2. Celsius-to-Fahrenheit Converter
3. Algebraic Calculation with Conditional LED

The lab also required properly labeled controls and indicators, organized Front Panels and Block Diagrams, and the use of a While Loop for programmatic control.

---

## Objectives

- Develop three Virtual Instruments using LabVIEW.
- Practice fundamental graphical programming techniques.
- Perform numerical calculations.
- Calculate the sum and average of four inputs.
- Convert Celsius temperature to Fahrenheit.
- Implement an algebraic calculation using three inputs.
- Apply conditional Boolean logic.
- Turn an LED ON when the calculated value of X is less than zero.
- Use a While Loop for programmatic control.
- Maintain neat and properly labeled Front Panels and Block Diagrams.

---

## Software

- National Instruments LabVIEW

---

# VI 1 – Sum and Average

The first VI accepts four numeric inputs and calculates the sum and average of all four values.

### Functions

- Four numeric inputs
- Sum calculation
- Average calculation
- Numeric indicators for the results

### Skills Demonstrated

- Numerical data manipulation
- Mathematical operations
- Graphical programming
- Numeric controls and indicators

---

# VI 2 – Celsius to Fahrenheit Conversion

The second VI converts a temperature from degrees Celsius to degrees Fahrenheit.

### Conversion Formula

**F = (C × 1.8) + 32**

Where:

- **C** = Celsius temperature
- **F** = Fahrenheit temperature

### Skills Demonstrated

- Unit conversion
- Mathematical calculations
- Numerical data manipulation
- Graphical programming

---

# VI 3 – Algebraic Calculation and Conditional LED

The third VI performs the following algebraic calculation:

**X = (A + B) × (C - 1)**

The controls are labeled **A, B, and C**, and the calculated value of **X** is displayed using a numeric indicator.

The VI also includes a conditional Boolean element. The LED turns **ON when X is less than zero**.

### Skills Demonstrated

- Algebraic calculations
- Numerical data processing
- Boolean logic
- Conditional decision-making
- Numeric indicators
- LED indicators

### Logic

Calculate X
     |
     v
Is X < 0?
   /   \
 Yes    No
  |      |
  v      v
LED ON  LED OFF
Program Control

The lab required the use of a While Loop to stop the VI programmatically.

The assignment also emphasized:

Properly labeling controls and indicators
Keeping the Front Panel neat
Keeping the Block Diagram organized
Aligning numeric controls
Maintaining consistent spacing
Results

The three Virtual Instruments were successfully developed to perform their assigned functions.

The project demonstrated:

Sum and average calculations
Celsius-to-Fahrenheit conversion
Algebraic calculations
Conditional Boolean logic
LED status indication
Graphical programming
Programmatic control using While Loops
Project Gallery
VI 1 – Sum and Average

The first VI accepts four numeric inputs and displays their sum and average.

VI 2 – Celsius to Fahrenheit

The second VI converts Celsius to Fahrenheit using:

F = (C × 1.8) + 32

VI 3 – Algebraic Calculation

The third VI calculates:

X = (A + B) × (C - 1)

VI 3 – Conditional LED

The final screenshot demonstrates the conditional LED behavior based on the calculated value of X.

Skills Demonstrated
Technical Skills
LabVIEW
Graphical Programming
Virtual Instrument Development
Numerical Calculations
Boolean Logic
Data Manipulation
Unit Conversion
Testing and Validation
Troubleshooting
Technical Documentation
Engineering Skills
Problem Solving
Mathematical Analysis
Logical Thinking
Systematic Testing
User Interface Organization
Attention to Detail
Project Files
Lab Report

The complete laboratory report is available in this repository.

LabVIEW Files

The LabVIEW source file(s) used for this project are available in the LabVIEW folder.

Screenshots

Screenshots showing the Front Panels and Block Diagrams are available in the Screenshots folder.

What I Learned

This project strengthened my understanding of LabVIEW's graphical programming environment and provided practical experience developing Virtual Instruments for different computational tasks.

Through the three VIs, I practiced numerical calculations, unit conversion, algebraic expressions, Boolean logic, and programmatic control using While Loops.

The project also reinforced the importance of properly labeled controls and indicators, organized Front Panels and Block Diagrams, testing, and systematic problem solving.

Reference

Essentials of Building Virtual Instruments with LabVIEW and Arduino for Lab Automation Applications.

Reference
