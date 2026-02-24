# CIVE 202 Project #2  
## NDOT Concrete Mix Design

**Student:** Bhuwanraj Singh Parihar  
**Course:** CIVE 202 – Civil Engineering Analysis II  
**Client:** Nebraska Department of Transportation (NDOT)  
**Semester:** Spring 2026  

    



## Project Overview

This project translates the NDOT Concrete Mix Design Excel spreadsheet into a structured Python program. The goal is to replicate the engineering logic used in the NDOT mix design worksheet and convert it into reusable Python functions with sequential user inputs.

The program calculates material quantities for **one cubic yard of concrete**, including cement, supplementary cementitious materials (SCMs), water, aggregates, and air content.




## Project Objectives

- Recreate the NDOT “Mix Design” Excel tab in Python
- Convert spreadsheet formulas into structured Python functions
- Use sequential user input to define mix parameters
- Generate a contractor-ready mix weight table
- Validate the program using four realistic concrete mix scenarios




## Engineering Basis

All calculations are based on:

- **1 cubic yard of concrete**
- Volume balancing (total material volume = 27 cubic feet)
- Specific gravity conversions
- Water–cement ratio relationships
- Aggregate proportioning by percentage




## Program Capabilities

The Python model performs:

- Calculation of total cementitious content
- Determination of required water weight
- Volume conversion using specific gravity
- Air content volume calculation
- Remaining aggregate volume determination
- Final weight calculations for:
  - Cement
  - Fly Ash
  - Silica Fume
  - Other SCM
  - Fine Aggregate
  - Coarse Aggregate
  - Other Aggregate
  - Water




## Repository Contents

| File | Description |
|------|-------------|
| **NDOT Mix Design.xlsx** | Original Excel file provided by NDOT |
| **CIVE202_Spring2026_Bhuwanraj_Project2_PythonCode.ipynb** | Python implementation of mix design logic |
| **CIVE202_Spring2026_Bhuwanraj_Project2_ACD.docx** | Annotated Code Document explaining Excel-to-Python translation |
| **CIVE202_Spring2026_Bhuwanraj_Project2_SOW.docx** | Scope of Work outlining project tasks |
| **CIVE202_Spring2026_Bhuwanraj_Project2_Report.docx** | Final technical report submitted to NDOT |




## How to Run the Program

1. Open the Jupyter Notebook:
   `CIVE202_Spring2026_Bhuwanraj_Project2_PythonCode.ipynb`
2. Run cells sequentially.
3. Enter requested mix design inputs when prompted.
4. Review calculated material weights for one cubic yard.




## Mix Verification

The program was tested using four realistic concrete mix scenarios to verify:

- Logical consistency
- Proper volume balancing
- Accurate weight outputs
- Engineering plausibility




## References

- Nebraska Department of Transportation (NDOT) Mix Design Excel File  
- ACI Concrete Mix Design Principles  
- Course materials from CIVE 202  




## Reproducibility

All calculations follow deterministic engineering equations derived directly from the NDOT Excel worksheet. Given identical inputs, the Python model will always produce identical mix design results.
