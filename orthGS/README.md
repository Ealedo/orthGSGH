# orthGS
R package to Analyse Orthology-Paralogy Relationships among Glutamine Synthetase from Plants.

## Installing

To install this package, start R and enter:

`if (!requireNamespace("BiocManager", quietly = TRUE))
    install.packages("BiocManager")`
 
`BiocManager::install("Biostrings")`
`BiocManager::install("muscle")`
install.packages("orthGS")` 


To get the version currently in development (not tested) you must have the 'devtools' package installed and type in the console:

devtools::install_github(repo = "ecaledo/orthGSGH", subdir ="EnvNJ")

If desired, any previous version can be installed:

devtools::install_github(repo = "ecaledo/orthGH", subdir = "versions/orthGS_v0.1.3")

## Contact

Your are welcome to:

* Send us an email to: elenaaledoesteban@gmail.com
