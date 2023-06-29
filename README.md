# 🧬 dt4dds_notebooks

- [Overview](#overview)
- [Software Requirements](#software-requirements)
- [Installation Guide](#installation-guide)
- [Data Sources](#data-sources)

# Overview
This repository contains the data analysis, in the form of Jupyter Notebooks and data files, for the error characterization and figures in the following publication:
> Andreas L. Gimpel, Wendelin J. Stark, Reinhard Heckel, Robert N. Grass. Experimental quantification of errors and biases in DNA data storage for a digital twin. Manuscript in preparation.

The Python package `dt4dds`, providing a customizable, digital representation of the widely-used DNA data storage workflow involving array synthesis, PCR, Aging, and Sequencing-By-Synthesis, is found in the [dt4dds repository](https://github.com/fml-ethz/dt4dds).

# Software requirements

The data analysis has been tested and performed on Windwos 10 using Python 3.10. The following Python packages are required: 
```
dt4dds
statsmodels
scikit-learn
```

# Installation guide
To clone this repository from Github, use
```bash
git clone https://github.com/fml-ethz/dt4dds_notebooks
cd dt4dds_notebooks
```


# Data sources
Some of the analysis in this repository is based on sequencing data from other publications.

## /data/DNAFountain
> Yaniv Erlich, Dina Zielinski. DNA Fountain enables a robust and efficient storage architecture. Science 355, 950-954 (2017). DOI:10.1126/science.aaj2038

The `MasterPool` and `DeepCopy` datasets were used for the characterization of the efficiency distribution. The data is publicly available in the ENA archives [here](https://www.ebi.ac.uk/ena/browser/view/PRJEB19305) and [here](https://www.ebi.ac.uk/ena/browser/view/PRJEB19307).



## /data/DoT
> Koch, J., Gantenbein, S., Masania, K. et al. A DNA-of-things storage architecture to create materials with embedded memory. Nat Biotechnol 38, 39–43 (2020). https://doi.org/10.1038/s41587-019-0356-z

All `Bunny` datasets, including the generations, were used for the characterization of the efficiency distribution and for external validation. The data is publicly available in this [figshare repository](https://figshare.com/s/283543df2b734b7988c6).


## /data/MolecularBias
> Chen, YJ., Takahashi, C.N., Organick, L. et al. Quantifying molecular bias in DNA data storage. Nat Commun 11, 3264 (2020). https://doi.org/10.1038/s41467-020-16958-3

The datasets `run36.npy` and `run42.py` were used for the characterization of the efficiency distribution. The data is publicly available in this [GitHub repository](https://github.com/uwmisl/storage-biasing-ncomms20).


