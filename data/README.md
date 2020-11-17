### Data folder

The data directory contains data used in the analysis. This is treated as read only; in paricular the R/python files are never allowed to write to the files in here. Depending on the project, these might be csv files, a database, and the directory itself may have subdirectories.

Dataset Description:

Y is the outcome (continuous) 
A is a binary treatment indicator
V1 through Vp are covariates. (The number of covariates, p, varies across datasets. Could be binary or continuous)

Data source: Atlantic Causal Inference Conference (ACIC) Data Challenge

