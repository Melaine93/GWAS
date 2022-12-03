# GWAS
Genome-wide association studies (GWAS) to identify genes associated with a particular trait. This method studies the entire set of DNA of a large group of individuals, searching for small variations, called single nucleotide polymorphisms (SNPs).
# Requirements:
- R et R Studio: https://posit.co/download/rstudio-desktop/
- rMVP: https://github.com/xiaolei-lab/rMVP
# pheno = phenotype data
# geno.hmp = genotype data
# Analysis:
# No_compression  
# with_compression improves statistical power
# parameters analysis based on clustering methods to group individuals based on their kinship
# MLMM (Multiple Loci Mixed Linear Model) use forward-backward stepwise
# linear mixed-model regression to include associated markers as covariates 
# FarmCPU iterative method where markers are tested against the associated markers
# mvp 
