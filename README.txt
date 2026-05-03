# Dataset: Grazing Gradient Threshold Analysis

## Description
This repository contains data and analysis for the study:
“Quantifying Structural and Functional Thresholds Along Grazing Gradients Using a Power-Based Model in Arid Rangelands.”

Data were collected along grazing gradients (0–1000 m) from three disturbance centers in central Iran:
- One wildlife watering point 
- Two livestock camps 

## Data Contents
The repository includes:

### 1. Raw Data
- Vegetation cover (total and functional groups)
- Species richness
- Soil properties (SOM, TN, MWD, Ks, λc)

### 2. Processed Data
- Calculated diversity indices (Margalef R1, Menhinick R2)
- Standardized variables
- Coefficient of variation (CV)
- Weights (wi)
- Dimensionless index (Ym)

### 3. Modeled Outputs
- Threshold distance (D0)
- Half-response distance (D50)
- Sensitivity parameter (p)
- Model fit (SSE)

## Variables
| Variable | Description | Unit |
|----------|------------|------|
| Distance | Distance from disturbance center | m |
| Center | Type of disturbance (wildlife/livestock) | - |
| Total_cover | Total vegetation cover | % |
| SOM | Soil organic matter | % |
| TN | Total nitrogen | % |
| MWD | Mean weight diameter | mm |
| Ks | Saturated hydraulic conductivity | cm/h |
| Ym | Weighted index | dimensionless |

## Methods Summary
Data were standardized and weighted using the coefficient of variation (CV). A power-based nonlinear model was applied to estimate ecological thresholds (D0, D50) and system sensitivity (p).

## Reproducibility
All data used in the analysis are provided. Model parameters were estimated using nonlinear optimization (Excel Solver).

## Contact
Hossein Bashari 
Isfahan University of Technology
hbashari@iut.ac.ir
