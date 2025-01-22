# Optimization for 3D Printed Parts
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

### Planned Steps with JASP
1. **Data Normalization**: Prepare the collected data for statistical analysis.
2. **ANOVA Analysis**: Perform ANOVA to understand the impact of different parameters on tensile and compressive strength.
3. **Visualization**: Use JASP to generate graphs and charts for clear visualization of results.
4. **Optimization**: Leverage insights from ANOVA to recommend optimal configurations for 3D-printed parts.

This addition will provide a robust statistical foundation to validate experimental findings and refine optimization techniques.

---

## Project Task Table
| Task                        | Description                                                                                                   | Assigned To                | Status       |
|-----------------------------|---------------------------------------------------------------------------------------------------------------|----------------------------|--------------|
| **3D Printing**             | 3D print the following specimens:                                                                            | Gopinath, Nakka Karthik    | Not Started  |
|                             | - 3 sets of tensile testing specimens for varying infill density                                             |                            |              |
|                             | - 3 sets of compressive testing specimens for varying infill density                                         |                            |              |
|                             | - 3 sets of tensile testing specimens for varying wall line count                                            |                            |              |
|                             | - 3 sets of compressive testing specimens for varying wall line count                                        |                            |              |
| **Data Entry**              | Add the different weights of the specimens and create an online Excel sheet to track progress.               | Jwalitha, Sanjay           | Not Started  |
| **Learning Optimization**   | Learn about optimization techniques and their applications and submit a concise report on the same.          | All Members                | Not Started  |

This README serves as a comprehensive guide and provides an overview of the setup, statistical analysis, and optimization techniques for tensile and compressive testing. Results from these analyses will guide the selection of optimal printing configurations for enhanced mechanical performance.
