This scripts are intended to prepare, from fastq sequences, the most relevant .h5ad matrix for CardamomOT

Execute in the following order:

Define_cells.ipynb

Define_time.ipynb

Define_genes.ipynb



Notes: 

1. The original .fastq files have to be aligned first using STARSolo as shown on top of Define_cells.ipynb.

2. Iteration is of essence. You will have to run all the scripts many times, since for example the cell type definition will impact your gene list, the velocity analysis may help you to refine the cell type definition, etc...

3. Define_genes will require Irkernel to be installed.
