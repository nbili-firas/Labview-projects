# Project 003 – LabVIEW Programming and Logic

## Project Overview 

Project 003 consists of four Virtual Instruments (VIs) developed using National Instruments LabVIEW. The laboratory exercises focus on numerical calculations, conditional logic, integer detection, unit conversion, random number generation, Boolean indicators, and programmatic control.

The four exercises are:

1. **Problem 1 – Floating-Point Calculations and Division-by-Zero Detection**
2. **Problem 2 – Integer Detection**
3. **Problem 3 – Feet-to-Meters and Miles Conversion**
4. **Problem 4 – Random Number Guessing Game**

Each VI was developed using a Front Panel and Block Diagram and tested to verify the required functionality.

---

## Project Requirements

The laboratory required the following development standards:

- Keep the Front Panel and Block Diagram neat and properly labeled.
- Use a While Loop to stop each VI programmatically.
- Ensure that no coercion dots are present on the Block Diagram.
- Develop and test all required VI files.
- Organize the completed VI files for submission.

---

## Software Used

- National Instruments LabVIEW

---

# Problem 1 – Floating-Point Calculations and Division-by-Zero Detection

## Objective

The first VI accepts two floating-point numbers, **X** and **Y**.

The VI performs the following operations:

- Subtracts Y from X.
- Divides X by Y.
- Displays both calculated results.
- Detects when Y equals zero.
- Uses a Boolean LED to indicate a division-by-zero condition.

### Calculations

Subtraction:

**X - Y**

Division:

**X / Y**

Conditional check:

**Y = 0**

When Y equals zero, the Boolean LED turns ON.

---

## Development Process

1. Create floating-point numeric controls for X and Y.
2. Create an indicator for the subtraction result.
3. Subtract Y from X.
4. Create an indicator for the division result.
5. Divide X by Y.
6. Compare Y with zero.
7. Connect the comparison result to a Boolean LED.
8. Place the program inside a While Loop.
9. Add a stop control for programmatic operation.
10. Test the VI using different X and Y values.
11. Verify the division-by-zero indication.
12. Check the Block Diagram for coercion dots.

### LabVIEW Source File

[Open Problem 1 VI](LabVIEW/4_5%20Construct%20a%20VI%20Pro1.vi)

### Screenshots

![Problem 1 – Test 1](Screenshots/VI_Pro1_1.png)

![Problem 1 – Test 2](Screenshots/VI_Pro1_2.png)

---

# Problem 2 – Integer Detection

## Objective

The second VI determines whether a number entered through a floating-point numeric control represents an integer.

A Boolean LED on the Front Panel indicates whether the entered value is an integer.

---

## Development Process

1. Create a floating-point numeric control.
2. Process the input using the required numerical functions.
3. Determine whether the entered value represents an integer.
4. Connect the result to a Boolean LED.
5. Place the program inside a While Loop.
6. Add a stop control.
7. Test the VI using integer values.
8. Test the VI using non-integer values.
9. Observe the Boolean LED response.
10. Check the Block Diagram for coercion dots.

### LabVIEW Source File

[Open Problem 2 VI](LabVIEW/4_5%20Construct%20a%20VI%20Pro2.vi)

### Screenshots

![Problem 2 – Test 1](Screenshots/VI_Pro2_1.png)

![Problem 2 – Test 2](Screenshots/VI_Pro2_2.png)

---

# Problem 3 – Feet-to-Meters and Miles Conversion

## Objective

The third VI accepts an input value in feet and converts the measurement to both meters and miles.

The laboratory provides the following conversion relationships:

**1 mile = 5280 feet**

**1 meter = 3.281 feet**

### Calculations

Meters:

**Meters = Feet / 3.281**

Miles:

**Miles = Feet / 5280**

---

## Development Process

1. Create a numeric control labeled **Feet**.
2. Divide the feet value by 3.281 to calculate meters.
3. Divide the feet value by 5280 to calculate miles.
4. Create a numeric indicator for meters.
5. Create a numeric indicator for miles.
6. Connect the calculations to their corresponding indicators.
7. Place the program inside a While Loop.
8. Add a stop control.
9. Test the VI using numerical values.
10. Verify the conversion results.
11. Check the Block Diagram for coercion dots.

