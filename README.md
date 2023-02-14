#  Project structure for a computational research project
## **Main folder (Name of the folder: Docking study)**

Subfolders:

1.Raw_data :
  Metadata (word doc),
  Receptor_docking sites (.csv file)

2.Output files
  
  Figures :
    Fig_receptor,
    Fig_docking
    
  Documents :
    Manuscript,
    Draft_article
    
  Analysis files :
    Receptor_analysis,
    Docking_analysis
    
  Scripts :
     R_files,
     R_analysis code,	
     R_figures code

3.README.txt

4.README.md (current file)

I would be working on a receptor ligand interaction project. 
This would be a docking study (i.e to study ligand receptor interaction), to understand at what particular site of the receptor would a ligand bind to. 
So initially, I would create a main folder named “Docking study”. 
The name of the folder is itself indicative of the main objective of the study and is easy to comprehend, as it explains the content. 
Within this main folder, I would create 3 subfolders and one README.txt file.

First sub folder would be a named as “raw_data” within which a metadata(word) file and a docking study raw data text file in the format of .csv(comma separated values) file would be present. 
The metadata file would describe the information about the raw data (.csv file) (eg : File name, Description, column name, data type, column description). 
The .csv raw data can later be imported into an excel sheet (.xlsx) file, by text import option and choosing appropriate delimiter/fixed data options

Second sub folder will be named as “Output files”, which would again contain 3 sub folders named “figures”, “documents”, “Analysis files”. 
Within the “figures” folder, all the figures generated via R script would be named appropriately (eg : Fig_receptor, Fig_docking). 
The “documents” folder will contain the “manuscript” and “draft_article” for comprehending the project. 
The Analysis files would contain “Receptor_analysis” and “Docking_analysis” files , which would be used to analyse the raw data.

The third Sub folder will be named “scripts”, which would contain all the code written in R programming language to generate figures and analyse raw data. 
The R scripts will be named as “R_analysis code”, “R_figures code”.

The fourth file is the README.txt file , which is a plain text file. 
It will contain information about : What do the files contain ?, how are they obtained/generated ?. 
It would contain more information about how were the raw data and meta data generated, process of analysis workflow, organizational scheme, project purpose, R packages used etc. 
Overall, it is a text file to document the work done and it would represent the contents about the project in a way that humans can understand and contemplate.

I chose this particular project structure as I wanted keep the raw data separate from output/derived files and segregate the files that contained code (R script). 
I felt this approach is of utmost importance, particularly when we deal with large sets of data and we might later get confused on aspects like - what data set generated which figure ?, which file contains raw data and which contains processed data etc. Overall, this weeks lecture on reproducibility.

## Figure to display substarte receptor inetraction 
![Example image of Docking site and substarte interaction](https://ccsb.scripps.edu/wp-content/uploads/2019/03/nihms350924f9.jpg)
