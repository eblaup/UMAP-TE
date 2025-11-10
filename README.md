# **Evaluation of Uniform Manifold Approximation and Projection for dimensionality reduction for large geochemical datasets relevant to magmatic ore-fertility, petrologic classification, and provenance**
<img align="right" width="304" height="821" alt="Fig_1" src="https://github.com/user-attachments/assets/a5a092b1-2124-47c7-ba72-80731f54f716" />


## Instructions
This repository contains jupyter notebooks that can be downloaded and run on the users computer. After downloading, users will need to update the directories in the code and then follow the instructions within the notebooks. 
Users can also transform their own datasets using the Zircon Fertility UMAP script and saved UMAP model by inputting their datasets provided they are in the same format (same columns). 

The user needs to install Python 3.12.4 and all the libraries listed in "package_list.txt" to reproduce the Conda environment. The same version of Python is required to read the scaler/model files (*.sav) provided.

## Contents
This repository contains scripts used to project mineral trace element geochemical data using UMAP. Commented instructions can be found within the linked jupyter notebooks The manuscript and code uses existing literature compilations of apatite and zircon geochemistry from Carrasco-Godoy et al., 2024 (https://doi.org/10.5382/econgeo.5086) and references therein; Nathwani et al., 2024 (https://doi.org/10.1038/s41467-024-52786-5), Castellanos-Melendez et al., 2024 (https://doi.org/10.1016/j.epsl.2024.119053), O'Sullivan et al., 2020, downloaded from their PANGAEA repository (https://doi.org/10.1594/PANGAEA.906570), and a GeoROC precompiled apatite file (2024-12-01, doi:10.25625/SGFTFN).

* The folder labelled Zircon Fertility contains the script, data, and UMAP model used to project zircon geochemistry using Eu/Eu*, λ3, P, Dy/Yb, λ2, Ce/Nd, Eu, Tb, Gd, and Gd/Yb. This transform is also used to project the Nathwani et al., 2024 dataset and the Castellanos-Melendez et al., 2024 dataset into UMAP-PCD space.

* The folder labelled Zircon Geochemistry contains the script, data, and UMAP model used to project zircon geochemistry using P, Ce, Eu, Th, La, Pr, Y, Nd, Gd, Er, Yb, Sm, Dy, and Lu.

* The folder labelled Yerington contains the scripts and data used to construct the Yerington district figures.

* The apatite folder contains the script and dataset used to project the apatite data of O'Sullivan et al., 2020 along with the GeoROC apatite. 


