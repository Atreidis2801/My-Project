# My-Project
Non-INvasive Glucose Monitoring using Gold Nanoparticles
Smart Nano-Sensing System (SNSS)
Non-Invasive Glucose Monitoring via Gold Nanoparticle 
Developed by: Atreyi Barma Majumder
Registration Number: 25BOE10040
Institution: Vellore Institute of Technology, Bhopal
Project Overview
The Smart Nano-Sensing System (SNSS) is a next-generation medical wearable designed to provide continuous, non-invasive glucose monitoring. Moving away from traditional "finger-pricking" methods, this project utilizes Surface Plasmon Resonance (SPR) in functionalized Gold Nanoparticles (AuNPs) embedded in a biocompatible hydrogel patch.
When glucose molecules bind to the nanoparticles, they cause a measurable shift in light absorption. This optical change is captured by a high-precision photodetector, processed via a Kalman filter to remove motion artifacts, and transmitted to a mobile interface for real-time health tracking.
Key Features
1. Nanotechnology-Driven Detection
High Sensitivity: Leverages the optical properties of AuNPs to detect minute glucose concentrations in interstitial fluid.
Reusable Sensing Layer: The chemical binding is designed to be reversible, allowing for continuous 72-hour monitoring per patch.
2. Advanced Signal Processing
Noise Reduction: Integrated Kalman Filter algorithm (Python-based) to eliminate data spikes caused by physical activity or skin stretching.
Adaptive Calibration: Automatically adjusts for skin temperature fluctuations to maintain accuracy.
3. Smart Connectivity & Alerts
Real-time Dashboard: Visualizes glucose trends over a 24-hour period using a custom GUI.
Haptic Emergency Alerts: Immediate vibration and phone notifications if glucose levels cross critical thresholds (Hypoglycemia < 70 mg/dL or Hyperglycemia > 140 mg/dL).
4. Data Integrity & Security
Encrypted Storage: Uses a structured SQLite3 backend to securely store patient logs, timestamps, and physician notes.
User Profiles: Dedicated data management for individual patient metrics (Weight, Age, Medical History).
5. Eco-Friendly Design
Low Power Consumption: Built on the ARM Cortex-M architecture with Bluetooth Low Energy (BLE) to maximize battery life up to 7 days.
Technical Stack
Language: Python 3.x (Signal Processing & Backend)
Libraries: NumPy (Math), Matplotlib (Visualization), SQLite3 (Database)
Architecture: Micro-service based communication between sensor hardware and mobile UI.
Documentation: Mermaid.js for System Design and Architecture.
How to Run the Simulation
Clone the Repository: git clone https://github.com/AtreyiBM/NanoGlucoseMonitor.git
Install Dependencies:
pip install numpy matplotlib
Execute the Filter Test:
python sensor_filter.py
Generate Results Graph:
python generate_dashboard.py

