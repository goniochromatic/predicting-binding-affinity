# Predicting protein-ligand binding affinity with machine learning


## Description of contents (recommended to read in this order):


### 1. Preparing_index.ipynb

Contains the process of filtering data and creating the main index data table

### 2. Protein_descriptors.ipynb

Describes the sourcing of sequence and DSSP data, and their processing to generate 
the data describing the proteins

### 3. Molecular_descriptors.ipynb

Describes the process of sourcing new .sdf files for the molecules in the dataset, 
and the use of the Mordred python library to generate the molecular descriptors 
for the molecules in the dataset

### 4. Data_and_models.ipynb

Jupyter notebook detailing the process of combining the data tables generated in 
the previous notebooks, the splitting of the data into training and testind sets, 
and the training of the machine algorithms used to predict the affinity

### 5. Descriptions.pdf

Contains a list of descriptions for all the features that were used for training

### 6. requirements.txt

A requirements file with the list of required packages to run the code
