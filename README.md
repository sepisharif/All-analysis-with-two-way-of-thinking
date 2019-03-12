# All-analysis-with-two-way-of-thinking
There are seven files on this repository one file is checkingalldataset for the rest of other 6 files. but there are two 
categories file with the name of T2D in the beginnig or three criteria in the begining of their file names 
(two way of thinking to make cases) including :

"CheckingAllDatasetsforQCT2DCaseControl" file which is mainly making the cases and controls based on three criteria for T2D
that I have explained them o its RMD. Also try to find the real numer of individuals as a case and control afetr genotyping and
passing QC.

"T2DMasterDataset" is making the master datasets after finding the realated T2D variabes for 4 datasets and rename those related
variables as the same name then integrated all the datset and get rid of duplicated.
The case in all the files with the name of T2D in the begining were made based on the individulas, only in DIABETES column.

"T2DCasControlPopulation" is making cases and control for each populations based on just th eindividuals in DIABETES column,
and also calcluates some important statistical parameets to evaluste cases and controls in the poulations.

"T2DAssociationLogistiregression" is making the logistic regession to check the association bwteen T2D and BMI, WAIST and etc.

"TrhreeCriteriaT2DMasterDataset" is making the master datasets after finding the realated T2D variabes for 4 datasets and rename those related
variables as the same name then integrated all the datset and get rid of duplicated.
The case in all the files with the name of threecriteria in the begining were made based on the individulas, in DIABETES column
with the positive status or DIABETESTREAT column, who they are under T2D related treatment or DIABINCLUDEB,which is random 
glucose column> 11, in otherdatasets based on the literature review that i did i found the similar information in the columns
with different names and I change their name to be the same.

"ThreeCriteriaT2DCaseControlPopulation" is making cases and controls for T2D in different population and calcluates some important
statistical parameets to evaluste cases and controls in the poulations.

"ThreeT2DcriteriaAssociationBIMWAIST" is making the logistic regession to check the association bwteen T2D and BMI, WAIST and etc.

