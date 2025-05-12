# BAN-6420-Module-2---Salary-Function
# San Francisco Salaries Analysis

## Files Included
- `Salary_Analysis.ipynb`: Python Jupyter notebook with data processing
- `unzip_profile.R`: R script for unzipping and displaying data
- `Employee_Profile.zip`: Sample output file (optional to include)

## How to Run

### Python Notebook
1. Open `Salary_Analysis.ipynb` in Jupyter
2. Run all cells sequentially
3. The notebook will:
   - Import salary data
   - Process into dictionary
   - Export employee profiles

### R Script
1. Run the Python notebook first to generate zip files
2. Execute `unzip_profile.R` in RStudio or with:
   ```bash
   Rscript unzip_profile.R
   ```

## Requirements
- Python 3.x with Jupyter
- R with required packages (IRkernel for notebook)
- pandas, rpy2 (for Python-R integration)
