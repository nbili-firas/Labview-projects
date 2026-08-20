# Project 005 – Multisim Circuit Simulation

## Overview

This folder contains the National Instruments Multisim circuit simulation developed for Project 005.

The simulation models an infrared-based proximity detection concept using an optical transmitter and phototransistor receiver.

The circuit was used to study how interruption of the simulated light path affects the receiver circuit and its measured voltage.

The resulting voltage behavior was then used to develop and test the LabVIEW Virtual Instrument included in this project.

---

# Source File

## File

`5_2 Infrared Based Proximity Detection Using LabVIEW®.ms14`

## Open Multisim File

[Open Multisim Circuit](5_2%20Infrared%20Based%20Proximity%20Detection%20Using%20LabVIEW%C2%AE.ms14)

---

# Purpose of the Circuit

The Multisim circuit provides the electronic simulation portion of the proximity detection system.

The system models:

```text
Optical Transmitter
       |
       v
Simulated Light Path
       |
       v
Phototransistor Receiver
       |
       v
Electrical Response
       |
       v
Voltage Measurement
       |
       v
LabVIEW Detection Logic
```

---

# Circuit Operation

## Light Path Available

When the transmitting side is active and the simulated light reaches the phototransistor:

1. The phototransistor responds to the light.
2. The electrical behavior of the receiver circuit changes accordingly.
3. The receiver-side LED indicates the circuit condition.
4. The phototransistor voltage can be measured.

---

## Light Path Interrupted

Opening the transmitter-side switch simulates an object obstructing the light path.

When the optical path is interrupted:

1. The transmitter condition changes.
2. The phototransistor no longer receives the simulated light.
3. The receiver circuit changes state.
4. The voltage across the phototransistor changes.
5. The changed voltage can be interpreted as an object-detection condition.

---

# Measurement Process

A Digital Multimeter was connected to the simulated circuit to observe the phototransistor-related voltage.

The process consisted of:

1. Build the transmitter and receiver circuit.
2. Position the optical components appropriately.
3. Run the simulation.
4. Test the unobstructed condition.
5. Record the voltage.
6. Simulate an obstruction.
7. Record the resulting voltage.
8. Compare the operating conditions.
9. Use the measurements to establish the LabVIEW threshold.

---

# Detection Threshold

Analysis of the simulated measurements led to a detection threshold of:

**3.5 V**

This value was subsequently implemented in the LabVIEW VI.

The threshold allows the software to convert the simulated electrical measurement into a logical proximity-detection state.

---

# Multisim Concepts Demonstrated

- Electronic Circuit Simulation
- Optical Sensor Simulation
- Phototransistor Operation
- Photodiode / Optical Source Behavior
- Infrared Proximity Detection
- Circuit Switching
- LED Status Indication
- Digital Multimeter Measurements
- Voltage Measurement
- Sensor Circuit Analysis
- Simulation Testing

---

# Integration with LabVIEW

The Multisim and LabVIEW portions of this project serve different but connected purposes.

| Multisim | LabVIEW |
|---|---|
| Simulates the electronic circuit | Processes sensor-related voltage |
| Models optical sensing behavior | Evaluates voltage threshold |
| Provides voltage measurements | Implements decision logic |
| Demonstrates circuit response | Displays detection messages |
| Tests sensor conditions | Controls status indication |

This workflow demonstrates how circuit simulation data can be used to design and validate a software-based monitoring application.

---

# Related Project Files

Return to the main project:

[Project 005 Main README](../README.md)

View the LabVIEW VI:

[LabVIEW Source Files](../LabVIEW/)

View the screenshots:

[Project Screenshots](../Screenshots/)

---

# Purpose of This Folder

This folder preserves the original Multisim `.ms14` circuit simulation used for Project 005.

Together with the LabVIEW source file, it documents both the electronic simulation and software-monitoring portions of the infrared proximity detection project.
