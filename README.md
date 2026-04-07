# Functional Analysis of Darwin Sea Level Pressure (1951-2025)

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![FDA](https://img.shields.io/badge/Functional_Data_Analysis-009688?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

📋 Overview  
This project applies Functional Data Analysis **(FDA)** techniques to analyze 75 years (1951-2025) of monthly Darwin Sea Level Pressure (SLP) data. The analysis transforms discrete monthly observations into continuous functions to study **seasonal patterns, interannual variability, and ENSO-related pressure anomalies**.

##  🎯 Key Objectives
- Convert discrete SLP measurements into smooth functional curves using Fourier basis functions
- Compute and interpret functional descriptive statistics (mean, standard deviation, covariance)
- Perform Functional Principal Component Analysis (FPCA) to identify dominant modes of variation
- Apply VARIMAX rotation to enhance the physical interpretability of principal components

## 📊  Dataset
- Source: Darwin, Australia sea level pressure records
- Time Period: 1951 - 2025 (75 years)
- Resolution: Monthly observations (12 months per year)
- Format: 75 rows × 12 columns matrix (years × months)
- Units: mb relative to 1000 mb

## ![Description of image](image/S1.png)

## 🚀 Getting Started

### 1. Clone the Repository
- git clone https://github.com/yourusername/darwin-slp-fda.git
- cd darwin-slp-fda
### 2. Launch R or RStudio
Open RStudio or your preferred R environment.
###  3. Install Required Package & Load fda Library
- install.packages("fda")
- library(fda)
### 5. Read and Prepare the Data
![Description of image](image/S2.png)

### 6. Set Up Fourier Basis for Smoothing
![Description of image](image/S3.png)

### 7. Perform Smoothing with Chosen λ
![Description of image](image/S4.png)

### 8. Compute Functional Statistics
![Description of image](image/S5.png)

### 9. Perform FPCA
![Description of image](image/S6.png)

