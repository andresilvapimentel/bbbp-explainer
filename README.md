# BBBP Explainer
<img src="emoji brain.jpg" alt="drawing" width="200"/>

[![DOI](https://zenodo.org/badge/10920029.svg)](https://zenodo.org/badge/latestdoi/10920029)

BBBP Explainer is a code to generate structural alerts using Local Interpretable Model-Agnostic Explanations (LIME) of machine learning models from the BBBP dataset.
BBBP Explainer means Blood-Brain Barrier Explainer.

The BBBP Explainer framework is highly versatile (coded in Google Colab), with options that can be further developed and optimized by the users: it can accept any user-defined datasets (or datasets available in MoleculeNet repository), can use different fingerprints, data splitters, cross-validation methods, and any classification model from DeepChem library.

There are two codes to analyze the data generated from BBBP Explainer: BBBP(0)_explainer.ipynb and BBBP(1)_explainer.ipynb
1) BBBP(0)_explainer.ipynb explains the fragments importants of non-penetrating BBB drugs; and
2) BBBP(1)_explainer.ipynb explains the fragments importants of penetrating BBB drugs.

The BBBP dataset is provided from the MoleculeNet and DeepChem libraries. It is upload using DeepChem tools. DeepChem tools may also be used to upload any dataset in MoleculeNet or user-defined dataset. However, the BBBP dataset was curated removing duplicate and triplicate compounds, unifying compounds with two lables, and fixing smiles with RDKit issues. The BBBP dataset was cross-validated to get the most robust models.

The BBBP explainer was used with three classifiers: MultiTask, ExtraTrees, and Random Forest. And, these models were analyzed with different metrics (precision, accuracy, recall, and F1 scores) and with the confusion matrix. The models were optimized using hyperparameterization approach to get the best hyper parameters from each model and output the best results.

# Installation instructions

BBBP Explainer is 100% compatible with Google Colab platform developed in Microsoft Windows using Python version 3.8.

BBBP Explainer has the following dependencies: Lime, RDkit, DeepChem, Pandas, Matplotlib, sklearn, mols2grid, IPython and XlsxWriter.

<img src="emoji brain.gif" alt="drawing" width="200"/>

# Documentation

The complete documentation about how to run the BBBP Explainer protocol and several tutorials is being developed.

# Get help

BBBP Explainer is being actively developed and some issues may arise or you may need extra help to run BBBP Explainer. In those cases, there are two main ways to get help:

1) Open a new issue in this repository
Or 
2) write an email to André Silva Pimentel (a_pimentel@puc-rio.br) (I will do my best to answer your questions as soon as possible).

# License

BBBP Explainer is available under MIT License. See license document for more details. URL and DOI: https://github.com/andresilvapimentel/bbbp-explainer (https://doi.org/10.5281/zenodo.10920029)

# Contributors

This code was written under collaboration:
Cayque Monteiro Castro Nascimento (PhD student), Lucca Caiaffa Santos Rosa (Undergraduate student) and Caio Oliveira Argolo (Undergraduate student), who performed the analysis and part of the code under my guiding as advisor, Andre Silva Pimentel, who wrote most of the code with Lucca Caiaffa Santos Rosa.
