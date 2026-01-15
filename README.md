# Predicting Company Sector Using ESG Risk Factors

## Overview
This project investigates whether a company’s sector can be predicted using Environmental,
Social, and Governance (ESG) risk factors. Using ESG risk scores across multiple industries, we
perform exploratory data analysis to identify sector-specific risk patterns and then apply a
Random Forest classifier to model the relationship between ESG risks and company sector.

The results show that ESG risk profiles vary meaningfully by industry and can be used to predict
company sector with moderate accuracy, suggesting that sustainability risks are not uniform
across sectors.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/aplancher/ESG-Risk.git
2. Navigate to project directory
   cd ESG-Risk
3. Install libraries
   pip install pandas numpy matplotlib scipy scikit-learn
4. Open in any Jupyter-compatible environment
   (e.g., Jupyter Notebook, VS Code, Google Colab)
5. Run all cells in order
   This notebook will perform exploratory data analysis, train a Random Forest classifier, and evaluate model performance using standard classification metrics. 
