This repository contains the script command files, which were developed to perform classification of structural patterns of RNA–protein interactions. 
To execute the script command files, kindly install the GrandIso-Network from the given link: https://github.com/aplbrain/grandiso-networkx .
Pattern annotation was performed using the GrandIso-Network algorithm, which implements a subgraph isomorphism approach to identify recurring structural patterns within RNA–protein interaction complexes.
Therefore, the functions of the script command files are summarized and listed below:
1. Shows the hydrogen bonds between amino acids and nucleic acids in the opened PDB structure complexes and saves them into files.
2. Extraction of the required selection of residues and removal of non-standard residues.
3. Selection of the number of residues required for analysis and specific pattern types based on the number of residues needed for 3D pattern extraction.
4. Removal of duplicates and saving into .lp files.
5. Calculation of the total number of patterns before and after duplicate removal.
6. Collection of hydrogen bond information data from PDB structures.
7. Collection of pattern and PDB ID, pattern sequence, and residue pattern, and saving into a pattern type CSV file.
8. Extraction of hydrogen bonds for each line in the CSV file and saving them into a folder.
9. Classification of the extracted 3D pattern arrangements.
