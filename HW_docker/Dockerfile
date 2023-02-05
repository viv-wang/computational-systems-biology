# build from base image
FROM risserlin/bcb420-base-image:winter2023

# install packages DESEq2 and pheatmap
RUN R -e 'BiocManager::install("DESEq2")' 
RUN R -e 'install.packages("pheatmap", dependencies=TRUE, repos="http://cran.rstudio.com/")'
