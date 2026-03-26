Execute in the following order:

Define_cells.ipynb

Define_time.ipynb

Define_genes_1.ipynb

bub_H.R

Define_genes_2.ipynb (will require merge_table.csv)


Notes: 

1. The original .fastq files have to be aligned first using STARSolo as shown on top of Define_cells.ipynb.

2. iteration is of essence. You will have to run all the scripts many times, since for example the cell type definition will impact your gene list, the velocity analysis may help you to refine the cell type definition, etc...

3. Define_genes_3.ipynb will do the same job as combining Define_genes_2.ipynb,  bub_H.R and Define_genes_2.ipynb. It will require Irkernel to be installed.
