# bbbp-explainer
<img src="emoji brain.jpg" alt="drawing" width="200"/>

[![DOI](https://zenodo.org/badge/606507245.svg)](https://zenodo.org/badge/latestdoi/606507245)

BBBP Explainer is a code to generate structural alerts using Local Interpretable Model-Agnostic Explanations (LIME) and SHapley Additive exPlanations (SHAP) of machine learning models from the BBBP dataset.
BBBP Explainer means Blood-Brain Barrier Explainer.

The BBBP Explainer framework is highly versatile (coded in Google Colab), with options that can be further developed and optimized by the users: it can accept any user-defined datasets (or datasets available in MoleculeNet repository), can use different fingerprints, data splitters, cross-validation methods, and any classification model from DeepChem library.

There are two codes to analyze the data generated from BBBP Explainer: BBBP(0)_explainer.ipynb and BBBP(1)_explainer.ipynb
1) BBBP(0)_explainer.ipynb explains the fragments importants of non-penetrating BBB drugs; and
2) BBBP(1)_explainer.ipynb explains the fragments importants of penetrating BBB drugs.

The BBBP dataset is provided from the MoleculeNet and DeepChem libraries. It is upload using DeepChem tools. DeepChem tools may also be used to upload any dataset in MoleculeNet or user-defined dataset. 

# Installation instructions

BBBP Explainer is 100% compatible with Google Colab platform developed in Microsoft Windows using Python version 3.8.

BBBP Explainer has the following dependencies: Lime, SHAP, RDkit, DeepChem, Pandas, Matplotlib, sklearn, mols2grid, IPython and XlsxWriter.

<img src="emoji brain.gif" alt="drawing" width="200"/>

# Documentation

The complete documentation about how to run the BBBP Explainer protocol and several tutorials is being developed.

# Get help

BBBP Explainer is being actively developed and some issues may arise or you may need extra help to run BBBP Explainer. In those cases, there are two main ways to get help:

1) Open a new issue in this repository
Or 
2) write an email to André Silva Pimentel (a_pimentel@puc-rio.br) (I will do my best to answer your questions as soon as possible).

# License

BBBP Explainer is available under MIT License. See license document for more details. URL and DOI: https://github.com/andresilvapimentel/bbbp-explainer (https://doi.org/10.5281/zenodo.7677519)

# Contributors

This code was written under collaboration:
Cayque Monteiro Castro Nascimento (PhD student) and Caio Oliveira Argolo (Undergraduate student), who performed the analysis and part of the code under my guiding as advisor, Andre Silva Pimentel, who wrote most of the code.
