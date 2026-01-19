# Final Laboratory Exam

## Overview
This project implements an Arduino-to-Python client system where a push button on an Arduino sends a Serial signal to a Python program, which then calls an HTTP API endpoint to control a remote LED system.

---

## Objectives
- Detect a valid push-button press on Arduino  
- Send a single debounced signal via Serial  
- Process Serial input using Python  
- Trigger an API request based on the received signal  

---

## System Behaviors
- Arduino detects a button press and sends one signal only  
- The signal represents the assigned group number  
- Python listens continuously to the Serial port  
- Python sends an HTTP request to `/led/group/<number>/toggle`  
- Arduino does not make HTTP requests or control LEDs  

---

## Output
The Python client displays:
- Group number received  
- API endpoint called  
- API response status (success or error)  

---

## Other Requirements
- One button press equals one API request  
- Long button presses must not generate repeated requests  
- All Serial input must be validated  
- Invalid input returns an error message  
