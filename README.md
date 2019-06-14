# Summary
The hogwash R package is a phylogenetically-informed, convergence-based method for performing genome-wide association studies in bacteria. In short, the user inputs a phylogenetic tree, a phenotype (either binary or continuous), and a genotype (a binary matrix) and receives an output of the genotypes that are significantly associated with the phenotype after correcting for multiple testing, requiring convergence, and accounting for the clonal structure of the population.
   
# Install the package
`install.packages("devtools")`  
`devtools::install_github("katiesaund/hogwash")`  
`library(hogwash)`
  
# Getting started
[Please check out the wiki](https://github.com/katiesaund/hogwash/wiki) for a brief primer on bacterial GWAS, detailed descriptions of the algorithms, and example data & results.  


