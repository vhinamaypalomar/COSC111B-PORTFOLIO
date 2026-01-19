# Laboratory Activity 7 – Controlling Arduino using FastAPI

## Objectives
- Understand and implement Arduino Serial Connection.
-  Utilize Python as a tool for implementing serial connection, and implement a HTTP-based solution using FastAPI.
-  Create a simple circuit what will implement bi-directional connection between Arduino and Python using Fast API

## Description
This activity integrates Arduino with FastAPI, allowing LEDs to be controlled through HTTP requests while maintaining physical button control on the Arduino.

## What Was Implemented
- RESTful API for LED control
- Serial communication between FastAPI and Arduino
- Bidirectional hardware interaction

## Code Summary
**Arduino**
- Handles Serial commands from FastAPI
- Supports individual and group LED control
- Detects physical button presses

**FastAPI**
- Exposes HTTP endpoints for LED control
- Sends Serial commands to Arduino
- Simulates IoT-style device control
