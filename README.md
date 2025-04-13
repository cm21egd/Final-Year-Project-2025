This folder contains the code which has been used in this project in order to achieve the final solubility predictions as stated in my final report. 
Part 1 contains the code of how I combined the two data sets provided into a single file with duplicates averaged. This is followed by the code used to clean the data to give a refined input and increase data coverage. Part 3 calculates the data coverage of my final file. 
Parts 4 and 5 convert the SMILES of the solutes into xyz files which explain the shape of the molecule in 3D, and converts this inot a MOPAC input file which contains information for MOPAC to process the compounds and their solvents, and resolve these into descriptor values.
Part 6 contains code used for the extraction of all of the descirptors for the machine learning. 
Part 7 is the generation of MOPAC input files for the solvents in order to calculate the HOMO and LUMO for each of the solvents to calculate the difference of these to the solutes.
The final parts are the machine learning code and evaluation parameters to calulate how accurate these methods were at calculating the solubility of these compounds in various solvents. 
The Initial and Final Datasets are included, in which information of the solvents and solutes and their experimental logS values. 
