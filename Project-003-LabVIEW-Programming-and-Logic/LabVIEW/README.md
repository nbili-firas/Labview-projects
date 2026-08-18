# Project 003 – LabVIEW Source Files

## Overview

This folder contains the four LabVIEW Virtual Instrument source files developed for Project 003.

Each source file corresponds to one of the four laboratory problems and demonstrates a different programming, mathematical, or logical application.

---

# Problem 1 – Floating-Point Calculations and Division-by-Zero Detection

### Source File

[Open Problem 1 VI](4_5%20Construct%20a%20VI%20Pro1.vi)

### File Name

`4_5 Construct a VI Pro1.vi`

### Purpose

This VI accepts two floating-point inputs, X and Y, performs subtraction and division, and detects when Y equals zero.

### Functions

- Accept X and Y
- Calculate X - Y
- Calculate X / Y
- Detect Y = 0
- Control a Boolean LED
- Operate inside a While Loop

### Concepts Demonstrated

- Floating-point data
- Mathematical operations
- Comparison logic
- Boolean indicators
- While Loops
- Data flow
- Testing and troubleshooting

---

# Problem 2 – Integer Detection

### Source File

[Open Problem 2 VI](4_5%20Construct%20a%20VI%20Pro2.vi)

### File Name

`4_5 Construct a VI Pro2.vi`

### Purpose

This VI evaluates a floating-point numeric input and determines whether the entered value represents an integer.

### Functions

- Accept a floating-point input
- Process the numerical value
- Determine whether the value is an integer
- Control a Boolean LED
- Operate inside a While Loop

### Concepts Demonstrated

- Floating-point processing
- Numerical operations
- Conditional logic
- Boolean indicators
- While Loops
- Testing and validation

---

# Problem 3 – Feet-to-Meters and Miles Conversion

### Source File

[Open Problem 3 VI](4_5%20Construct%20a%20VI%20Pro3.vi)

### File Name

`4_5 Construct a VI Pro3.vi`

### Purpose

This VI converts a measurement in feet to meters and miles.

### Conversion Relationships

**1 meter = 3.281 feet**

**1 mile = 5280 feet**

### Functions

- Accept feet as input
- Calculate meters
- Calculate miles
- Display both converted values
- Operate inside a While Loop

### Concepts Demonstrated

- Unit conversion
- Mathematical operations
- Numeric controls
- Numeric indicators
- Data flow
- While Loops

---

# Problem 4 – Random Number Guessing Game

### Source File

[Open Problem 4 VI](4_5%20Construct%20a%20VI%20Pro4.vi)

### File Name

`4_5 Construct a VI Pro4.vi`

### Purpose

This VI allows the user to guess an integer between 1 and 5 and compares the user's choice with a generated random number.

### Functions

- Accept a user guess
- Generate a random number
- Process the random value into the required range
- Display the generated value
- Compare the generated value with the user's guess
- Control the Right Number Boolean LED
- Operate inside a While Loop

### Concepts Demonstrated

- Random number generation
- Numerical comparison
- Boolean logic
- Conditional logic
- Numeric controls and indicators
- While Loops
- Testing

---

# Development Process

The source files were developed using the following process:

1. Review the laboratory requirements.
2. Identify the required inputs and outputs.
3. Design the Front Panel.
4. Add and label numeric controls.
5. Add and label numeric and Boolean indicators.
6. Build the Block Diagram.
7. Add the required mathematical and logical functions.
8. Connect the data flow.
9. Add a While Loop for programmatic operation.
10. Add the stop control.
11. Run and test the VI.
12. Test different input conditions.
13. Troubleshoot unexpected results.
14. Verify the program output.
15. Check for coercion dots.
16. Organize the completed Block Diagram.

---

# Source File Organization

| Problem | Source File | Function |
|---|---|---|
| Problem 1 | `4_5 Construct a VI Pro1.vi` | Floating-point calculations and division-by-zero detection |
| Problem 2 | `4_5 Construct a VI Pro2.vi` | Integer detection |
| Problem 3 | `4_5 Construct a VI Pro3.vi` | Feet-to-meters and miles conversion |
| Problem 4 | `4_5 Construct a VI Pro4.vi` | Random number guessing and comparison |

---

# Related Documentation

Return to the main project documentation:

[Project 003 Main README](../README.md)

View the project screenshots:

[Project 003 Screenshots](../Screenshots/)

View the laboratory report:

[Project 003 Lab Report](../Lab-Report.pdf)

---

# Purpose of This Folder

This folder preserves the original LabVIEW Virtual Instrument source files developed for Project 003.

The `.vi` files provide access to the graphical programs behind the screenshots and documentation and demonstrate the LabVIEW development work completed during the laboratory exercises.
