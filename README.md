# Gene Expression
---
## Abstract
An overview of RNA sequencing and microarray gene expression analysis. This analysis includes exploring, visualizing and clustering the gene expression data by hierarchically-clustered heatmap, principal component analysis (PCA) and t-distributed Stochastic Neighbor Embedding (t-SNE). The analysis also includes code for cancer classification by using supervised machine learning on gene expression data.    


## Data
The RNA-sequencing gene expression level dataset is a fraction of the Illumina HiSeq dataset from  the cancer genome atlas (TCGA) pan-cancer analysis project (Weinstein, J.N. et al. 2013), and was retrieved from [UCI machine learning repository](https://archive.ics.uci.edu/ml/datasets/gene+expression+cancer+RNA-Seq). The data contain 801 observations, expression levels of 20532 genes, and labels of five cancers; breast (BRCA), kidney (KIRC), lung adeno (LUAD), Colon (COAD), and Prostate (PRAD). 

## Analysis
The data was first explored by performing hierarchically-clustering, and visualizing the result using a heatmap.

![heatmap](hi_cl_heatmap.png) 



Weinstein, J. N. et al. (2013), 'The Cancer Genome Atlas Pan-Cancer analysis project', Nat Genet 45 (10), 1113-1120. 
