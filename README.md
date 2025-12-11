# 2D Residential Thermal-Sensor Simulation System

This project implements a dual WebView system for simulating thermal sensors in residential environments with movable characters and sensors.

## Features

- **Dual WebView Interface**:
  - WebView A: Top-down view of the residential environment
  - WebView B: Side view of the same room with switchable perspectives

- **Interactive Elements**:
  - Movable character with multiple states (standing, sitting, lying, crawling, fallen)
  - Placable thermal sensors with adjustable angles and field of view
  - Various furniture types that can be placed in the environment

- **Thermal Sensor Simulation**:
  - 256x256 thermal sensor output grid
  - Field of view visualization
  - Occlusion detection from furniture
  - Heat signature based on character state

- **Status Monitoring**:
  - Character position and state
  - Danger level detection
  - Movement status
  - Occlusion status

## Controls

- **Object Placement**: Use the dropdown to select between character, sensor, or furniture placement
- **Character States**: Change character state using the dropdown (standing, sitting, lying, crawling, fallen)
- **Mouse Controls**: Click and drag to move objects
- **Keyboard Controls**: Arrow keys to move the character

## Room Types

- Bedroom
- Living Room
- Kitchen
- Bathroom

## Sensor Features

- Adjustable position and angle
- Configurable field of view
- Real-time thermal output based on character presence
- Occlusion detection from furniture

## How to Run

1. Install dependencies: `npm install`
2. Start the server: `npx serve .`
3. Open your browser and navigate to the provided URL (typically http://localhost:3000)

## Technical Details

- Uses HTML5 Canvas for rendering
- Implements ray-casting for thermal sensor simulation
- Real-time collision and occlusion detection
- Responsive UI with dual views synchronization

## Use Cases

- Elderly care monitoring system simulation
- Home security system prototyping
- Thermal sensor algorithm development
- Human behavior analysis in residential environments