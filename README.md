The Breast Cancer dataset that is being used contains an array gene expression with a 251 set of data consisting of detailed information about the breast-cancer patients like survival time, LNstatus, tumor size in mm, age ,PRstatus, histgrade etc.

The given dataset is analyzed by performing the Differential Gene Expression (DGE) analysis to estimate the survival rate and breast- cancer.

First normalization is implemented to the given dataset in consideration to identify any important differences and a denogram is generated. Unfortunately, the generated denogram fails to provide complete information so as to which gene adds value to the clusters. To solve this we generate heatmap and observe the up and down-regulated genes. The data then generated is insufficient for our analysis and hence we opt for PCA - principal component analysis and gain dimensionally reduced data. The DE analysis is carried out after PCA plot. The DE analysis happens with a precondition of having 0.05 as q value.DE analysis helps us find the gene score. Indicators for breast cancer metastasis are cox regression, tumor size, and lymph node metastasis. The final output of our analysis showcased that between the tumor size and lymph node metastasis there was important association statistically also these are played an important role in the survival and have got various survival prognosis. 
