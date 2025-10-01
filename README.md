**Machine Learning Term Project – Fall 2024**

This group project was completed as part of the Machine Learning course at the University of Helsinki (Spring 2025 intake). The project focuses on predicting the saturation vapour pressure (pSat) of atmospherically relevant molecules using machine learning techniques.

**Dataset:**

We used the GeckoQ dataset, which contains atomic structures and thermodynamic properties for 31,637 molecules formed by the oxidation of α-pinene, toluene, and decane. The dataset is designed to support data-driven research in atmospheric science, particularly in the context of aerosol particle growth and new particle formation (NPF).

**Target Variable:**

log_pSat_Pa: The logarithmic saturation vapour pressure, a measure of a molecule’s ability to condense into the liquid phase. Molecules with low pSat (LVOCs) are particularly important for NPF research.

**Features:**

Interpretable molecular descriptors: molecular weight, number of atoms, functional groups, and other chemical properties.

Topographical fingerprints (TopFP): encoding the atomic structure of molecules for machine learning applications.

**Objective:**

Build a regression-based machine learning model to predict log_pSat_Pa from molecular features. The project involves:

Thorough data exploration and preprocessing

Feature selection and engineering

Model selection and performance evaluation

Critical analysis of model assumptions and results

**Key Notes:**

The task is non-linear regression, so simple linear models may not capture the complexity of the relationships.

The focus is on understanding and correctly applying machine learning methods, not on achieving the best performance compared to literature benchmarks.


**Team Members:**

Samara Senari Bowinnage

Gayani Anandagoda

Chen Yihao

**References:**

Besel et al., Scientific Data, 2023, DOI: <10.1038/s41597-023-02366-x>

Wang et al., PNAS, 2017, DOI: <10.1073/pnas.1707564114>




svm_model : saved svm model with eps-regression 

svm_modle_test : saved svm model without eps-regression

xgb_model : gradient Boosting model 
