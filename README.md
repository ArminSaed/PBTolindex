# PBTolindex
# how to install and perform the functions in this package:
install.packages("C:/Users/saedm/Desktop/Tolerance indices/PBTolindex_1.0.1.tar.gz",
                 repos = NULL, type = 'source')

library(PBTolindex)

setwd("C:/Users/saedm/Desktop")

index()

corelplot()

scattermatrix()

threeD()

clust_heatmap()

pca_biplot()

perform_all()