### LabVIEW Source File

[Open Problem 3 VI](LabVIEW/4_5%20Construct%20a%20VI%20Pro3.vi)

### Screenshot

![Problem 3 – Feet Conversion](Screenshots/VI_Pro3.png)

---

# Problem 4 – Random Number Guessing Game

## Objective

The fourth VI creates a number-guessing application.

The user guesses an integer between **1 and 5**. The VI generates a random number within the required range, displays the generated value, and compares it with the user's guess.

If the two numbers are equal, the **Right Number** Boolean LED turns ON.

---

## Development Process

1. Create a numeric control for the user's guess.
2. Generate a random number.
3. Process the generated value to produce an integer in the required range.
4. Display the generated number using a numeric indicator.
5. Compare the generated number with the user's choice.
6. Connect the comparison result to the **Right Number** Boolean LED.
7. Place the program inside a While Loop.
8. Add a stop control.
9. Run the VI multiple times.
10. Test matching and non-matching conditions.
11. Observe the Boolean LED response.
12. Check the Block Diagram for coercion dots.

### Comparison Logic

**User Guess = Generated Number**

- Equal → LED ON
- Not Equal → LED OFF

### LabVIEW Source File

[Open Problem 4 VI](LabVIEW/4_5%20Construct%20a%20VI%20Pro4.vi)

### Screenshots

![Problem 4 – Test 1](Screenshots/VI_Pro4_1.png)

![Problem 4 – Test 2](Screenshots/VI_Pro4_2.png)

---

# Project Results

The four Virtual Instruments demonstrate different LabVIEW programming concepts.

| Problem | Application | Main Concepts |
|---|---|---|
| Problem 1 | Floating-point calculations | Subtraction, division, comparison logic, Boolean indication |
| Problem 2 | Integer detection | Numerical processing, conditional logic, Boolean indication |
| Problem 3 | Unit conversion | Mathematical operations, numerical inputs and outputs |
| Problem 4 | Number guessing | Random number generation, comparison logic, Boolean indication |

---

# Skills Demonstrated

## Technical Skills

- National Instruments LabVIEW
- Graphical Programming
- Virtual Instrument Development
- Front Panel Design
- Block Diagram Development
- Floating-Point Data Processing
- Mathematical Calculations
- Boolean Logic
- Conditional Logic
- Numerical Comparison
- Random Number Generation
- Unit Conversion
- While Loops
- Data Flow Programming
- Testing and Validation
- Troubleshooting

## Engineering and Problem-Solving Skills

- Mathematical Analysis
- Logical Thinking
- Problem Solving
- Systematic Testing
- Data Interpretation
- Attention to Detail
- Program Development
- Technical Documentation

---

# Project Files

## Lab Report

The complete laboratory report for Project 003 is available below.

[View Project 003 Lab Report](Lab-Report.pdf)

## LabVIEW Source Files

The four original LabVIEW VI files are located in the `LabVIEW` folder.

[View LabVIEW Source Files](LabVIEW/)

## Screenshots

The Front Panel and Block Diagram screenshots are located in the `Screenshots` folder.

[View Project Screenshots](Screenshots/)

---

# What I Learned

This project strengthened my understanding of LabVIEW graphical programming and conditional logic.

Through the four exercises, I gained practical experience working with floating-point values, mathematical calculations, Boolean indicators, unit conversions, random number generation, numerical comparisons, and programmatic control using While Loops.

The project also reinforced the importance of organized Front Panels and Block Diagrams, proper labeling, testing different operating conditions, troubleshooting, verifying results, and maintaining consistent data types to avoid coercion dots.

---

# Conclusion

Project 003 provided practical experience developing LabVIEW Virtual Instruments for several programming and engineering applications.

The exercises demonstrated how graphical programming can be used to perform numerical calculations, evaluate conditions, detect special input conditions, convert measurements, generate random values, and implement decision-making logic.

The project also reinforced a structured approach to designing, testing, troubleshooting, and documenting Virtual Instruments.

---

# Reference

Laboratory instructions and requirements provided for the LabVIEW assignment.
