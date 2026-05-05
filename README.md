# Virtual-_lab_simple-pendulum
Virtualization of simple pendulum experiment for determining acceleration due to gravity, amplitude effect and dumping effect through visualization 

README: Virtual Physics Laboratory (Simple Pendulum)
Meru University of Science and Technology
This repository contains the frontend architecture for the Virtual Physics Lab, specifically designed for the Simple Pendulum Experiment. This project is a core component of digital innovation within the Competency-Based Education (CBE) framework, aimed at providing high-fidelity laboratory access through hardware abstraction.
1. Virtualization vs. Simulation
Unlike a standard simulation that uses code to approximate physics, this system employs Virtualization:
•	Apparatus Virtualization: The physical simple pendulum, stopwatch, and meter rule are abstracted into a digital "Virtual Machine" for physics.
•	Environment Virtualization: The laboratory bench and manual procedures are virtualized into a web-based dashboard, ensuring that the student follows the exact same logical steps as they would in a physical lab.
•	Deterministic Outcomes: By using high-fidelity demonstrations, the system eliminates the "noise" of software-calculated physics, ensuring students focus on the experimentation process and data analysis.

2. Core Modules
A. Virtual Control Panel
The "Hypervisor" of the lab. It manages the state of the experiment:
•	Part Selector: Switches between different experimental configurations (Part A, B, and C).
•	Parameter Manager: Allows users to configure physical constants (Length, Mass, etc.) which then "boots" the corresponding virtual experiment.
B. Virtual Observation Deck
A responsive 16:9 viewport that provides the visual output of the virtualized apparatus. It is designed for maximum clarity and cross-device compatibility.
C. Interactive Data Layer
A digital logging system where students record observations.
•	Real-time Input: Dynamic tables that mirror a physical laboratory notebook.
•	Tabbed Navigation: Organized sections for different experimental runs to prevent data clutter.

3. Technical Specifications
•	UI Framework: Semantic HTML5 and Modular CSS3.
•	Design System: Meru University Institutional Branding (Green/Gold palette).
•	Responsiveness: Mobile-first architecture using CSS Grid and Flexbox to ensure the lab is accessible on smartphones, tablets, and desktops.
•	Optimization: High-performance rendering with a focus on low-latency state changes between experimental parameters.

 4. Installation & Deployment
This is a standalone web-based virtualization system.
1.	Clone the repository.
2.	Open index.html in any modern web browser (Chrome, Firefox, Edge, or Safari).
3.	Dependencies: No local installation is required. The system pulls icons from FontAwesome and typography from Google Fonts via CDN.

5. Project Context
•	Developer: Meshack Kiptoo
•	Project Title: Final Year Capstone – Virtual Laboratory System
•	Objective: To bridge the gap between theoretical physics and practical learning through ICT integration.

6. License & Usage
This software is intended for academic use at Meru University of Science and Technology. All institutional branding and experimental protocols are the property of the Department of Physical Sciences. 
Design Note: The UI uses a custom-built responsive viewer to ensure that the virtualized experiment maintains its aspect ratio regardless of the student's screen size, preserving the integrity of the visual measurements.

