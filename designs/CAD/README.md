# 🌊 **TMS Seawall – CAD Designs**

CAD models and technical documentation for the **Tsunami Mitigation System (TMS)** seawall prototype.  
This directory contains all geometry for the sloped seawall, internal cavity, and structural ribs.

---

## 📁 **Directory Contents**

All files exist **directly** in this directory.  
**There are no subfolders.**

### **CAD Models**
- `tms_wall_full.step` – Full 3D seawall assembly  
- `rib_unit.step` – Individual rib geometry  
- `cavity_profile.step` – Inner cavity cross-section  
- `foundation_block.step` – Base and anchoring geometry  

### **Technical Drawings**
- `wall_section.pdf` – Annotated cross-section with angles  
- `rib_layout.pdf` – Rib spacing and cavity interface  
- `foundation_details.pdf` – Footing and reinforcement notes  

### **Reference Files**
- `geometry_notes.md` – Slopes, dimensions, parametric notes  
- `materials_and_thickness.txt` – Material assumptions and design thickness  
- `load_path_analysis.pdf` – Structural load-path explanation  
- `slopes_and_angles.xlsx` – Numeric angle calculations  

### **Exports**
- `.STEP` – Full-resolution CAD  
- `.STL` – Mesh files for simulation  
- `.DXF` – 2D profiles  

---

## 🧭 **Orientation Summary**

A quick guide to how the seawall is defined in CAD:

| Component | Description |
|----------|-------------|
| **Seaside Face** | Sloped face that meets the wave front |
| **Land-Side Face** | Fully vertical, supports the rear |
| **Inner Cavity Face** | Faces toward the sea inside the hollow region |
| **Ribs** | Always **perpendicular to the inner cavity face**, not the ground |
| **Units** | All dimensions are given in **mm** |

Correct orientation is essential for simulation and analysis.

---

## 🛠️ **Versioning Rules**

File naming uses these conventions:

- `_vX.Y` → Major/minor geometry updates  
- `_revA`, `_revB` → Small corrections, cleanup, or tuning  

Whenever geometry changes, update the version tag.

---

## 🤝 **Contribution Guidelines**

To ensure consistency:

- Keep all critical slopes and thicknesses **parametric**  
- Update `geometry_notes.md` whenever a core value changes  
- Use clear file naming (e.g., `wall_15deg_v4.step`)  
- Maintain `.STEP` as the primary exchange format  
- Avoid creating subfolders unless new modules require them  

---
