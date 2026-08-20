# Project 004 – LabVIEW Source File

## Overview

This folder contains the LabVIEW Virtual Instrument source file developed for Project 004.

The VI was created to monitor and analyze light intensity using graphical programming, numerical indicators, graphical displays, Boolean indicators, mathematical relationships, and user-defined limits.

---

# Source File

## Light Intensity Meter Using Photocell

### File

`4_6 Light Intensity Meter using Photocell.vi`

### Open Source File

[Open Light Intensity Meter VI](4_6%20Light%20Intensity%20Meter%20using%20Photocell.vi)

---

# Purpose

The VI was developed to provide a graphical monitoring system for light-intensity-related data.

The application demonstrates how LabVIEW can be used to:

- Monitor sensor-related values
- Display numerical information
- Display changing signals graphically
- Evaluate user-defined limits
- Control Boolean indicators
- Apply mathematical relationships
- Generate simulated signals
- Observe changing system behavior

---

# Photocell Behavior

The VI is based on the electrical behavior of a photocell.

The photocell demonstrates the following relationship:

**Increasing Light → Decreasing Resistance**

**Decreasing Light → Increasing Resistance**

The changing resistance affects the voltage produced by the associated voltage-divider circuit.

---

# Development Process

## Step 1 – Identify Inputs and Outputs

The required parameters and display elements were identified.

The VI required visual tools for:

- Numeric values
- Graphical data
- Boolean status indication
- User-defined monitoring limits

---

## Step 2 – Design the Front Panel

The Front Panel was developed as the user interface for the monitoring system.

It provides visual access to the values and indicators needed to observe system behavior.

---

## Step 3 – Develop the Block Diagram

The Block Diagram was constructed using LabVIEW graphical programming functions.

The Block Diagram processes data and connects the calculations, indicators, and monitoring logic.

---

## Step 4 – Implement Mathematical Relationships

Mathematical functions were used to model the relationship between resistance and voltage in the photocell circuit.

This allowed the electrical behavior of the sensor system to be represented within LabVIEW.

---

## Step 5 – Implement Monitoring Logic

Comparison logic was incorporated to evaluate the monitored value against user-defined limits.

Boolean indicators provide visual feedback based on the comparison results.

---

## Step 6 – Use Express VIs

Express VIs were used to simplify configuration and reduce development time.

These tools allowed signal-generation and processing functions to be added efficiently.

---

## Step 7 – Generate a Test Signal

The **Simulate Signal Express VI** was used to create a sine-wave signal for testing and validation.

This provided a controlled changing input for observing system behavior.

---

## Step 8 – Visualize the Signal

Graphical indicators were used to display the changing signal.

This allowed the behavior of the system to be observed visually.

---

## Step 9 – Test and Validate

The VI was tested to verify:

- Numeric indicators
- Graphical displays
- Boolean indicators
- Threshold logic
- Signal generation
- Mathematical processing

---

# LabVIEW Concepts Demonstrated

- Virtual Instrument Development
- Front Panel Design
- Block Diagram Programming
- Numeric Indicators
- Graphical Indicators
- Boolean Indicators
- Express VIs
- Simulate Signal Express VI
- Comparison Logic
- Conditional Logic
- Mathematical Functions
- Signal Visualization
- Data Processing
- Testing and Validation

---

# Electronics Concepts Demonstrated

- Photocell Operation
- Light Intensity
- Resistance Variation
- Voltage Divider Analysis
- Voltage Measurement
- Sensor Monitoring
- Electrical Data Interpretation

---

# Related Documentation

Return to the main project page:

[Project 004 Main README](../README.md)

View the project screenshots:

[Project 004 Screenshots](../Screenshots/)

---

# Purpose of This Folder

This folder preserves the original LabVIEW source file developed for Project 004.

The `.vi` file provides access to the graphical program behind the screenshots and project documentation and demonstrates the LabVIEW programming completed for the light-intensity monitoring system.
