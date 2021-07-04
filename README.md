# BigDataAnalytics

### GOAL: The objective of this project is to learn the foundaments of Big Data Analysis and apply them to a big dataset. More precisely with the Cancer Prediction dataset we try to answer the following questions:
- Is there a correlation between the genes expressed in the tumor cells?
- Which clinical information is correlated with each other?
- Which patients cluster together based on their gene expression?
- Is there a difference in gene expression between the clusters?
- Is there a difference in gene expression between living or dead patients?

### Dataset Used:
#### https://www.kaggle.com/abhiparashar/cancer-prediction?select=PAAD.gct

#### Before running the Jupyter Notebook install the following packages in R:
install.packages("BiocManager")
BiocManager::install("Rgraphviz")
install.packages('Hmisc')
install.packages('Seurat')
install.packages("data.table")
install.packages("lubridate")

