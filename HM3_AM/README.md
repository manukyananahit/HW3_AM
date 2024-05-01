###Homework 3 - Survival Analysis
##Author: Anahit Manukyan

#Overview
This Jupyter Notebook is dedicated to performing survival analysis as part of a homework assignment. The primary goal is to analyze customer data and determine factors that influence the survival time of customers, using various statistical models and tools.

#Contents
1. Building models using AFT fitters - This section evaluates different Accelerated Failure Time (AFT) models to find the best performer based on criteria such as AIC (Akaike Information Criterion), BIC (Bayesian Information Criterion), and log-likelihood values. The LogNormalFitter is selected for detailed analysis due to its superior performance metrics.
2. Significant Features Identification - Identification of significant features that impact customer survival times. Features with a p-value less than 0.05 are considered significant, and their effects on survival times are analyzed, including both increases and decreases in survival likelihood.
3. Customer Lifetime Value (CLV) Analysis - Exploration of the Customer Lifetime Value, particularly focusing on different customer categories, with an analysis of the "Plus Service" category and its impact on survival likelihood.
4. Report - A summary report of the findings and conclusions from the survival analysis.

#Key Findings
1. The LogNormalFitter model is the most suitable for our survival data based on its lower AIC and BIC scores and higher log-likelihood.
2. Several customer features significantly affect survival times, such as customer category, marital status, and service usage.
3. Customers in the "Plus Service" category have a higher likelihood of prolonged engagement with the service.

#Usage
To run this notebook: Open the notebook and run all cells sequentially to replicate the analysis and view the plots and statistical outputs.

#Dependencies
Python 3
Libraries: pandas, numpy, lifelines (for survival analysis), matplotlib, seaborn (for plotting)