# MF_CNN
## Multi-fidelity Classification with CNN Model

This is the final research project of the Computational Statistics course of the Master's Degree in Mathematical Engineering at Politecnico di Milano. The team is composed of me and Melis Yılmaz. 

## Problem Description

The main goal of the project is to find a multi-fidelity classifier to efficiently determine the regions in the atria where arrhythmias can be induced in cardiac tissue.
In this work, we were inspired by a previous study* and we propose to use a Convolutional Neural Network Model instead of Multi-fidelity Gaussian Process Classification.

## Data

<img width="361" alt="image" src="https://github.com/hdtemurtas/MF_CNN/assets/114245127/9899e634-ffe5-496e-b782-a4fc0dfcdcbd"> 

Data is used from "https://github.com/fsahli/AtrialMFclass".
It is in .obj file format that represents the 3D geometry of a heart and then it is transformed into .npz files.


## References
*L. Gander, S. Pezzuto, A. Gharaviri, R. Krause, P. Perdikaris, F. Sahli. Fast characterization of inducible regions of atrial fibrillation models with multi-fidelity Gaussian process classification. Frontiers in Physiology (2022): doi:10.3389/fphys.2022.757159
