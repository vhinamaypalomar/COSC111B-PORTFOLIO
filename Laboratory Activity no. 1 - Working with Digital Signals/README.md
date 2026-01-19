# Laboratory Activity 1 – Working with Digital Signals

## Objectives
- Review Arduino as a device for IoT systems implementation  
- Understand and implement digital signals using Arduino  

## Description
This activity introduces basic digital signal control using Arduino. Multiple LEDs are controlled sequentially to demonstrate how digital outputs operate using HIGH and LOW logic levels.

## What Was Implemented
- Five LEDs connected to digital output pins
- Sequential ON and OFF operation using loops
- Fixed timing control using delays

## Code Summary
- Uses an array to manage multiple LED pins
- Configures all pins as OUTPUT in `setup()`
- Turns LEDs ON and OFF one at a time using `digitalWrite()`
- Demonstrates binary logic behavior and timing control
