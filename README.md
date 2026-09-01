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

Data scientist with a PhD in Biological Sciences. A bioinformatics background introduced me to working with large-scale, complex datasets to solve biological problems; today I apply statistical modeling and machine learning to diverse types of complex data — building end-to-end ML pipelines, from data acquisition and model development to interpretability and deployment (APIs, containerization).

---

## Portfolio projects

### [ML-Based Prediction of Breast Cancer Treatment Subtype from Gene Expression Data](https://github.com/virginiagalvan/breast-cancer-subtype-predictor) · [Live API](https://tcga-brca-subtype-classifier.onrender.com/docs)

Built and deployed a supervised ML classifier (Logistic Regression, Random Forest, XGBoost — compared via cross-validation) that predicts breast cancer subtype from gene expression data, reaching 93% accuracy on 981 patients (TCGA-BRCA). Full pipeline: SQL-based cohort assembly, model selection, SHAP interpretability, and a live REST API (FastAPI + Docker). The model's top predictive feature — found automatically, with no domain input — was ESR1 (estrogen receptor), the same gene oncologists use to guide treatment.

`Python` `SQL` `scikit-learn` `XGBoost` `SHAP` `FastAPI` `Docker` `Jupyter`

---

### [Biocatalyst Candidate Clustering: Prioritizing Enzyme Candidates with Unsupervised Learning](https://github.com/virginiagalvan/clustering-for-industrial-biocatalyst-discovery)

Framed a real bottleneck in industrial biocatalyst discovery — deciding which enzyme candidates are worth testing experimentally — as an unsupervised learning problem. Used K-means and hierarchical clustering (independently corroborating each other) to group ~2,200 candidates across 5 evaluation criteria, then translated the clusters into an actual ranked shortlist: composite scoring within the strongest cluster, deliberate inclusion of a calculated-risk group instead of only "safe" picks, and a rare co-membership signal used as an explicit tie-breaker.

`Python` `scikit-learn` `pandas` `SciPy` `Jupyter`

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
