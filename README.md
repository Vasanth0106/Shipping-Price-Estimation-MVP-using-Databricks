# Shipping Cost Estimator Pipeline

## Summary
This project builds a shipping cost estimation pipeline for e-commerce orders using PySpark on Databricks.  
It generates synthetic product weights, dimensions, and locations, then calculates shipping distance with the Haversine formula.  
Effective shipping weight (physical vs volumetric) and a simple pricing formula are used to estimate shipping costs.  
Results are saved as a Delta Lake table for easy querying and analysis.

## Setup
1. Use a Databricks workspace with PySpark.  
2. Upload the notebook (`.py` or `.ipynb`).  
3. Ensure access to the sales report table `workspace.salesdata.sale_report` or adapt the code accordingly.  
4. No extra dependencies needed.

## Running the Pipeline
- Run the notebook step-by-step to load data, generate synthetic attributes, calculate distances and weights, compute shipping costs, and save output as a Delta table.  
- Query the Delta table for results or downstream use.

## Code Highlights
- Clear modular steps with comments covering data loading, synthetic data creation, distance calculation, weight and cost computation, and data saving.

## AI Assistance
- ChatGPT helped refine the code and document the process.  
- Databricks provided the scalable PySpark environment.



