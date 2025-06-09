# Wear Reduction in Slider Pump – ME 351 Studio Project 6

This project investigates wear reduction strategies for a slider pump using parameter design techniques. An L8 orthogonal array was used to test different combinations of five design factors (and two interactions), and statistical analysis was conducted to determine optimal conditions for minimizing wear over the pump’s design life.

## 📌 Objective
Reduce wear in a slider pump through factorial experimentation and statistical quality improvement techniques. Compare optimized design conditions against an existing benchmark.

## 🧪 Experimental Design
- **Design Factors:** Material, Weight, Surface Roughness, Clearance, Side Material
- **Interactions:** A×B, A×C
- **Data Set:** Wear in microns measured at 8 points per trial (R1–R8)
- **Design Matrix:** L8 orthogonal array with binary levels

## 🧮 Part I – Statistical Analysis
- Calculated main and interaction effects
- Conducted Analysis of Variance (ANOVA) and Pooled ANOVA
- Constructed confidence intervals for factor effects
- Estimated mean wear under optimal conditions
- Compared results against benchmark wear data

## 📊 Part II – S/N Ratio Analysis
- Computed S/N ratios for each trial to account for variability
- Conducted ANOVA on S/N data
- Identified optimal factor levels based on both wear and S/N ratio
- Estimated performance gain over the benchmark using “S/N + 20” method

## ✅ Key Outcomes
- Identified optimal factor settings to reduce wear significantly
- Achieved quantitative improvement over existing product based on both average wear and signal-to-noise ratio
- Demonstrated effective application of parameter design and quality engineering tools

## 🛠 Tools Used
- MATLAB for data processing, calculations, and plotting
- Excel for tabulating results and visual analysis

## 📁 Contents
- `SP6_WearData_Analysis.m`: MATLAB script for calculations and plots
- `SP6_Report.pdf`: Final report with analysis, graphs, and discussion
- `wear_data.csv`: Raw wear measurements and design matrix
