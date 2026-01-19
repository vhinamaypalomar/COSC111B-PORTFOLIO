# Midterm Laboratory Exam

## Overview
This project implements a **smart lighting system using Arduino** that adjusts LED indicators based on ambient light intensity measured by a photoresistor. The system supports **manual and automatic modes** and allows user interaction via the Serial Monitor.

---

## Objectives
- Measure ambient light intensity using a photoresistor  
- Convert sensor values to percentage (0–100%)  
- Control LEDs based on light thresholds  
- Implement Serial-based mode switching and control  

---

## System Behavior
- Light intensity is read from a photoresistor (0–1023 → 0–100%)
- Only **one LED is active at a time**:
  - **Green** – Low light  
  - **Yellow** – Medium light  
  - **Red** – High light  

---

## Operating Modes

### Manual Mode
- User-defined thresholds via Serial commands:
  - `SET LOW xx`
  - `SET HIGH xx`
- Invalid commands return an error message

### Automatic Mode
- Thresholds adjust automatically based on environment:
  - **Cloudy:** 0%–40%
  - **Normal:** 41%–70%
  - **Bright Sunlight:** 71%–100%

---

## Serial Commands
- `MODE AUTO` – Enable automatic mode  
- `MODE MANUAL` – Enable manual mode  

---

## Output (Every Second)
- Light intensity (%)
- Active LED
- Current mode
- Environment status

---

## Other Requirements
- Threshold updates are restricted by mode
- Only one LED may be active at any time
