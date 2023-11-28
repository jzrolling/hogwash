#EDITED PACKAGE
Edited branch of katiesaund/hogwash with more extensive logging features to easy validation.
THIS IS EXPERIMENTAL CODE. USE AT YOUR OWN RISK. 

# Summary
The hogwash R package is a phylogenetically-informed, convergence-based method for performing genome-wide association studies in bacteria. In short, the user inputs a phylogenetic tree, a phenotype (either binary or continuous), and a genotype (a binary matrix) and receives an output of the genotypes that are significantly associated with the phenotype after correcting for multiple testing, requiring convergence, and accounting for the clonal structure of the population.
   
# Install the package
`install.packages("devtools")`  
`devtools::install_github("4C554D43/hogwash")`  
`library(hogwash)`
  
# Getting started
[Please check out the wiki](https://github.com/katiesaund/hogwash/wiki) or vignette for a brief primer on bacterial GWAS, detailed descriptions of the algorithms, and example data with results.

# The paper 
To learn about using hogwash on your bacterial data please read the paper ["Hogwash: three methods for genome-wide association studies in bacteria"](https://www.microbiologyresearch.org/content/journal/mgen/10.1099/mgen.0.000469). It describes the algorithms and their performance on simulated data. The simulated data used in the paper were generated using the code in this [repository](https://github.com/katiesaund/simulate_data_for_convergence_based_bGWAS). 


