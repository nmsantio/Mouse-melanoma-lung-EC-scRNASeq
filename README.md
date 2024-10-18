SYSTEM REQUIREMENTS

Windows Operating system 

Computer with minimum: 

-64 Gt RAM

-CPU with 8 cores or more

- 1 Tb of hard disk space

1: Install R (Version: 4.4.1) 

2: Install RStudio (Version: 2024.04.2+764)

Install the following R packages:

BiocNeighbors	https://www.bioconductor.org/packages/release/bioc/html/BiocNeighbors.html 

CellChat	http://www.cellchat.org/  

ClusterProfiler	https://bioconductor.org/packages/release/bioc/html/clusterProfiler.html 

ComplexHeatmap	https://jokergoo.github.io/ComplexHeatmap-reference/book/index.html 

data.table	https://rdatatable.gitlab.io/data.table/

DoubletFinder	https://github.com/chris-mcginnis-ucsf/DoubletFinder

dplyr		https://dplyr.tidyverse.org/

enrichplot	https://bioconductor.org/packages/enrichplot.

ggalluvial	https://corybrunson.github.io/ggalluvial/

ggplot2		https://ggplot2.tidyverse.org/

glmGamPoi	https://github.com/const-ae/glmGamPoi

heatmaply	https://talgalili.github.io/heatmaply/

htmltools	https://rstudio.github.io/htmltools/

Igraph		https://r.igraph.org/

maftools	https://bioconductor.org/packages/devel/bioc/vignettes/maftools/inst/doc/maftools.html 

magrittr	https://magrittr.tidyverse.org/

nichenetr	https://github.com/saeyslab/nichenetr

Matrix		https://rdrr.io/rforge/Matrix/

NMF		https://renozao.github.io/NMF/devel/index.html 

patchwork	https://patchwork.data-imaginist.com/

pathview	https://pathview.r-forge.r-project.org/ 

plotly		https://plotly.com/r/getting-started/

RColorBrewer	https://r-graph-gallery.com/38-rcolorbrewers-palettes.html

Reticulate	https://rstudio.github.io/reticulate/

scCustomize	https://samuel-marsh.github.io/scCustomize/index.html

rstatix		https://rdrr.io/cran/rstatix/

Seurat		https://satijalab.org/seurat/

SeuratDisk	https://github.com/mojaveazure

tidyverse	https://www.tidyverse.org/

Ucell		https://rdrr.io/github/carmonalab/UCell/

viridis		https://cran.r-project.org/web/packages/viridis/vignettes/intro-to-viridis.html


INSTALLATION QUIDE

https://posit.co/download/rstudio-desktop/

estimated install time: 30 min - 1 h

See links above for R package installation.

INSTRUCTIONS FOR USE

DATA 1. Mouse melanoma and control lung data


Download data:

https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE235394

https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE253749

https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE253751



set1 (exp1) GSE235394, access code: unmnswysnbkbfed 

set2 (exp2) GSE253749, access code: sdcbkssgblypdyn  

set3 (exp3) GSE253751, access code: otclcwsybzuhtyf 



Follow code at 

https://github.com/nmsantio/Mouse-melanoma-lung-EC-scRNASeq

Step 1. Mouse Melanoma Data reading



prior to beginning install all packages listed above and name the data folders accordingly:



main folder: 

exp1 

subfolders: 

c (063barcodes.tsv.qz, 063features.tsv.gq, 063matrix.mtx.gz)

6h (064barcodes.tsv.qz, 064features.tsv.gq, 064matrix.mtx.gz)



main folder: 

exp2 

subfolders: 

c (052barcodes.tsv.qz, 052features.tsv.gq, 052matrix.mtx.gz)

6h (051barcodes.tsv.qz, 051features.tsv.gq, 051matrix.mtx.gz)

28h (053barcodes.tsv.qz, 053features.tsv.gq, 053matrix.mtx.gz)



main folder: 

exp3 

subfolders: 

c (058barcodes.tsv.qz, 058features.tsv.gq, 058matrix.mtx.gz)

6h (059barcodes.tsv.qz, 059features.tsv.gq, 059matrix.mtx.gz)

Step 2. Find Doublets

Step 3. Data integration and clustering


Additional visualization instructions can be found from the above mentioned links, mainly at

https://satijalab.org/seurat/

https://samuel-marsh.github.io/scCustomize/index.html
