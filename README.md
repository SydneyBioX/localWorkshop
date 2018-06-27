# Finding 'Omics Biomarkers: Classification of High-dimensional Biological Data with R

This repsitory contains presenter slides and data files used for the presentation at Charles Perkins Centre on 29 June 2018.

To install Bioconductor software, BiocManager must firstly be obtained from CRAN.

```
install.packages("BiocManager")
library(BiocManager)
```

Before attending the workshop, ensure R is at least version 3.5.0 and install ClassifyR using

```
install("ClassifyR", dependencies = TRUE)
```

Additionally, DESeq2, EDASeq and genefilter are used for some exploratory visualisations and analysis. They can be installed by running the command

```
install(c("DESeq2", "EDASeq", "genefilter"))
```
