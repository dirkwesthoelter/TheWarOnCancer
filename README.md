# TheWarOnCancer
Results of ML project "The War on Cancer"/ RWTH Aachen  
[![Python 3.11+](https://img.shields.io/badge/Python-%E2%89%A53.11-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg)](https://jupyter.org/)

## Overview
This project focuses on the development of predictive models for estrogen receptor (ER) status and relapse using gene expression data in combination with corresponding clinical metadata from a cohort of patients with breast (mammary) carcinoma. Principal component analysis and clustering analyses of gene expression data from patients with breast (mammary) carcinoma revealed the presence of two distinct molecular subtypes. However, using gene expression data alone, it was not possible to develop high-quality predictive models for the available staging parameters (histological grade, lymph node status, and tumor size) or for the clinical outcome relapse. The results are reproducible based on the raw data provided in this repository, the notebook with code and corresponding requirements to conduct the analyses.

> Gene expression data:  [gene_expression](data/mammacarcinoma_gex.csv)   
> Clincal data: [clinical data](data/mammacarcinoma_pat.csv)   
> Jupyter notebook with code: [notebook](notebooks/project.ipynb)   
> Results and interpretation: [results-pdf](results/Report_DW.pdf)

## Project Structure

This project repository contains raw data (gene expression and clinical data), notebook with code and a report with key results.
.
```text
├── data/              # Two raw data csv files
├── notebooks/         # Jupyter notebooks for exploration, training, analysis
├── results/           # Generated outputs (figures, tables, metrics, models) and interpretation in form of a report (pdf/docx).
├── requirements       # Packages used for analyses
└── README.md
```

## Getting Started
### Prerequisites
- Analyses were performed using Python 3.11.9 in Visual Studio Code (v1.107.1) with a Jupyter Notebook kernel.

### Setup with pip
The following steps assume that the project has been downloaded or cloned locally
and that all commands are executed from the project root directory.

1. Create and activate a virtual environment:

```bash
python3.11 -m venv .venv
source .venv/bin/activate
```
2. Install dependencies
```bash
pip install --upgrade pip
pip install -r requirements.txt
```
