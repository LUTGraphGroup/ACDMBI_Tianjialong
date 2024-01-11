# ACDMBI
ACDMBI：A deep learning model based on community division and multi-source biological information fusion predicts essential proteins
## Data:
（1）The file **./Data/CentralityData/BioGRID_centrality.csv** contains the initial features of the protein-protein interaction network obtained through community division.  

（2）The file **./Data/Gene_Data/BioGRID_gene.xlsx** contains the gene expression data of proteins.  

（3）The file **./Data/Protein_data/BioGRID.xlsx** contains the protein-protein interaction network data.  

（4）The file **./Data/Subcellular_Data/BioGRID/Top_1024_normalized.csv** contains the subcellular localization information data of proteins.  


## Code:
（1）The file **Community_Division.py** generates the initial features of the protein-protein interaction network obtained through community division.  

（2）The file **DNN_Subcellular.py** extracts features of proteins from subcellular localization information.  

（3）The file **GCNmodel.py** enriches the initial features of the protein-protein interaction network using GCN.  

（4）The file **LSTM_gene.py** extracts data from genes.  

（5）The file **Classification.py** predicts key proteins.  
