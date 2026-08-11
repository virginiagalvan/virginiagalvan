# Virginia Galván

Data Scientist · PhD in Biological Sciences

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=flat)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-E97627?style=flat&logo=jupyter&logoColor=white)
![Statistical Modeling](https://img.shields.io/badge/Statistical_Modeling-4EACD1?style=flat)
![Bioinformatics](https://img.shields.io/badge/Bioinformatics-0F6E56?style=flat)

---

## About

Data scientist with a PhD in Biological Sciences, applying statistical modeling and machine learning to biological and clinical data. Experience spans end-to-end ML pipelines — from data acquisition and SQL-based cohort assembly to model development, interpretability, and deployment — alongside computational biology work in metagenomics and microbial lipid metabolism. I combine rigorous scientific methodology with production-oriented engineering practices to build reliable tools from complex datasets.

---

## Portfolio projects

### [Predicting Breast Cancer Treatment Subtype from Gene Expression Data](https://github.com/virginiagalvan/breast-cancer-subtype-predictor) · [Live API](https://tcga-brca-subtype-classifier.onrender.com/docs)

Predicts which of 5 breast cancer subtypes (PAM50: Luminal A, Luminal B, HER2-enriched, Basal-like, Normal-like) a tumor has from gene expression — the subtype determines whether a patient receives hormone therapy, targeted therapy, or chemotherapy. Model correctly classifies 93% of patients in testing (F1-macro 0.86), and — without being told anything about cancer biology — independently identified the estrogen-receptor gene (ESR1) as its top predictive signal, the same gene oncologists already use to guide treatment. Built end-to-end on the public TCGA-BRCA cohort (cBioPortal API, 981 patients): SQL-based cohort assembly, model comparison (Logistic Regression, Random Forest, XGBoost), SHAP interpretability, deployed live via FastAPI + Docker.

`Python` `SQL` `scikit-learn` `XGBoost` `SHAP` `FastAPI` `Docker` `Jupyter`

---

### [WS/DGAT Biosynthetic Potential in Marine and Terrestrial Environments](https://github.com/virginiagalvan/wsdgat-biosynthetic-potential)

Computational metagenomics survey mining public sequence databases (IMG/M) — 13 local metagenomes, 101 global marine metagenomes, 227 terrestrial metagenomes, 50 paired Malaspina deep-ocean samples, and 18,392 bacterial genomes — for a target lipid-biosynthesis enzyme family (WS/DGAT, Pfam PF03007). End-to-end pipeline: gene/domain identification, taxonomic assignment (BLASTp + MEGAN6), phylogenetics (MEGA-X), relative-abundance normalization against ribosomal marker genes, and statistical testing (Mann-Whitney U, Wilcoxon signed-rank, Spearman correlation) in Python. 7 notebooks, fully reproducible, tied to a peer-reviewed publication (PLOS ONE, 2023).

`Python` `pandas` `scipy` `Biopython` `geopandas` `Jupyter`

---

## Selected publications

- **High wax ester and triacylglycerol biosynthesis potential in coastal sediments of Antarctic and Subantarctic environments** · *PLOS ONE, 2023* · [10.1371/journal.pone.0288509](https://doi.org/10.1371/journal.pone.0288509)
  Galván V, Pascutti F, Sandoval NE, Lanfranconi MP, Lozada M, Arabolaza AL, Mac Cormack WP, Alvarez HM, Gramajo HC, & Dionisi HM

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/virgina-galvan-390ba233b/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/virginiagalvan)
[![Email](https://img.shields.io/badge/Email-virginiagalvan13@gmail.com-181717?style=flat&logo=gmail&logoColor=white)](mailto:virginiagalvan13@gmail.com)
