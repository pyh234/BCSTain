# BCSTain
Undergraduate graduation project：model to predict spatial transcriptome from H&amp;E image
## introduction  
spatial transcriptomics play a crucial role in the classification diagnosis and treatment of breast cancer. It can help reseachers discover spatial location relationship of cells and identify the important spatial domains in tumors, so as to effectively promote the prograss of related research. However, the high cost limits the large-scale clinical application of spatial transcriptome. In contrast, a large number of publicly available tumor H&E stained image data are rich in clinical annotation information. By predicting the spatial transcriptome from a large number of H&E stained images of breast cancer at a lower cost, researchers can conduct downstream analysis combined with clinical information annotation, thus in-depth understanding of the association between the spatial structure of tumors and their prognosis, providing new insights for breast cancer diagnosis and treatment.  

## task
we use existing foundation model to extract features from H&E image. And downstream classifier maps image features into gene expression. During the training progress, the foundation model will be tuned by LoRA.    

## result  
Compared to existing tools, including **ST-Net**, **HisToGene**, **Hist2ST**, BCSTain can predict a **larger number** of gene of spatial expression. BCSTain also demostrates better perfomance in both **gene expression prediction accuracy** and s**patial region identification**.  

## figure  
![Model display diagram](./images/model.pdf)   
![Comparison of gene expression](./)
