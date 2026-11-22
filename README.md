# Wakizashi PC Case

Open-source enclosed slim wall-mount SFF PC case. 

![Wakizashi PC Case](./photo/swmc-db-7l%20(9).jpg)

![Wakizashi PC Case](./photo/swmc-db-7l%20(30).jpg)

Designed for building either a compact gaming system or a small NAS. Due to its horizontal orientation and a flat linear component layout, heat overlap between components is minimized, preventing thermal crosstalk. Thanks to its slim profile and flush-to-wall mounting capability, the case saves massive space in your home setup, offering a near-zero footprint.

---

## Technical Specifications

* **Dimensions:** 220 x 440 x 73 mm
* **Volume:** 7L
* **Weight (without feet):** 2.0 kg
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
* Three optional cover designs (Standard, Wood Slat, Wakizashi)

---

## Use Cases

* **Wall-mounted above a desk:** Mount the case on the wall directly above your monitor to completely free up desk space in your home setup.
* **DIY Steam Machine:** Place the case on top of a TV stand in the living room as a high-performance console-sized PC for big-screen gaming.
* **Zero-footprint workstation:** Combine the wall-mounted case with a wall-mounted monitor, soundbar, and a folding wall desk to create a workstation that folds completely flat against the wall when not in use.
* **NAS / Stealth Home Server:** Mount the case on a hallway wall to create a headless server that stays completely out of the way, occupying zero floor or shelf space while looking like a piece of interior decor.
---

## Dust Filter

To install a dust filter, a standard 100x30 cm mesh sheet can be purchased, cut to the size of the chosen cover, and installed directly underneath it.

---

## Manufacturing

To fabricate the case, provide the PDF drawings and DXF files to a metal shop capable of laser cutting, bending, welding, and painting. Agree on the paint color in advance.

### Ordering the Case on AliExpress

You can also order custom fabrication of this case on AliExpress:

* [AliExpress Store](https://www.aliexpress.com/store/1102204216) — The shop where I ordered my prototype
* [manufacturing_pack_aliexpress.zip](./manufacturing_pack_aliexpress.zip) — Ready-to-send package for the AliExpress seller (includes a text file with all necessary information for the manager, DXF files, STEP flat patterns, PDF drawings, and a 3D STEP assembly; note that this package includes the Standard cover design)
* [SmallFormFactor.net Build Log](https://smallformfactor.net/forum/threads/slim-wall-mount-7l-pc-case-project.20416/post-296806) — Detailed post describing my ordering process and experience with the seller

---

## Thermal Testing

### Gaming Setup

For these tests, I used older hardware with a thermal output comparable to modern components.

**Test Bench:**
* **CPU:** Intel Core i5-3330S (65W TDP)
* **GPU:** ASUS GeForce GTX 760 DirectCU Mini (170W TDP)
* **CPU Cooler:** ID-Cooling DK-01S
* **PSU:** T.F.SKYWINDINTL Flex ATX 600W

**Temperatures in an open-air setup (classic layout):**
* **CPU:** 77°C
* **GPU:** 80°C

**Temperatures inside the case (with 2 out of 3 possible exhaust fans installed):**
* **CPU:** 80°C
* **GPU:** 84°C

**Test Duration (AIDA64 + FurMark):** ~25 minutes

**Temperature delta (open-air vs. inside the case):** +3°C for the CPU, +4°C for the GPU.

---

### NAS Setup

For the NAS build, thermal testing was conducted during extended workloads inside the assembled case.

**Test Bench:**
* **CPU:** AMD Ryzen 3 2200GE (35W TDP)
* **CPU Cooler:** AMD Wraith Stealth
* **Cooling:** Case fan mounted directly above the drive cage

**Temperatures inside the case:**
* **CPU (under AIDA64 stress test):** up to 63°C
* **HDDs (under prolonged workload):** 38–41°C

---

## Files & Documentation

* [BOM.txt](./BOM.txt) — Fasteners, hardware, and components list
* [Assembly_guide.pdf](./Assembly_guide.pdf) — Assembly instructions
* [photo/](./photo/) — Prototype photos and renders
* [drawings_pdf/](./drawings_pdf/) — Manufacturing drawings in PDF format
* [dxf_main/](./dxf_main/) — Main DXF files for laser cutting
* [dxf_alternative/](./dxf_alternative/) — Alternative DXF files (use if the main files cannot be read or imported with errors by the fabricator)
* [flat_patterns_step/](./flat_patterns_step/) — Unfolded flat patterns in STEP format (backup option if both DXF formats fail)
* [model_step/](./model_step/) — Complete 3D model of the case in STEP format
