# CIVE 202 – Civil Engineering Analysis II  
## Project #2: Automation of NDOT Concrete Mix Design  

**Client:** Nebraska Department of Transportation (NDOT)  
**Course:** University of Nebraska–Lincoln  
**Semester:** Spring 2026  
**Team:** Group 4  




# Executive Summary

This project automates the Nebraska Department of Transportation (NDOT) Excel-based concrete mix design model by translating it into a structured and reusable Python program.

The original Excel worksheet was reverse-engineered and converted into modular Python functions that replicate every calculation step. The final program produces a fully formatted NDOT-style weight summary for **1 cubic yard (27 ft³) of concrete**.

The automation improves:
- Computational accuracy
- Model transparency
- Reproducibility of results
- Engineering workflow efficiency
- Ease of validation using multiple test scenarios




# Engineering Objective

To develop a reliable Python-based automation tool that:

• Replicates all formulas from the NDOT Mix Design worksheet  
• Maintains engineering unit consistency  
• Uses specific gravity relationships for volume-to-weight conversion  
• Automatically calculates aggregate volumes and weights  
• Generates a professional formatted output summary  
• Validates accuracy using realistic concrete mix scenarios  




# How the Model Works

The program performs the following sequence:

1. Accepts cementitious material inputs (cement, fly ash, silica fume, SCM)
2. Calculates batch water using the water-cement ratio
3. Converts material weights to volumes using:
   - Specific gravity
   - Unit weight of water (62.4 lb/ft³)
4. Computes air volume based on percent air content
5. Determines remaining aggregate volume
6. Allocates aggregate volume using percentage splits
7. Converts aggregate volumes to final batch weights
8. Prints a formatted NDOT weight summary

All calculations are based on:

> **1 cubic yard of concrete = 27 cubic feet**




# Repository Structure

| File | Description |
|------|-------------|
| **CIVE202_Spring2026_Group4_Project2_PythonCode.ipynb** | Main automation python program |
| **CIVE202_Spring2026_Group4_Project2_AnnotatedCodeDocument.pdf** | Line-by-line code explanation |
| **CIVE202_Spring2026_Group4_Project2_ScopeOfWork.pdf** | Project objectives, tasks, and deliverables |
| **CIVE202_Spring2026_Group4_Project2_GanttChart.pdf** | Project schedule and workflow timeline |
| **CIVE202_Spring2026_Group4_Project2_RealisticScenarioMixtures.pdf** | Four validated test cases |
| **CIVE202_Spring2026_Group4_Project2_Report.pdf** | Complete technical documentation |




# Validation & Testing

The model was verified using four realistic design scenarios:

1. NDOT Class 47B Pavement Mix  
2. 4000 PSI Structural Concrete (ACI Typical Mix)  
3. 47BD Concrete Mix  
4. 10,000 PSI High-Strength Structural Mix  

Each scenario successfully reproduced expected NDOT-style batch summaries.




# Key Engineering Concepts Applied

• Water-Cement Ratio (w/c)  
• Specific Gravity Volume Relationships  
• Unit Weight of Water (62.4 lb/ft³)  
• Absolute Volume Method  
• Aggregate Volume Distribution  
• Structured Function-Based Programming  
• Engineering Output Formatting  




# Technical Skills Demonstrated

- Python function design
- Modular programming structure
- Engineering unit conversion
- Numeric formatting using f-strings
- Process automation
- Validation testing
- Professional technical documentation




# References

- Nebraska Department of Transportation (NDOT) Mix Design Excel File  
- ACI Concrete Mix Design Principles  
- Course materials from CIVE 202  
-All NDOT reference materials and scenario sources are cited in:
**CIVE202_Spring2026_Group4_Project2_Report.pdf**




## Developed For:
Nebraska Department of Transportation (NDOT)  
University of Nebraska–Lincoln  
Department of Civil Engineering
