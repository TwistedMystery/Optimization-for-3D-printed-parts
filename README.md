# Optimization-for-3D-printed-parts
A Consecutive Analysis on Strength of 3D Printed Parts based on the infill percentage, Infill Shape, Wall thickness, and other factors and optimization for these parts. 
# Tensile and Compressive Testing Procedures

This project focuses on conducting tensile and compressive tests to evaluate the mechanical properties of 3D-printed specimens. The objective is to gain insight into potential issues and variations in material performance based on different configurations of infill patterns, densities, orientations, and specimen size.

## Overview

The project is divided into two test setups:

1. **Tensile Testing**: Investigating how different printing configurations affect tensile strength and failure modes.
2. **Compressive Testing**: Examining the impact of various factors on compressive strength and deformation.

---

## 1. Tensile Testing

<div style="float: left; width: 300px; margin-right: 20px;">
  <img src="https://github.com/TwistedMystery/Optimization-for-3D-printed-parts-/blob/main/Picture1.png" alt="Tensile Testing Setup" style="width: 100%;"/>
</div>

In the tensile test, subsize specimens are printed and prepared under various configurations to examine how different infill patterns, densities, and orientations affect the mechanical properties of the printed material.

### Objective:
The goal is to compare the mechanical performance of the specimens based on:
- **Wall Line Count**: Varying the number of walls of the specimen.
- **Infill Density**: Variying percentage of Infill density.
- **Infill Shape**: All 14 different infill shapes.
---
## 2. Compressive Testing

<div style="float: left; width: 300px; margin-right: 20px;">
  <img src="https://github.com/TwistedMystery/Optimization-for-3D-printed-parts-/blob/main/Picture2.png" alt="Compressive Testing Setup" style="width: 100%;"/>
</div>

For compressive testing, two different cube sizes are prepared: **10 x 10 x 10 mm** and **30 x 30 x 30 mm**. Similar to the tensile test, variations in the number of walls, infill density, infill shape, and print type are used to understand the impact of these parameters under compression.

### Objective:
The goal is to compare the mechanical performance of the specimens based on:
- **Wall Line Count**: Varying the number of walls of the specimen.
- **Infill Density**: Variying percentage of Infill density.
- **Infill Shape**: All 14 different infill shapes.

# Tensile and Compressive Tests

This document summarizes the tensile and compressive tests conducted on subsize specimens and cubes, focusing on various parameters including infill density, wall thickness, and infill shape. Each section includes tables for recording strength, weight, cost, and strength/weight ratios.

## Tensile Test

### Infill Density

| S.No | Type              | Number of Walls | Infill Density | Infill Shape |
|------|-------------------|-----------------|----------------|--------------|
| 1    | Subsize Specimen   | 1               | 10%            | Grid         |
| 2    | Subsize Specimen   | 1               | 20%            | Grid         |
| 3    | Subsize Specimen   | 1               | 30%            | Grid         |
| 4    | Subsize Specimen   | 1               | 40%            | Grid         |
| 5    | Subsize Specimen   | 1               | 50%            | Grid         |
| 6    | Subsize Specimen   | 1               | 60%            | Grid         |
| 7    | Subsize Specimen   | 1               | 70%            | Grid         |
| 8    | Subsize Specimen   | 1               | 80%            | Grid         |

As the infill percentage increases, there is a general trend of increasing strength, weight, and cost. The values for strength, weight, cost, and strength/weight ratio can be recorded in the table below.

| Infill Percentage | Strength (kg) | Weight | Cost | Strength/Weight |
|-------------------|----------------|--------|------|------------------|
| 10%               |                |        |      |                  |
| 20%               |                |        |      |                  |
| 30%               |                |        |      |                  |
| 40%               |                |        |      |                  |
| 50%               |                |        |      |                  |
| 60%               |                |        |      |                  |
| 70%               |                |        |      |                  |
| 80%               |                |        |      |                  |

### Wall Thickness

| S.No | Type              | Number of Walls | Wall Number | Infill Shape |
|------|-------------------|-----------------|-------------|--------------|
| 1    | Subsize Specimen   | 20%             | 1           | Grid         |
| 2    | Subsize Specimen   | 20%             | 2           | Grid         |
| 3    | Subsize Specimen   | 20%             | 3           | Grid         |
| 4    | Subsize Specimen   | 20%             | 4           | Grid         |
| 5    | Subsize Specimen   | 20%             | 5           | Grid         |
| 6    | Subsize Specimen   | 20%             | 6           | Grid         |
| 7    | Subsize Specimen   | 20%             | 7           | Grid         |
| 8    | Subsize Specimen   | 20%             | 8           | Grid         |

As the infill percentage increases, there is a general trend of increasing strength, weight, and cost. The values can be recorded as follows:

