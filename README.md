# MSc-Dissertation

# MR Fluid Based Haptic Feedback System

This repository hosts the MSc Robotics dissertation project by **Samanta Suprio Sujoy** from the University of Sheffield.

## 📄 Abstract
This project explores the development of a wearable haptic feedback system using Magnetorheological (MR) fluid. The system generates both **normal and lateral forces** using MR fluid's field-dependent viscosity characteristics. A silicone-based device and peristaltic pump controlled by an Arduino and electromagnet were designed and tested to simulate cutaneous feedback for a user's index finger.

## 🎯 Objectives
- Design a wearable silicone haptic device with embedded fluid channels.
- Use MR fluid to generate haptic forces based on applied magnetic fields.
- Control fluid motion and actuation using Arduino, a relay circuit, a peristaltic pump, and an electromagnet.
- Evaluate system performance using a 6-axis load cell and map it with gripping tasks from a Franka gripper.

## 📐 Key Concepts
- **Hagen–Poiseuille Law**: To model fluid viscosity under zero field.
- **Herschel–Bulkley Model**: To model post-yielding, non-Newtonian fluid behavior.
- **Cutaneous Feedback**: Focus on pressure and lateral force simulation using smart materials.

## 📊 Results
- Generated consistent normal forces (~0.4N) and torques (up to 2Nm).
- Real-time feedback successfully integrated with a Franka Emika gripper.
- Demonstrated effective force mapping between sensed grip force and feedback intensity.

## 🧪 Technologies Used
- MR Fluid (MRF-132DG)
- Ecoflex® Silicone
- Arduino Uno
- 2-Channel Relay
- Peristaltic Pump
- 6-Axis Load Cell
- ROS (for serial data logging)
- Franka Emika robot arm

## 📂 Files
- [`ACS6200-Thesis.pdf`](./thesis/ACS6200-Thesis.pdf): Full thesis document.
- [`Project_outline.pptx`](./assets/Project_outline.pptx): Summarized presentation slides.
- [`/scripts`](./scripts): Contains Arduino code for control and data logging.

## 🔮 Future Work
- Integrate variable magnetic field control.
- Improve MR fluid homogeneity and long-term stability.
- Redesign the silicone device to enhance durability and seal integrity.
- Replace relays with solid-state switching modules for high-frequency activation.

## 📬 Contact
For collaboration or questions, reach out via [LinkedIn](https://www.linkedin.com/in/samanta-suprio-sujoy/) or GitHub Issues.
