# RoboCup Autonomous Soccer Robot – Mechanical Hardware (Open-Source)

![Status](https://img.shields.io/badge/Status-Production_Ready-brightgreen?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-blue?style=flat-square)
![Category](https://img.shields.io/badge/RoboCup_Junior-Infrared-orange?style=flat-square)

Welcome to the official open-source hardware repository of our National Champion RoboCup High School Robotics Team! This repository hosts production-ready CAD models, 3D printing parameters, chassis blueprints, and physical integration guidelines for competitive autonomous soccer robots.

---

## Technical Specifications & Engineering Highlights

- **Kinematics & Drive System:** Omnidirectional drive mechanism using custom-designed aluminum omniwheels and 4 high-torque motor.
- **Physical Fabrication:** Precision-cut 2D laser chassis (acrylic) integrated with FDM 3D printed structural components (PLA/PC).
- **Control & Sensor Integration:** Embedded mounting brackets for optical encoders, infrared ball sensors, compass modules, and main circuit board protection.
- **CAD Software Used:** Fusion 360.

---

## 📂 Repository Organization

To make navigation easy for rookie and experienced robotics teams, files are structured into the following folders:

```text
├── CAD_Files/            # Editable native CAD (.f3d, .sldprt) and universal .STEP files
├── STL_Printables/       # Production-ready 3D printable files sorted by robot module
├── Documentation/        # Assembly guidelines, Bill of Materials (BOM), and hardware clearance specs
└── Media/                # High-resolution renders, physical photos, and match performance clips

## How to Use These Hardware Files

1. **For Custom Modification:** Download `.STEP` files from the `/CAD_Files` directory to adapt clearances, motor mounts, or drive parameters to your team's specific requirements in Fusion 360, SolidWorks, or any major CAD suite.
2. **For Direct 3D Printing:** Access production-ready `.STL` files directly from `/STL_Printables`.
3. **Assembly & Mechanical Standards:** Refer to the `/Documentation` directory for:
   - Hardware specs and recommended metric screw sizes (M2 / M3).
   - Heat-set brass insert locations and assembly clearances.
   - Recommended slicing profile: **30%+ Gyroid or Cubic infill** for high-stress structural parts (PETG or PLA+ recommended).

---

## 🌟 Impact & Open-Source Philosophy

By open-sourcing these blueprints, our mission is to lower the technical barrier to entry for emerging high-school robotics teams in Brazil and worldwide. We believe that sharing production-grade hardware empowers student engineers to innovate faster and focus on advanced control, strategy, and Physical AI.

These exact hardware designs helped power our team to top historical achievements:
- **1st Place / National Champions** — RoboCup Brasil (Junior Soccer Infrared)
- **6th Place Globally** — RoboCup Incheon (junior Soccer Infrared)

---

## License & Attribution

This repository is officially released under the **MIT License**. You are free to use, modify, distribute, and build upon these mechanical designs for both competitive and educational projects.

*If your team adopts or adapts our CAD files, please consider leaving a star ⭐ on this repository and citing our team in your engineering notebook!*
