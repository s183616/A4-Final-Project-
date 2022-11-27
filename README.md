# A4-Final-Project-
# 41934 Advanced BIM, Assaignment 4 Final Project
## Group 16: Isabella Vad (s183616) and Amalie Hartvig Jensen (s183619)

**Step-by-step guide to use the tool:**

Export your BIM project to .ifc file format and save on your device. 
Open the main.py file in the tool folder.
In code line XX, insert the file path of your .ifc file. 
Press Run code. -> .json files will automatically be generated in the tool folder in a folder named ‘output’. 
Open LCAbyg 5 (v.5.2.1.0) or install LCAbyg with the installation file provided in the tool folder (NB: for Windows only, otherwise visit: https://old.lcabyg.dk/download-program).
In LCAbyg, click on ‘Filer’ -> ‘Ny’ ->  ‘Tomt projekt’, to open a new empty project.  
Click on ‘Filer’ -> ‘importer komponenter fra json’, to import generated json components. 
Choose the generated ‘output’ folder and press ‘Select Folder’ 
Under the ‘Bygningsmodel’ module, the building element beams from the ifc file are generated and displaying its corresponding data ‘Konstruktioner’, ‘Byggevare’, ‘Faser’ by clicking on the element (see Figure 4). 
Note, the amounts(‘mængde’) and units under the ‘Konstruktioner’ and ‘Byggevarer’ tabs must be manually specified (see Figure 5). 
Read the LCA results under the ‘Resultater’ module and in ‘Analyse og rapport’ for graphic representations. 

<img src=" diagram_tool.svg">
