# CopulaPhenoImpute1.0
Package: CopulaPhenoImpute1.0
Type: Package;
Title: Phenotype Imputation With Copula Model;
Version: 0.0.1;
Author: Jianjun Zhang, Jane Zizhen Zhao, Samantha Gonzales, Xuexia Wang, Qiuying Sha;
Maintainer: Jane Zizhen Zhao <jan3zhao@ad.unc.edu>;
Description: Methods for phenotype imputation based on a Gaussian copula model with three different loss functions (Square, Uniform, Quantile);
License: GPL-3;
Encoding: UTF-8;
LazyData: true;
Imports: 
    MASS,
    mvtnorm,
    stats
RoxygenNote: 7.3.2;
URL: https://github.com/janezhao888/CopulaPhenoImpute1.0;
Depends: 
    R (>= 2.10)

# It can be installed and tested using  the following code below:

## devtools::install("/path/to/CopulaPhenoImpute1.0")

devtools::install_github("https://github.com/janezhao888/CopulaPhenoImpute1.0")


?copulaImputation
copulaImputation(simulated_phenotype, lossfunction = "square", impute_col = 3) #simulated_phenotype comes with the package for easy testing

