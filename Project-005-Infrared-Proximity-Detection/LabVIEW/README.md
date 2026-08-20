# Project 005 – LabVIEW Source File

## Overview

This folder contains the LabVIEW Virtual Instrument developed for the infrared proximity detection project.

The VI processes a phototransistor-related voltage and determines whether the simulated optical sensing condition represents an object-detected or object-not-detected state.

---

# Source File

## File

`5_2 Infrared Based Proximity Detection.vi`

## Open Source File

[Open LabVIEW VI](5_2%20Infrared%20Based%20Proximity%20Detection.vi)

---

# Purpose

The Virtual Instrument converts a numerical sensor-related voltage into a logical proximity-detection result.

The application provides:

- Voltage input
- Threshold comparison
- Conditional processing
- Text status message
- Boolean status indication
- Continuous monitoring through a While Loop
- Programmatic Stop control

---

# Front Panel

The Front Panel contains the primary user-interface components.

| Component | Function |
|---|---|
| Voltage across photo Transistor | Represents the measured sensor voltage |
| Message | Displays the detection result |
| Status Indicator | Provides visual detection status |
| Stop | Stops execution of the While Loop |

---

# Detection Threshold

The VI uses a threshold of:

**3.5 V**

The incoming voltage is compared with this value to determine which case should execute.

---

# Block Diagram Development

## Step 1 – While Loop

The processing logic is placed inside a While Loop to allow continuous execution.

The loop continues until the user activates the Stop control.

---

## Step 2 – Time Delay

A Time Delay function is included in the loop.

The laboratory specifies:

**0.1 seconds**

This controls loop execution and helps reduce unnecessary CPU utilization.

---

## Step 3 – Voltage Comparison

The input voltage is compared against the 3.5 V threshold.

The result of the comparison produces a Boolean value.

---

## Step 4 – Case Structure

The Boolean result controls a Case Structure.

The Case Structure determines:

- Which message is displayed
- Which state is sent to the Status Indicator

---

## Step 5 – Status Output

The Front Panel provides two forms of detection feedback.

### Object Detected

- Message: `Object Detected`
- Status Indicator: ON / Red

### Object Not Detected

- Message: `Object not detected`
- Status Indicator: OFF / Green

---

# Program Flow

```text
Voltage Input
     |
     v
3.5 V Comparison
     |
     v
Boolean Result
     |
     v
Case Structure
   /       \
 Case A    Case B
   |          |
   v          v
Message     Message
   |          |
   +----------+
       |
       v
Status Indicator
```

---

# Development Process

1. Review the Multisim voltage measurements.
2. Determine the detection threshold.
3. Create the LabVIEW Front Panel.
4. Add the voltage numeric control.
5. Add the Message string indicator.
6. Add the Status Indicator.
7. Configure indicator colors.
8. Create a While Loop.
9. Move the controls and indicators inside the loop.
10. Add the Time Delay.
11. Implement the 3.5 V comparison.
12. Add a Case Structure.
13. Configure both cases.
14. Add string constants for the detection messages.
15. Add Boolean constants for the Status Indicator.
16. Run the VI.
17. Test multiple voltage conditions.
18. Verify both detection states.
19. Stop the VI programmatically.

---

# LabVIEW Concepts Demonstrated

- Graphical Programming
- Virtual Instruments
- Front Panel Design
- Block Diagram Development
- Numeric Controls
- String Indicators
- Boolean Indicators
- Comparison Logic
- Case Structures
- While Loops
- Time Delay
- Conditional Processing
- Data Flow
- Testing
- Troubleshooting

---

# Related Project Files

Return to the main project:

[Project 005 Main README](../README.md)

View the Multisim circuit:

[Multisim Source Files](../Multisim/)

View the screenshots:

[Project Screenshots](../Screenshots/)

---

# Purpose of This Folder

This folder preserves the original LabVIEW `.vi` source file used to implement the software portion of Project 005.

The source file demonstrates how sensor-related voltage data can be processed using graphical programming and converted into useful detection status information.
