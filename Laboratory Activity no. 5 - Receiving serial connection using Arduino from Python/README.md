# Laboratory Activity 5 – Receiving serial connection using Arduino from Python

## Objectives
- Understand and implement Arduino Serial Connection.
- Utilize Python as a tool for implementing serial connection.
- Create a simple circuit that can be controlled using Serial connection using Arduino and Python.

## Description
This activity establishes one-way Serial communication where Python sends commands to Arduino to control multiple LEDs.

## What Was Implemented
- Modular Arduino code using a header file
- Python menu-based LED controller
- Serial command processing

## Code Summary
**Arduino**
- Uses a header file to manage LED functions
- Processes single-character Serial commands
- Toggles LEDs individually or collectively

**Python**
- Uses the `pyserial` library
- Sends commands via Serial
- Receives and displays Arduino responses
