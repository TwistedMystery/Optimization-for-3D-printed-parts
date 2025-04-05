# Optimization for 3D Print Parameters
A Consecutive Analysis on Strength of 3D Printed Parts Based on Infill Percentage, Infill Shape, Wall Thickness, and Other Factors, and Optimization for These Parts.

---

## Tensile and Compressive Testing Procedures
This project focuses on conducting **tensile** and **compressive tests** to evaluate the mechanical properties of 3D-printed specimens. The goal is to gain insight into potential issues and material performance variations based on different configurations of **infill patterns**, **densities**, **orientations**, and **specimen size**.

---

## Overview
The project aims to analyze the effects of **3D printing parameters** on the mechanical properties of 3D-printed parts using two test setups:
- **Tensile Testing**
- **Compressive Testing**

---

### Data Collection
All collected data should be added to this Excel sheet:  
[**Data Collection Sheet**](https://kluniversityin-my.sharepoint.com/:x:/g/personal/2100070036_kluniversity_in/EQ-lFUcfcStDj6tSOiSIfe4BCcFKMRETumc8dLTqK5-3vw?e=WKx98z)

---

## 1. Tensile Testing
![Tensile Testing Setup](https://github.com/TwistedMystery/Optimization-for-3D-printed-parts-/blob/main/Picture1.png)
*Objective*: Investigate the effect of **infill patterns**, **densities**, and **orientations** on tensile strength and failure modes.  

*Specimens*:  
- Subsize specimens printed under varying configurations.

---

## 2. Compressive Testing
![Compressive Testing Setup](https://github.com/TwistedMystery/Optimization-for-3D-printed-parts-/blob/main/Picture2.png)
*Objective*: Examine the effect of **wall line count**, **infill density**, **infill shape**, and **print type** on compressive strength.  

*Specimens*:  
- Cube sizes: **10 x 10 x 10 mm** and **30 x 30 x 30 mm**  
- Configurations: Variations in **wall count**, **infill density**, and **shape**.

---

## Optimization for 3D Printed Parts
This project includes images of optimized 3D-printed parts, showcasing various views and test configurations.

### Images
<div style="display: flex; justify-content: space-between; gap: 10px;">
  <img src="https://github.com/TwistedMystery/Optimization-for-3D-printed-parts-/blob/main/Crush%20Piece%201.jpg" width="150" alt="Crush Piece 1">
  <img src="https://github.com/TwistedMystery/Optimization-for-3D-printed-parts-/blob/main/Stretched%20Piece%201%20front%20view.jpg" width="150" alt="Stretched Piece 1 Front View">
  <img src="https://github.com/TwistedMystery/Optimization-for-3D-printed-parts-/blob/main/Stretched%20Piece%201%20side%20view.jpg" width="150" alt="Stretched Piece 1 Side View">
</div>

---

## Introduction of Statistical Tools (JASP and ANOVA)
To further enhance the analysis of the data collected, we will use **JASP**, a free and open-source statistical software, to perform an **ANOVA (Analysis of Variance)**. This method will help:
- **Identify significant factors** affecting the strength and performance of 3D-printed parts.
- Compare variations in strength based on parameters such as infill density, wall line count, and infill shape.

### New Plan Dated 05-04-2025
To gain critical information and get valid results, the approach to the optimization of 3D print parameters will be
- Design of Experiments to reduce the wastage of marterial that is being tested via incorporating 4 different parameters with 4 variations each the table for the design of experiments is given below.
- Testing the 16 Experiments and retesting based on test data.
- Parento Analysis to determine how different factors/parameters affect the ultimate tensile strength.
- Utilizing RSM to optimize the parameters and final testing to validate the results.

This addition will provide a robust statistical foundation to validate experimental findings and refine optimization techniques.
---

## 📊 Experimental Setup & Parameters

We aim to evaluate how different print parameters affect mold quality and casting ease. Parameters such as infill density, wall line count, infill shape, and layer height are varied systematically.

### Experiment Parameters Table

| Run | Infill Density (%) | Wall Line Count | Infill Shape | Layer Height (mm) | Printed | Time   | Weight (g) | Coil Length (m) | Tested |
|-----|--------------------|------------------|--------------|-------------------|---------|--------|------------|------------------|--------|
| 1   | 10                 | 1                | Grid         | 0.10              | N       | 1h 17m | 5g         | 1.75m            | N      |
| 2   | 10                 | 3                | Gyroid       | 0.15              | N       | 1h 9m  | 7g         | 2.27m            | N      |
| 3   | 10                 | 5                | Tri-Hexagon  | 0.20              | N       | 1h 5m  | 8g         | 2.84m            | N      |
| 4   | 10                 | 7                | Cubic        | 0.25              | N       | 1h 2m  | 10g        | 3.33m            | N      |
| 5   | 30                 | 1                | Gyroid       | 0.20              | N       | 1h 8m  | 8g         | 2.84m            | N      |
| 6   | 30                 | 3                | Grid         | 0.25              | N       | 1h 1m  | 10g        | 3.31m            | N      |
| 7   | 30                 | 5                | Cubic        | 0.10              | N       | 1h 46m | 8g         | 2.60m            | N      |
| 8   | 30                 | 7                | Tri-Hexagon  | 0.15              | N       | 1h 23m | 9g         | 2.92m            | N      |
| 9   | 50                 | 1                | Tri-Hexagon  | 0.25              | N       | 1h 1m  | 10g        | 3.44m            | N      |
| 10  | 50                 | 3                | Cubic        | 0.20              | N       | 1h 9m  | 10g        | 3.22m            | N      |
| 11  | 50                 | 5                | Grid         | 0.15              | N       | 1h 24m | 9g         | 3.07m            | N      |
| 12  | 50                 | 7                | Gyroid       | 0.10              | N       | 2h 28m | 9g         | 3.08m            | N      |
| 13  | 70                 | 1                | Cubic        | 0.15              | N       | 1h 23m | 10g        | 3.24m            | N      |
| 14  | 70                 | 3                | Tri-Hexagon  | 0.10              | N       | 1h 59m | 10g        | 3.25m            | N      |
| 15  | 70                 | 5                | Gyroid       | 0.25              | N       | 1h 13m | 11g        | 3.70m            | N      |
| 16  | 70                 | 7                | Grid         | 0.20              | N       | 1h 16m | 11g        | 3.57m            | N      |

---

## 💾 SD Card Allocation

To manage distributed 3D printing, jobs were allocated across three SD cards:

| SD Card | Assigned Prints                  | Total Coil Length (m) |
|---------|----------------------------------|------------------------|
| Card 1  | E4, E6, E9, E10, E13, E16         | **20.11m**             |
| Card 2  | E1, E2, E3, E7, E8                | **12.38m**             |
| Card 3  | E5, E11, E12, E14, E15            | **15.94m**             |

---

This README serves as a comprehensive guide and provides an overview of the setup, statistical analysis, and optimization techniques for tensile and compressive testing. Results from these analyses will guide the selection of optimal printing configurations for enhanced mechanical performance.

