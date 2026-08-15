# Project 002 – LabVIEW Calculations and Logic

## Project Overview

This project consists of three Virtual Instruments (VIs) developed using National Instruments LabVIEW. The laboratory exercises focus on applying graphical programming techniques to mathematical calculations, random number generation, comparison logic, Boolean indicators, and engineering calculations.

The project contains three separate LabVIEW exercises:

1. **Problem 1 – Sphere Surface Area and Volume**
2. **Problem 2 – Random Number Comparison**
3. **Problem 3 – Resistor Tolerance Calculation**

Each exercise required the development of a Front Panel and Block Diagram to perform the assigned calculation or programming task.

---

## Project Objectives

The objectives of this project were to:

- Develop Virtual Instruments using LabVIEW.
- Perform mathematical and engineering calculations.
- Use numerical controls and indicators.
- Use mathematical constants such as π.
- Generate random numbers between 0 and 1.
- Compare numerical values.
- Use Boolean logic to control an LED.
- Calculate maximum and minimum resistance values.
- Observe data flow through a LabVIEW Block Diagram.
- Use LabVIEW Highlight Execution to observe program execution.
- Test the developed VIs and observe their results.

---

## Software Used

- National Instruments LabVIEW

---

# Problem 1 – Sphere Surface Area and Volume

## Objective

The first exercise required developing a Virtual Instrument that calculates the **surface area and volume of a sphere**.

The only input required is the sphere diameter, represented by **d**.

The radius is calculated using:

**r = d / 2**

The volume is calculated using:

**V = 4/3 × π × r³**

The surface area is calculated using:

**S = 4 × π × r²**

The VI contains:

- One numeric control for the sphere diameter.
- One numeric indicator for volume.
- One numeric indicator for surface area.

---

## Problem 1 – Development Process

### Step 1 – Create the Input

A numeric control was created for the sphere diameter and labeled:

**d**

This provides the input value used by the VI.

### Step 2 – Calculate the Radius

The diameter is divided by 2 to determine the radius:

**r = d / 2**

### Step 3 – Calculate the Volume

The radius is used in the sphere volume equation:

**V = 4/3 × π × r³**

The mathematical constant π is used as part of the calculation.

### Step 4 – Calculate the Surface Area

The radius is also used to calculate the surface area:

**S = 4 × π × r²**

### Step 5 – Display the Results

Two numeric indicators were added to the Front Panel:

- **Volume**
- **Surface**

The resulting values are displayed to the user.

---

## Problem 1 – Result

The completed VI successfully calculates the surface area and volume of a sphere from a user-provided diameter.

![Problem 1 – Sphere Surface Area and Volume](../Screenshots/Screenshot%202026-08-15%20123927.png)

---

# Problem 2 – Random Number Comparison

## Objective

The second exercise required developing a Virtual Instrument that generates two random numbers between **0 and 1** and compares their values.

The two values are displayed using meters labeled:

- **Random Number 1**
- **Random Number 2**

The maximum range of each meter was set to **1**.

A square Boolean LED is used to indicate the comparison result.

When:

**Random Number 1 > Random Number 2**

the Boolean indicator shows the ON state.

Otherwise, the Boolean indicator shows the OFF state.

---

## Problem 2 – Development Process

### Step 1 – Generate Random Number 1

A LabVIEW random number function was used to generate a numerical value between 0 and 1.

The value was connected to a meter labeled:

**Random Number 1**

### Step 2 – Generate Random Number 2

A second random number function was used to generate another value between 0 and 1.

The value was connected to a second meter labeled:

**Random Number 2**

### Step 3 – Configure the Meters

The maximum range of both meters was changed to:

**1**

This allows the meters to represent the complete range of the generated random values.

### Step 4 – Compare the Random Numbers

A comparison function was used to determine whether:

**Random Number 1 > Random Number 2**

### Step 5 – Control the Boolean Indicator

The comparison result was connected to a square Boolean LED.

The LED indicates the result of the comparison.

### Step 6 – Test the VI

The VI was run several times to observe the changing random values and corresponding Boolean results.

### Step 7 – Observe Data Flow

The Block Diagram was also observed using **Highlight Execution** to watch the flow of data through the program.

---

## Problem 2 – Result

The completed VI successfully generates two random numbers, displays the values on meters, compares the values, and uses a Boolean indicator to show the comparison result.

![Problem 2 – Random Number Comparison](../Screenshots/Screenshot%202026-08-15%20123941.png)

---

# Problem 3 – Resistor Tolerance Calculation

