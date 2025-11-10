# Bluetooth Speaker — Design & Build Report

**Course:** TDJ4M1  
**Teacher:** Mr. Watson  
**Students:** Oscar Chen, Sam Zhu  
**Date:** Oct 1, 2025

---

## Table of Contents

- [Overview](#overview)
- [Goals & Constraints](#goals--constraints)
- [Design Criteria](#design-criteria)
- [Investigation & Research](#investigation--research)
- [Concepts & Sketches](#concepts--sketches)
- [CAD, Printing & Assembly](#cad-printing--assembly)
- [Electronics](#electronics)
- [Manufacturing Notes](#manufacturing-notes)
- [Cost & Production](#cost--production)
- [Timeline](#timeline)
- [Evaluation](#evaluation)
- [Critical Reflection](#critical-reflection)
- [Repository Structure](#repository-structure)
- [Build & Print Instructions](#build--print-instructions)
- [Future Work](#future-work)
- [License](#license)

---

## Overview

This project delivers a **compact, portable Bluetooth sound system** designed and fabricated in **Fusion 360** and produced via **3D printing**.  
The enclosure houses:

- 2 main speakers + 2 auxiliary speakers + 1 subwoofer  
- 2 control boards  
- Accessible ports, buttons, and battery compartment  
- **Magnetic fluid (“ferrofluid”) display** that “dances” to music via a controllable electromagnet  
- **Flip-top back** and **magnetic front/back coupling** for easy maintenance  
- Internal **LED illumination** that reveals **thinned light channels** in the surface design  

> The design balances **functionality, safety, and aesthetics**, ensuring stable internal structure and a futuristic, creature-like appearance.

---

## Goals & Constraints

- **Functionality:** Secure internal components, accessible ports, vibration-resistant.  
- **Printability:** Modular, fits standard FDM printers.  
- **Serviceability:** Flip-top lid, magnetic connection.  
- **Aesthetics:** Light-transmitting surface patterns, mascot features.  
- **Safety:** Rounded edges, locally compatible electronics.

---

## Design Criteria

| Category  | Specification |
|------------|---------------|
| **Size** | Must fit within printer build volume; stable on table |
| **Function** | All buttons, speakers, and ports functional; components secured |
| **Materials** | 3D-printed plastic, strong but safe edges |
| **Aesthetics** | Clean, futuristic look with LED patterns |

---

## Investigation & Research

- **Pros:** Stable base designs, portability, good sound projection.  
- **Cons:** Spherical forms are unstable, some lack volume control.  

Key learnings:
- Front controls improve usability.  
- Symmetrical shapes enhance sound balance.  
- Transparent/lighted elements improve aesthetics.

---

## Concepts & Sketches

### Oscar’s Concept
- Cat-face front with ferrofluid as “face”  
- Multi-feet for stability and personality  
- 5-speaker array for richer audio  
- Magnetic front/back and flip-top design  
- Thinned wall patterns illuminated by LEDs  

### Sam’s Concept
- Stable internal structures for all components  
- Button extension mechanisms  
- Custom holders for speakers without screw holes  

Both ideas were combined into the final design: a cute yet futuristic speaker with advanced lighting and ferrofluid display.

---

## CAD, Printing & Assembly

> All files are available at:  
> [GitHub Repository](https://github.com/zhu-ziyu/TDJ-Speaker)

### Key Dates
- **Oct 18–19:** Initial CAD of enclosure; first test prints.  
- **Oct 20–23:** Flip-top, magnet connections, and button extensions.  
- **Oct 24:** Refined back panel and circuit board holes.  
- **Oct 27–29:** Added LED patterns and mascot; replaced electromagnet with local-safe version.  
- **Oct 31–Nov 4:** Final printing, soldering, and full assembly.

---

## Electronics

- **Main Components:** Two circuit boards, electromagnet, five speakers, LED lights.  
- **Feature:** Ferrofluid bottle reacts to music via controlled electromagnet.  
- **Fix:** Replaced unsafe imported electromagnet with Canada-compatible version.

---

## Manufacturing Notes

- **Material:** ABS (or PETG as alternative)  
- **Tolerances:** Precision snap-fits, magnet seats  
- **Orientation:** Printed to reduce visible supports  
- **Serviceability:** Flip-top hinge and magnetic coupling tested

---

## Cost & Production

| Item | Value |
|------|--------|
| **Material Cost (per unit)** | $62 CAD (tax included) |
| **Print Time** | 11 hours |
| **Suggested Retail** | $128 CAD |

---

## Timeline

| Date | Activity |
|------|-----------|
| Oct 1–10 | Approval, drafts, PCB modeling |
| Oct 16–23 | Final draft selection, modeling, magnet design |
| Oct 24–31 | LED patterning, new electromagnet, mascot |
| Nov 3–4 | Final assembly, soldering, testing |

---

## Evaluation

### Oscar
- **Strengths:** Advanced modeling, ferrofluid feature, and LED design.  
- **Successes:** Perfect component fitting, magnet system, user-friendly assembly.  
- **Improvements:** Add programmable RGB LEDs.  
- **Learned:** Check voltage compatibility before sourcing components.

### Sam
- **Strengths:** Assembly precision, soldering, stable mounts, troubleshooting.  
- **Successes:** Solved unstable speaker issue with custom holder.  
- **Improvements:** Explore stronger, more aesthetic materials.  
- **Learned:** Early verification of parts saves time.

---

## Critical Reflection

### Oscar
- **What went well:** Implemented complex modeling and safe electronics.  
- **What to improve:** Add RGB LED system reactive to music.  
- **Learned:** Importance of regional voltage verification.  
- **If starting over:** Prototype LED and verify all components early.

### Sam
- **What went well:** Produced stable, functioning assembly.  
- **What to improve:** Research material upgrades.  
- **Learned:** Value of creating testing protocols early.  
- **If starting over:** More testing time for final soldering.

---

## Repository Structure

