# Dataset: Grazing Gradient Threshold Analysis

## Description
This repository contains data and analysis for the study:
“Quantifying Structural and Functional Thresholds Along Grazing Gradients Using a Power-Based Model in Arid Rangelands.”

Data were collected along grazing gradients (0–1000 m) from three disturbance centers in central Iran:
- One wildlife watering point  
- Two livestock camps  

This dataset supports the reproducibility of all analyses and results presented in the manuscript.

---

## Data Contents

### Raw Data
- Vegetation cover (total and functional groups)
- Species richness
- Soil properties (SOM, TN, MWD, Ks, λc)

### Processed Data
- Diversity indices (Margalef R1, Menhinick R2)
- Standardized variables
- Coefficient of variation (CV)
- Weights (wi)
- Dimensionless weighted index (Ym)

### Modeled Outputs
- Threshold distance (D0)
- Half-response distance (D50)
- Sensitivity parameter (p)
- Model fit (SSE)

---

## Repository Structure

All data are organized within a main folder:

/Threshold limits/

This folder contains three subfolders corresponding to the three disturbance centers:

- Livestock Camp1  
- Livestock Camp2  
- Watering Point  

Each disturbance center folder contains two main subfolders:

### 1. Soil
Contains soil-related data:
- Soil data-modeled - [Center name] threshold limits.xlsx  

Each file includes:
- Raw soil measurements (SOM, TN, MWD, Ks, λc)  
- Processed variables  
- Modeled outputs and threshold estimates  

### 2. Vegetation (VEG)
Contains vegetation-related data in two files:

- RICHNESS Index - [Center name] - modeled & threshold limits.xlsx  
  - Species richness data  
  - Margalef (R1) and Menhinick (R2) indices  
  - Modeled outputs  

- VEGETATION COVER - [Center name] - modeled & threshold limits.xlsx  
  - Total and functional group cover (annuals, perennials, shrubs, grasses)  
  - Processed variables and modeled data  

This structure is consistent across all three disturbance centers.

Each Excel file contains raw data, processed variables, and model outputs in separate sheets.

---

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
| Ym | Dimensionless weighted index | - |

---

## Methods Summary
Data were standardized and weighted using the coefficient of variation (CV). A power-based nonlinear model was applied to describe ecosystem responses along grazing gradients and to estimate ecological thresholds (D0, D50) and system sensitivity (p).

---

## Reproducibility
All data used in the analysis are provided. Model parameters were estimated using nonlinear optimization (Microsoft Excel Solver). The dataset allows full reproduction of the analyses presented in the manuscript.

---

## Contact
Hossein Bashari  
Isfahan University of Technology  
Email: hbashari@iut.ac.ir