| Wall Number | Strength (kg) | Weight | Cost | Strength/Weight |
|-------------|----------------|--------|------|------------------|
| 1           |                |        |      |                  |
| 2           |                |        |      |                  |
| 3           |                |        |      |                  |
| 4           |                |        |      |                  |
| 5           |                |        |      |                  |
| 6           |                |        |      |                  |
| 7           |                |        |      |                  |
| 8           |                |        |      |                  |

### Infill Shape

| S.No | Type              | Number of Walls | Wall Number | Infill Shape     |
|------|-------------------|-----------------|-------------|-------------------|
| 1    | Subsize Specimen   |                 |             | Grid              |
| 2    | Subsize Specimen   |                 |             | Lines             |
| 3    | Subsize Specimen   |                 |             | Triangles         |
| 4    | Subsize Specimen   |                 |             | Tri Hexagon       |
| 5    | Subsize Specimen   |                 |             | Cubic             |
| 6    | Subsize Specimen   |                 |             | Cubic Subdivisions|
| 7    | Subsize Specimen   |                 |             | Octet             |
| 8    | Subsize Specimen   |                 |             | Quarter Cubic     |
| 9    | Subsize Specimen   |                 |             | Concentric        |
| 10   | Subsize Specimen   |                 |             | Zig-Zag           |
| 11   | Subsize Specimen   |                 |             | Cross             |
| 12   | Subsize Specimen   |                 |             | Cross 3D         |
| 13   | Subsize Specimen   |                 |             | Gyroid            |
| 14   | Subsize Specimen   |                 |             | Lighting          |

The values for strength, weight, cost, and strength/weight can be recorded as follows:

| Infill Shape     | Strength (kg) | Weight | Cost | Strength/Weight |
|-------------------|----------------|--------|------|------------------|
|                   |                |        |      |                  |
|                   |                |        |      |                  |
|                   |                |        |      |                  |
|                   |                |        |      |                  |
|                   |                |        |      |                  |
|                   |                |        |      |                  |
|                   |                |        |      |                  |

---

## Compressive Test

### Infill Density

| S.No | Type              | Number of Walls | Infill Density | Infill Shape |
|------|-------------------|-----------------|----------------|--------------|
| 1    | Cube              | 1               | 10%            | Grid         |
| 2    | Cube              | 1               | 20%            | Grid         |
| 3    | Cube              | 1               | 30%            | Grid         |
| 4    | Cube              | 1               | 40%            | Grid         |
| 5    | Cube              | 1               | 50%            | Grid         |
| 6    | Cube              | 1               | 60%            | Grid         |
| 7    | Cube              | 1               | 70%            | Grid         |
| 8    | Cube              | 1               | 80%            | Grid         |

As the infill percentage increases, there is a general trend of increasing strength, weight, and cost. The values for strength, weight, cost, and strength/weight ratio can be recorded in the table below.

| Infill Percentage | Strength (kg) | Weight | Cost | Strength/Weight |
|-------------------|----------------|--------|------|------------------|
| 10%               |                |        |      |                  |
| 20%               |                |        |      |                  |
| 30%               |                |        |      |                  |
| 40%               |                |        |      |                  |
| 50%               |                |        |      |                  |
| 60%               |                |        |      |                  |
| 70%               |                |        |      |                  |
| 80%               |                |        |      |                  |

### Wall Thickness

| S.No | Type              | Number of Walls | Wall Number | Infill Shape |
|------|-------------------|-----------------|-------------|--------------|
| 1    | Cube              | 20%             | 1           | Grid         |
| 2    | Cube              | 20%             | 2           | Grid         |
| 3    | Cube              | 20%             | 3           | Grid         |
| 4    | Cube              | 20%             | 4           | Grid         |
| 5    | Cube              | 20%             | 5           | Grid         |
| 6    | Cube              | 20%             | 6           | Grid         |
| 7    | Cube              | 20%             | 7           | Grid         |
| 8    | Cube              | 20%             | 8           | Grid         |

As the infill percentage increases, there is a general trend of increasing strength, weight, and cost. The values can be recorded as follows:

| Wall Number | Strength (kg) | Weight | Cost | Strength/Weight |
|-------------|----------------|--------|------|------------------|
| 1           |                |        |      |                  |
| 2           |                |        |      |                  |
| 3           |                |        |      |                  |
| 4           |                |        |      |                  |
| 5           |                |        |      |                  |
| 6           |                |        |      |                  |
| 7           |                |        |      |                  |
| 8           |                |        |      |                  |

###


                     
This README serves as a preparation guide and provides an overview of the setup for tensile and compressive testing. Results from these tests will help in identifying the optimal printing configurations for improved mechanical performance.
