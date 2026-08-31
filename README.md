# Wakizashi PC Case

Open-source enclosed slim wall-mount SFF PC case. 

![Wakizashi PC Case](./photo/swmc-db-7l%20(9).jpg)

> [!NOTE]
> **Project Status:** The hardware prototype is complete. This repository is currently being organized: final manufacturing files, 3D models, and documentation are being uploaded and formatted for public use.

Designed for building either a compact gaming system or a small NAS. Due to its horizontal orientation and a flat linear component layout, heat overlap between components is minimized, preventing thermal crosstalk. Thanks to its slim profile and flush-to-wall mounting capability, the case saves massive space in your home setup, offering a near-zero footprint.

---

## Technical Specifications

* **Dimensions:** 220 x 440 x 73 mm
* **Volume:** 7L
* **Material:** 1.0 mm steel
* **PSU Support:** TFX or Flex ATX (if Flex ATX is used, 1 x 2.5" SSD can be installed under it)
* **Cooling:** Up to 50 mm CPU cooler height, 3 x 60x15 mm case fans

---

## Hardware Compatibility

### 1. Gaming Build
* **Motherboard:** Mini-ITX
* **GPU:** Length up to ~205 mm, thickness up to 50 mm (2.5 slots). Requires 18.5 cm double reverse PCIe riser cable.
* **Storage:** 1 x 2.5" SSD

### 2. NAS Build
* **Motherboard:** Mini-ITX or Micro-ATX (mATX) (up to 200×225 mm)
* **Storage:** 2 x 3.5" HDD or 4 x 2.5" SSD

---

## UX Solutions

* Flush-to-wall mounting (via integrated corner slots on screw-in hooks)
* Downward-facing external ports
* Easily removable feet for surface placement
* Side-mounted USB-C port
* Additional reversible 3.5" HDD mounting holes for easier cable routing
* Three interchangeable cover designs (Standard, Wood Slat, Wakizashi)

---

## Use Cases

* **Wall-mounted above a desk:** Mount the case on the wall directly above your monitor to completely free up desk space in your home setup.
* **DIY Steam Machine:** Place the case on top of a TV stand in the living room as a high-performance console-sized PC for big-screen gaming.
* **Zero-footprint workstation:** Combine the wall-mounted case with a wall-mounted monitor, soundbar, and a folding wall desk to create a workstation that folds completely flat against the wall when not in use.

---

## Dust Filter

To install a dust filter, a standard 100x30 cm mesh sheet can be purchased, cut to the size of the chosen cover, and installed directly underneath it.

---

## Manufacturing

To fabricate the case, provide the PDF drawings and DXF files to a metal shop capable of laser cutting, bending, welding, and painting. Agree on the paint color in advance.

---

## Files & Documentation

* [BOM.txt](./BOM.txt) — Fasteners, hardware, and components list
* [Assembly_guide.pdf](./Assembly_guide.pdf) — Assembly instructions
* [photo/](./photo/) — Prototype photos and renders
* [drawings_pdf/](./drawings_pdf/) — Engineering drawings in PDF format
* [dxf_main/](./dxf_main/) — Main DXF files for laser cutting
* [dxf_alternative/](./dxf_alternative/) — Alternative DXF files (use if the main files cannot be read or imported with errors by the fabricator)
* [flat_patterns_step/](./flat_patterns_step/) — Unfolded flat patterns in STEP format (backup option if both DXF formats fail)
* [model_step/](./model_step/) — Complete 3D model of the case in STEP format
