# Laboratory Activity 2 – Working with Analog Signals

## Objectives
- Discuss analog signals and its implemention in a Arduino circuit. 
- Understrand analog to digital signal conversion using the map() function.

## Description
This activity demonstrates how Arduino reads analog signals from a potentiometer and converts them into PWM signals to control LED brightness.

## What Was Implemented
- Potentiometer as an analog input device
- LED brightness control using PWM
- Gradual fade-in and fade-out effects

## Code Summary
- Reads analog values using `analogRead()`
- Maps ADC values (0–1023) to PWM range (0–255)
- Uses nested loops for smooth brightness transitions
- Demonstrates real-time analog signal modulation
