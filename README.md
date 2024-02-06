# metabolomics-clustering-analysis-pipeline

This repo contains a notebook with the pipeline for metabolomics data assessment
The pipeline follows the steps:
1) filtering out metabolites with bad signal or marked batch effect
2) reducing the dimensionality and clustering
![plot](biplot with cluster.png)
3) correlating clusters with output data:
   
      3.1)  correlating clusters with output patient data


      3.2)  correlating clusters with genomics data (manhattan plot generation)


This repo only shows the code to run the pipeline, original data is not shared. Only the shape of the data is shown 
