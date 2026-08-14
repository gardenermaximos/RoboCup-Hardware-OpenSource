# 3D Printable Files (.STL / .3MF) & Manufacturing Guide

This directory contains production-ready 3D printable files (`.STL` and `.3MF`) for all custom structural and mechanical components of the robot. 

These models have been physically field-tested in high-impact RoboCup competition environments to ensure structural integrity, thermal resistance, and optimal weight distribution.

---

## Recommended 3D Printing Parameters

For maximum mechanical strength and part longevity under competitive loads, we recommend the following slicing settings:

| Parameter | Structural Parts (Chassis, Mounts) | High-Wear / Impact Parts (Omniwheels, Kickers) |
| :--- | :--- | :--- |
| **Recomended Material** | PETG / PLA+ / ABS | PETG / Nylon / TPU |
| **Layer Height** | 0.20 mm (Standard) | 0.16 mm - 0.20 mm |
| **Infill Percentage** | 25% – 40% | 50% – 100% (Solid) |
| **Infill Pattern** | Gyroid or 3D Honeycomb | Gyroid or Rectilinear |
| **Wall Loops / Perimeters** | 4 – 5 Walls | 5+ Walls (Crucial for strength) |
| **Top/Bottom Layers** | 4 Top / 4 Bottom | 5 Top / 5 Bottom |
| **Supports** | Organic / Tree Supports (where needed) | Minimal (designed for minimal bridging) |

---

## 📂 File Categorization

When uploading or downloading files in this directory, models are organized by module prefix:

* `DRV_` — **Drivetrain Components:** Motor holders, omniwheel assemblies, bearing retainers.
* `CHS_` — **Chassis & Structural:** Tier spacers, battery trays, outer protective bumpers.
* `SEN_` — **Sensor Mounts:** Infrared ring brackets, compass mounts, line sensor frames.
* `ACT_` — **Actuators:** Solenoid housings, dampener brackets.

---

## ⚙️ Tolerances & Hardware Notes

- **Screw Holes:** Holes designed for M2 and M3 screws are modeled with a standard tolerance of **+0.15 mm to +0.20 mm** to allow direct tapping or heat-set insert installation.
- **Heat-Set Inserts:** We strongly recommend using **M3 brass heat-set inserts** for parts that require frequent assembly/disassembly to avoid stripping 3D printed plastic threads.
- **Shrinkage Factor:** If printing with ABS or ASA, scale parts by ~0.5%–0.8% in your slicer to compensate for thermal contraction.
