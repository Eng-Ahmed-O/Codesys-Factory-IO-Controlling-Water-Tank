💧 Water Tank Control System

PLC-Based Industrial Automation Project

📌 Overview

This project is an industrial water tank control system developed using CODESYS for PLC programming and Factory I/O for 3D process simulation. Communication between both platforms is established using the OPC UA protocol.

The system simulates a real industrial tank process with analog control, dual operating modes, and real-time monitoring.

🏗️ System Description

The project represents a closed-loop water tank system that includes:

Filling valve

Discharge valve

Level sensor

Flow meter

Digital monitoring displays

Start, Stop, and Reset controls

All control logic is implemented in CODESYS and connected to the simulated plant in Factory I/O through OPC UA for real-time data exchange.

⚙️ Operating Modes
🟢 Manual Mode

In Manual Mode, the operator directly controls the system using two potentiometers:

One potentiometer controls the filling valve opening percentage.

The second potentiometer controls the discharge valve opening percentage.

The tank level changes dynamically according to the difference between filling flow and discharge flow.
Both tank level and flow rate are displayed continuously on digital displays.

This mode simulates direct operator control in an industrial process.

🔵 Automatic Mode

In Automatic Mode, the tank operates automatically between two predefined level limits:

The tank fills steadily until it reaches a level of 250.

Once the upper limit is reached, filling stops and discharge begins.

The tank level decreases until it reaches 50.

Once the lower limit is reached, discharge stops and filling resumes.

The cycle repeats continuously.

This mode simulates automatic level regulation using programmed logic inside the PLC.

🎛️ Control Features

Analog valve control using percentage-based signals

Real-time tank level monitoring

Real-time flow rate monitoring

Start function to enable system operation

Stop function to safely disable outputs

Reset function to return the system to its initial state

The project demonstrates practical implementation of industrial automation concepts including analog control, process sequencing, and PLC-to-simulation communication.

🎯 Project Purpose

This project was developed to simulate a realistic industrial water tank control system using professional automation tools. It demonstrates:

PLC programming using IEC 61131-3 standards

Analog process control

Dual-mode operation (Manual / Automatic)

Industrial communication via OPC UA

Real-time system monitoring and control
