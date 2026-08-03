# Virginia Galván

Data Scientist · PhD in Biological Sciences · Argentina

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![English](https://img.shields.io/badge/English-C1_Cambridge-1D9E75?style=flat)
![Spanish](https://img.shields.io/badge/Spanish-Native-993C1D?style=flat)

---

## About

Data scientist with a PhD in Biological Sciences, applying statistical modeling and machine learning to biological and clinical data. Experience spans end-to-end ML pipelines — from data acquisition and SQL-based cohort assembly to model development, interpretability, and deployment — alongside computational biology work in metagenomics and microbial lipid metabolism. I combine rigorous scientific methodology with production-oriented engineering practices to build reliable tools from complex datasets.

---

## Tech stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-006ACC?style=flat)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-E97627?style=flat&logo=jupyter&logoColor=white)
![Statistical Modeling](https://img.shields.io/badge/Statistical_Modeling-4EACD1?style=flat)
![Bioinformatics](https://img.shields.io/badge/Bioinformatics-0F6E56?style=flat)

---

## Selected publications

- **Exploring the versatility of fatty acid biosynthesis in *Escherichia coli*: Production of random methyl branched fatty acids** · *Metabolic Engineering, 2025* · [10.1016/j.ymben.2025.03.005](https://doi.org/10.1016/j.ymben.2025.03.005)

- **High wax ester and triacylglycerol biosynthesis potential in coastal sediments of Antarctic and Subantarctic environments** · *PLOS ONE, 2023* · [10.1371/journal.pone.0288509](https://doi.org/10.1371/journal.pone.0288509)
  Galván V, Pascutti F, Sandoval NE, Lanfranconi MP, Lozada M, Arabolaza AL, Mac Cormack WP, Alvarez HM, Gramajo HC, & Dionisi HM

- **Modification of PapA5 acyltransferase substrate selectivity for optimization of short-chain alcohol-derived multimethyl-branched ester production in *Escherichia coli*** · *Applied Microbiology and Biotechnology, 2020* · [10.1007/s00253-020-10872-w](https://doi.org/10.1007/s00253-020-10872-w)
  Roulet J, Galván V, Lara J, Salazar MO, Cholich V, Gramajo H, & Arabolaza A.

- **Analysis of urinary organic acid levels in early childhood and newborns: a gas chromatography-mass spectrometry study with evaluation of reference ranges**
  Saavedra DD, Hourcade ME, Alvarez CE, Wiggenhauser J, Galván V, Gatti M, Cabrera A, & Müller GL

---

## Portfolio projects

### [TCGA-BRCA Molecular Subtype Classifier](https://github.com/virginiagalvan/tcga-brca-subtype-classifier) · [Live API](https://tcga-brca-subtype-classifier.onrender.com/docs)

End-to-end, production-shaped ML pipeline predicting PAM50 breast cancer molecular subtype (Luminal A/B, HER2-enriched, Basal-like) from gene expression, using the public TCGA-BRCA cohort (cBioPortal API, 981 patients). Data loaded into a SQL database for cohort/feature-set assembly; Logistic Regression, Random Forest, and XGBoost compared via cross-validation (XGBoost best: 93% test accuracy); SHAP interpretability cross-checked against known breast-cancer biology (ESR1, ERBB2, MKI67); trained model served through a FastAPI endpoint, containerized with Docker, and deployed live on Render.

`Python` `SQL` `scikit-learn` `XGBoost` `SHAP` `FastAPI` `Docker` `Jupyter`

---

### [WS/DGAT Biosynthetic Potential in Marine and Terrestrial Environments](https://github.com/virginiagalvan/wsdgat-biosynthetic-potential)

Computational metagenomics survey mining public sequence databases (IMG/M) — 13 local metagenomes, 101 global marine metagenomes, 227 terrestrial metagenomes, 50 paired Malaspina deep-ocean samples, and 18,392 bacterial genomes — for a target lipid-biosynthesis enzyme family (WS/DGAT, Pfam PF03007). End-to-end pipeline: gene/domain identification, taxonomic assignment (BLASTp + MEGAN6), phylogenetics (MEGA-X), relative-abundance normalization against ribosomal marker genes, and statistical testing (Mann-Whitney U, Wilcoxon signed-rank, Spearman correlation) in Python. 7 notebooks, fully reproducible, tied to a peer-reviewed publication (PLOS ONE, 2023).

`Python` `pandas` `scipy` `Biopython` `geopandas` `Jupyter`

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/virgina-galvan-390ba233b/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/virginiagalvan)
[![Email](https://img.shields.io/badge/Email-virginiagalvan13@gmail.com-181717?style=flat&logo=gmail&logoColor=white)](mailto:virginiagalvan13@gmail.com)


