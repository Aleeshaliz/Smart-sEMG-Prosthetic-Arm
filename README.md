# Smart EMG-Controlled Prosthetic Arm

A low-cost, 3D-printed PLA prosthetic arm prototype controlled via forearm surface electromyography (sEMG) signals, featuring FlexiForce grip sensing, DRV2605L + LRA haptic feedback, and the **GripMate** Flutter mobile app.

## Need of This Project
Many existing prosthetic arms are expensive or lack intuitive control and sensory feedback, making everyday grasping and object handling difficult. This project aims to provide an affordable, responsive assistive prototype that translates muscle signals into finger motion while adding grip force awareness and tactile feedback.

## Tech & Hardware
* **Firmware & Simulation:** ESP32, Arduino IDE / PlatformIO, Wokwi, Teleplot, Edge Impulse
* **Hardware & Power:** 2x MyoWare sEMG sensors, 5x MG996R servos, FlexiForce 402 sensors, DRV2605L + LRA haptic module, 11.1V 3S LiPo battery + 5V buck converter
* **CAD & App:** Autodesk Fusion 360 (PLA 3D print), EasyEDA schematics, Flutter (**GripMate**)

## Repository Structure
* `app/` — GripMate Flutter app
* `design/` — Fusion 360 3D CAD files
* `docs/` — Project report and documentation
* `dsp/` — Signal processing files
* `firmware/sEMG/` — ESP32 control firmware

## Team
Aleesha Liz Titto, Anagha Jayadevan, Ananda Raj R. S., Elizabeth Chacko Varghese (ECE, RIT Kottayam)