## Objective

The third exercise required developing a Virtual Instrument that calculates the **maximum and minimum resistance values** for a given resistance and tolerance.

The Front Panel contains:

- **Resistance Value**
- **Tolerance in %**
- **MAX Resistance**
- **MIN Resistance**

The VI uses the resistance value and tolerance percentage to determine the acceptable maximum and minimum resistance values.

---

## Problem 3 – Development Process

### Step 1 – Create the Resistance Input

A numeric control was created for the resistor value and labeled:

**Resistance Value**

### Step 2 – Create the Tolerance Input

A second numeric control was created for the tolerance percentage and labeled:

**Tolerance in %**

### Step 3 – Convert the Tolerance

The tolerance percentage is converted into its corresponding decimal value for use in the calculation.

### Step 4 – Calculate the Maximum Resistance

The tolerance is applied to the resistance value to determine the upper resistance limit.

The result is displayed using the:

**MAX Resistance**

numeric indicator.

### Step 5 – Calculate the Minimum Resistance

The tolerance is applied in the opposite direction to determine the lower resistance limit.

The result is displayed using the:

**MIN Resistance**

numeric indicator.

### Step 6 – Test the VI

The VI was tested using resistance and tolerance values to verify the calculated maximum and minimum resistance values.

---

## Problem 3 – Result

The completed VI calculates and displays the maximum and minimum resistance values based on the specified resistance and tolerance.

![Problem 3 – Resistor Tolerance](../Screenshots/Screenshot%202026-08-15%20124002.png)

---

# LabVIEW Development Process

This project followed a structured development process for each Virtual Instrument:

1. **Review the problem requirements**
2. **Identify the required inputs and outputs**
3. **Create and label Front Panel controls**
4. **Create numeric indicators and Boolean indicators**
5. **Build the Block Diagram**
6. **Connect the required mathematical and logical functions**
7. **Run and test the VI**
8. **Observe the output**
9. **Troubleshoot and verify the results**
10. **Use Highlight Execution when required to observe data flow**
11. **Document the completed Virtual Instrument**

This process provided practical experience moving from a written engineering requirement to a functional graphical programming solution.

---

# Project Results

The three Virtual Instruments were successfully developed to perform their assigned functions.

### Problem 1

Calculated:

- Sphere volume
- Sphere surface area

### Problem 2

Implemented:

- Random Number 1 generation
- Random Number 2 generation
- Numerical comparison
- Boolean LED indication
- Data-flow observation

### Problem 3

Calculated:

- Maximum resistance
- Minimum resistance

---

# Skills Demonstrated

## Technical Skills

- National Instruments LabVIEW
- Graphical Programming
- Virtual Instrument Development
- Mathematical Calculations
- Numerical Data Manipulation
- Random Number Generation
- Comparison Logic
- Boolean Logic
- Front Panel Development
- Block Diagram Development
- Testing and Validation
- Highlight Execution
- Troubleshooting

## Engineering Skills

- Engineering Calculations
- Mathematical Analysis
- Logical Thinking
- Problem Solving
- Data Interpretation
- Attention to Detail
- Systematic Testing

---

# Project Files

## Lab Report

The complete laboratory report is included in this project repository.

## LabVIEW Source Files

The LabVIEW Virtual Instrument files are located in the `LabVIEW` folder:

1. `4.2 Surface Area and Volume of a Sphere-Prob1.vi`
2. `4.2 Surface Area and Volume of a Sphere-Prob2.vi`
3. `4.2 Surface Area and Volume of a Sphere-Prob3.vi`

## Screenshots

The Front Panel and Block Diagram screenshots are located in the `Screenshots` folder.

---

# What I Learned

This project strengthened my understanding of LabVIEW graphical programming and the process of developing Virtual Instruments from engineering requirements.

I gained practical experience creating numerical controls and indicators, performing mathematical calculations, using mathematical constants, generating random values, comparing numerical data, implementing Boolean logic, and calculating engineering values.

The project also reinforced the importance of testing, observing program execution, troubleshooting, and verifying that a Virtual Instrument produces the expected results.

---

# Conclusion

Project 002 provided practical experience applying LabVIEW to several different engineering and programming problems.

The three exercises demonstrated how graphical programming can be used to perform mathematical calculations, process numerical data, implement comparison and Boolean logic, and solve engineering-related calculations.

The project also demonstrated a structured approach to developing, testing, observing, and documenting Virtual Instruments.

---

# Reference

Laboratory instructions and requirements provided for the LabVIEW assignment.
