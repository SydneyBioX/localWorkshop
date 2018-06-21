# Finding 'Omics Biomarkers: Classification of High-dimensional Biological Data with R

This repsitory contains presenter slides and data files used for the presentation at Charles Perkins Centre on 29 June 2018.

To install Bioconductor software, BiocInstaller must firstly be obtained from CRAN.

```
install.packages("BiocManager")
library(BiocManager)
```

Before attending the workshop, ensure R is at least version 3.5.0 and install ClassifyR using

```
install("ClassifyR", dependencies = TRUE)
```

Additionally, DESeq2 and EDASeq are used for some exploratory visualisations. They can be installed by running the command

```
install(c("DESeq2", "EDASeq"))
```

Also, dowload the two data files `counts.txt` and `samples.txt` stored in the `data` directory. The easiest way to get them is to download the whole repository by clicking on the Clone or Download button in the top-right corner of the GitHub web page of the workshop and download a ZIP file.

