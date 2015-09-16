# keggmapper
A R package to do the same thing as KEGG Mapper

## Installation
```R
install.packages("devtools")
## try http if https is not available
source("https://bioconductor.org/biocLite.R")
biocLite("KEGGREST")

library(devtools)
install_github("kozo2/keggmapper")
```

## Examples
```R
library(keggmapper)
hitstable <- mapCpd(cpdIDlist)
```