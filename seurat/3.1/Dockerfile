FROM upendradevisetty/bioconductor:1.0

RUN apt-get update && apt-get install -y libpng-dev

RUN Rscript -e 'install.packages(c("Matrix", "ggridges", "png", "cowplot", "devtools", "Seurat", "ggrepel"));'
