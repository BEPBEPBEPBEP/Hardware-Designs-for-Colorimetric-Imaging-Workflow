# Hardware Designs for Colorimetric Imaging Workflow

This repository contains the STL and CAD files for 3D-printable components used in a low-cost colorimetric imaging workflow for paper-based microfluidic devices (µPADs). The system was designed to provide controlled imaging conditions while maintaining accessibility through minimal fabrication requirements.

---

## Overview

The hardware system supports reproducible colorimetric analysis by:

- Mounting a camera module at a fixed distance from the µPAD surface  
- Providing controlled illumination conditions  
- Shielding assays from ambient light interference  
- Ensuring consistent strip positioning during imaging  

The design prioritizes simplicity and low-cost fabrication, aligning with principles of frugal science and decentralized environmental monitoring.

---

## Components

The following components are included in this repository:

- **Imaging Enclosure**  
  3D-printed housing designed to securing the camera module and LED modules at a fixed distance for imaging purposes and isolate the detection environment from ambient light.

- **µPAD Strip Tray**  
  Removable tray with recessed groove for consistent alignment and repeatable positioning of µPAD strips.

- **Lighting Mount(s)** 
  Structures used to position LED modules for uniform illumination.

---

## File Types

Each component is provided in:

- **STL format** – for direct 3D printing  
- **CAD format (Fusion 360 / STEP)** – for modification and customization  

---

## Fabrication

All components were designed for fabrication using standard desktop 3D printers.

### Recommended print settings:
- Material: PLA or PETG  
- Layer height: 0.2 mm  
- Infill: 15–25%  
- Supports: Not required (for most parts)  

Print settings may be adjusted depending on printer capabilities.

---

## Assembly

The printed components are designed to integrate with:

- Raspberry Pi (single-board computer)  
- Arducam camera module  
- LED illumination modules  

Basic assembly involves:
1. Securing the camera to the enclosure roof  
2. Positioning lighting modules within designated mounts  
3. Inserting the µPAD strip tray into the enclosure  

Refer to the associated publication for full system configuration and imaging workflow.

---

## Usage

The assembled system is used to capture images of µPAD detection zones under controlled conditions for colorimetric analysis. The fixed geometry and enclosed design improve reproducibility across measurements.


---

## License

This work is licensed under the **Creative Commons Attribution 4.0 International License (CC BY 4.0)**.

You are free to share and adapt the designs with appropriate attribution.


---

## Notes

These designs were developed as part of a study investigating the feasibility of minimally fabricated µPAD systems for low-cost environmental sensing. The hardware reflects a design philosophy focused on accessibility and reproducibility rather than optimized instrumentation.

---

## Contact

For questions or collaboration inquiries, please contact:

Thomas Lau
Fordham University
tnlau2004@gmail.com
