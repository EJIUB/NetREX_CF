# NetREX_CF

We introduce  NetREX_CF -- Regulatory **Net**work **R**econstruction using **EX**pression and **C**ollaborative **F**iltering -- a GRN reconstruction approach that brings together a modern machine learning strategy (Collaborative Filtering) to address the incompleteness of the prior knowledge 
and a biologically justified model of gene expression (sparse Network Component Analysis based model).

In this GitHub page, we provide the python source codes of our NetREX_CF.

## Prerequest
1. Install https://implicit.readthedocs.io/en/latest/
2. Install https://www.cvxpy.org/ 
3. Install https://progressbar-2.readthedocs.io/en/latest/

## How to run?
1. Download data (Link shown in ./S2Cell/Readme.md)
2. Download Notebook/NetREXCF_S2Cell.ipynb
3. Put the data and the jupter notebook in the same folder
4. Open the jupter notebook and run.

## Imput format
NetREX_CF needs two inputs: expression data and prior data. One example of NetREX_CF's input can be found in Notebook/NetREXCF_S2Cell.ipynb
1. Expression data is genes by samples. 
2. Prior data is genes by TFs. The row names of expression data and prior data should be well aligned. 
