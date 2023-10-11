# GE-MFAT
A Feature-representation-transfer Method for Predicting Interactions between Proteins and Metabolites Based on Graph and Focusing Attention Mechanism
## Code description
The files starting with util is the processing code for each dataset.   
The files starting with k_fold are the training codes for each dataset.  
The files starting with dglNet is the util for construct the GCN.  
case_study_snap.py is the code for case study.
## Environment
For details environment.yml  
## Data
The data used in paper can be obtained on https://drive.google.com/drive/folders/1y71QppidGzh_Rfga6ae9fidrQs7pSrdK?usp=drive_link
## Pipline
1. Constructing GCN network nodes and relationships using the files starting with util.
2. Constructing GCN embedding features with dglNet files.
3. Constructing features for train using the file starting with util.
5. Training the model using the file starting with k_fold.
6. Predicting the case study with case_study_snap.py.
