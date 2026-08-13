# CAD Files & Parametric 3D Models

This directory contains the core source CAD (Computer-Aided Design) files for our National Champion RoboCup autonomous soccer robot. 

To maximize accessibility and compatibility across different engineering software, files are provided in both **native parametric formats** and **universal exchange formats (`.STEP`)**.

---

## 🛠️ Software & Technical Specifications

- **Primary CAD Software:** Autodesk Fusion 360 & SolidWorks
- **Measurement System:** Metric (Millimeters - `mm`)
- **Design Philosophy:** Modular, parametric modeling for rapid clearance adjustments and component replacement.

---

## 📂 File Types Available

1. **`.STEP` / `.STP` (Universal Step Files):** 
   - *Recommended for most users.* 
   - Compatible with Fusion 360, SolidWorks, Inventor, Rhino, Onshape, and FreeCAD.
   - Preserves 3D solid geometry and assembly hierarchies without software lock-in.

2. **`.f3d` / `.sldprt` / `.sldasm` (Native CAD Files):**
   - Native project files containing full parametric design trees, sketches, timelines, and joint constraints.

---

## Major Sub-Assemblies Included

When browsing or uploading files to this directory, the hardware is divided into these main mechanical modules:

- **Drivetrain & Kinematics:** Custom omniwheel hubs, motor mounting brackets, and gear/belt covers.
- **Chassis & Frame:** Baseplates, multi-tier standoff layouts, and bumper geometry.
- **Sensor & Electronics Mounts:** Enclosures and brackets for IR ring sensors, compass, line sensors, and main PCB supports.
- **Active Ball Manipulation (Kicker):** Solenoid housing, and shock-absorption brackets.

---

## How to Edit or Modify These Designs

1. Download the `.STEP` file of the module you wish to modify.
2. Import the file into your preferred CAD environment (set workspace units to **mm**).
3. Verify motor shaft tolerances and screw hole clearances (standard M2/M3 tapped holes) before re-exporting to STL for manufacturing.
