 *****************************************************************
* Predicting protein-ligand binding affinity with machine learning *
* ________________________________________________________________ *



 **************************
* Description of contents: *
* ________________________ *
 

|------------------------
| demo_presentation.pptx |
| =======================
|
| PowerPoint presentation for the demo of the project
|

|------------------
| descriptions.pdf |
| =================
|
| PDF file containing a list with explanations for all the descriptors
| used in the dataset to describe the protein and small molecule complexes
|

|-----
| src |
|=====
|
| Directory containing source code in Jupyter notebooks
|

|---------
| html_src |
|=========
|
| Directory containing the Jupyter notebooks in HTML format
|


 **************************
* Contents of src:         *
*                          *
* (recommended to be read  *
*  in this order)          *
* ________________________*
 


|-----------------------
| Preparing_index.ipynb |
| ======================
|
| Contains the process of filtering data and creating the main index data table
|

|--------------------------
| Protein_descriptors.ipynb |
|==========================
|
| Describes the sourcing of sequence and DSSP data, and their processing to generate 
| the data describing the proteins
|

|-----------------------------
| Molecular_descriptors.ipynb |
|=============================
|
| Describes the process of sourcing new .sdf files for the molecules in the dataset, 
| and the use of the Mordred python library to generate the molecular descriptors 
| for the molecules in the dataset
|

|----------------------
|Data_and_models.ipynb |
|======================
|
| Jupyter notebook detailing the process of combining the data tables generated in 
| the previous notebooks, the splitting of the data into training and testind sets, 
| and the training of the machine algorithms used to predict the affinity
|

|-----------------
|requirements.txt |
|=================
|
| A requirements file with the list of required packages to run the code
|