# RBioMiRGS
Simple to use package for both microarray and RNAseq data analysis (limma based)

Installation:

  - Install devtools
  
        install.packages("devtools")
    
  - Install bioconductor
  
        source("https://bioconductor.org/biocLite.R")
      
        biocLite()
    
  - Install the package
  
        devtools::install_github("jzhangc/git_RBiomiRGS/RBiomiRGS", repos = BiocInstaller::biocinstallRepos())   

Update log

    0.1.2
      - In addition to the environment, rbiomirGS_mrnalist() now outputs csv files of the mRNA resutls, as well as a hsa entrez list to the environment for modelling use

    0.1.1 (March.27.2017)
      - miRNA to mRNA function rbiomirGS_mrnalist() added.

    0.1.0 
      - Initial release
