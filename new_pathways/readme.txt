## Readme

Files in this repository
 - New_reactions.v0.ipynb - this file is the demo version, in which the reactions have been manually implemented.
    This file needs:
      - limonene_path.py
      - pinocembrin_path.py
      - strainlist.py
      
- New_reactions.v1.ipynb - First version of the automatized process
    This file needs:
      - limonene.v3.path  --> dataframe format, tabular separated data
      - pinocembrin.v3.path  --> dataframe format, tabular separated data 
      - strainlist.py
      - newpath.py --> libraries with functions to include new pathways in existing cobra models
      
      
      
Note: it is necessary to create a subfolder called "Ecoli_strains" in which all the strains from ecoli present in 'strains.py' exist in JSON format
