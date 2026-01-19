# Laboratory Activity 6 – Bidirectional Control Using Arduino and Python

## Objectives
- Understand and implement Arduino Serial Connection.
- Utilize Python as a tool for implementing serial connection.
- Create a simple circuit what will implement bi-directional connection between Arduino and Python.

## Description
This activity enables two-way communication where Arduino sends button press events to Python, and Python responds with LED control commands.

## What Was Implemented
- Button-to-Python event transmission
- Python-to-Arduino command response
- LED state toggling

## Code Summary
**Arduino**
- Detects button presses using edge detection
- Sends identifiers via Serial
- Receives commands to toggle LEDs

**Python**
- Listens for incoming Serial data
- Sends corresponding commands back to Arduino
- Demonstrates real-time bidirectional interaction
