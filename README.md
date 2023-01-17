# Testing the unobserved covariate assumptions of statistical matching for protected area evaluations
This repo contains the results of the literature review of protected area evaluations that use statistical matching and the code used to analyses the balance in unobserved confounders.

Data sources are for covariates detailed in appendix 1. Code for those taken from Google Earth Engine – here https://code.earthengine.google.com/a48c95248138b7adefbceba42613beff 

Forest plot data is taken from SEOSAW database contact them for access https://seosaw.github.io/

Code contains jupyter notebooks running on a R (4.0.5) kernel.
 - review results notebook summarises the findings of the literature review of protected area impact studies that use statistical matching.
 - covariates notebook creates the dataset of matching covariates for each IULA II plot and cluster and creates the map (figure 1). 
 - matching notebook produces the matched datasets for the first stage of analysis using commonly used methods at both the cluster and plot level.
 - randomised notebook creates 1000 matched datasets with randomly selected parameters and covariates.
 - results notebook summarises the balance in the unobserved confounders for all the matched datasets.


