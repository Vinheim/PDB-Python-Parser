# PDB-Python-Parser
This repository includes work done on a python PDB parser programming project for course CS 595, Introduction to Computational Biology. 
This program reads all lines and processes those that reference a protein secondary structure (alpha helix or beta sheet) from the input PDB (protein data bank) text file. 
Individual atom residue sequence numbers from all atoms in the file are compared against the sequence ranges of all identified secondary structures. 
If an atom's residue number falls within any of the structure ranges, then it is an atom that comprises a secondary structure, and is thus printed to an output pruned PDB file.
The result is a PDF file that, when opened in the UCSF Chimera 3D molecular structure visualization software, shows only alpha helices and beta sheets.
