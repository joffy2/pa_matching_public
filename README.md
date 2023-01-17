## TESTING THE UNOBSERVED COVARIATE ASSUMPTIONS OF STATISTICAL MATCHING FOR PROTECTED AREA EVALUATIONS
This repo contains the results of the literature review of protected area evaluations that use statistical matching and the code used to analyses the balance in unobserved confounders.

Data sources are for covarites detailed in appendix 1
link to the Google Earth Engine Script https://code.earthengine.google.com/a48c95248138b7adefbceba42613beff
Forest plot data is taken from SEOSAW databse contact them for access https://seosaw.github.io/ 

Code contains jupyter notebooks running on a R (4.0.5) kernal.
 - review_results notebook summarises the findings of the litriture review of protected area impact studies that use statistical matching
 - confounders notebook creates the dataset of confodunders for each IULA II plot and cluster and creates the map (figure 1)
 - matching notebook produces the matched datasets for the first stage of analysis using commonly used methods at both the cluster and plot level
 - randomised notebook creates 1000 matched datasets with randomly selected paramters and covarites
 - results notebook summarises the balacne in the unobervered confounders for all the matched datasets

