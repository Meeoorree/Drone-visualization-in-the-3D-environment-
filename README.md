# Drone-visualization-in-the-3D-environment-
This project is an interactive 3D drone swarm simulator built with Three.js, featuring real-time editing, timeline navigation, and comparison modes.
It simulates autonomous drone behavior across multiple time points with editable telemetry, states, and real-world-inspired attributes. Originally it was my assignmetn for the Data Visualization course in the university, but then extended into a fully-featured visualization tool.

# Features
My visualization has the following features:

Fully modeled campus scene with terrain, buildings, tracks, trees, water, lights

Real-time environment with shadows, fog, reflections, grid

Drone models with propellers, signal sphere, status and video LEDs

Drone Telemetry & State Animation

Position & Velocity mapping to 3D movement & orientation

Live propeller rotation

Signal intensity ↔ glowing sphere & pulse effect

Video feedback status (on/off LED)

State-based LED colors (Hovering, Attacking, Parachute, etc.)

Time-Series Data Navigation

Supports TP1 → TP6 time points

Timeline slider & step buttons

Play/Pause time evolution

Free-flight interpolation mode (smooth spline path curve)

Motion trails leave flight traces

Live Data Editing

Click a drone → open edit panel → modify:

| Editable Field   | Description              |
| ---------------- | ------------------------ |
| State            | Drone mission status tag |
| Battery (%)      | Remaining energy         |
| Signal Strength  | Comms power (1–5)        |
| Video Feedback   | Camera feed state        |
| Position (X/Y/Z) | 3D coordinates           |
| Velocity (X/Y/Z) | Motion vector            |

Original vs Modified Comparison

# How to run the code
Open .html file, maybe for for some regions VPN would be required;
