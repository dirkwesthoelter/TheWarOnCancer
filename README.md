# TheWarOnCancer
Results of ML project "The War on Cancer"/ RWTH Aachen  
[![Python 3.11+](https://img.shields.io/badge/Python-%E2%89%A53.11-blue.svg)](https://www.python.org/downloads/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebooks-orange.svg)](https://jupyter.org/)

## Overview
This project focuses on the development of predictive models for estrogen receptor (ER) status and relapse using gene expression data in combination with corresponding clinical metadata from a cohort of patients with breast (mammary) carcinoma. Principal component analysis and clustering analyses of gene expression data from patients with breast (mammary) carcinoma revealed the presence of two distinct molecular subtypes. However, using gene expression data alone, it was not possible to develop high-quality predictive models for the available staging parameters (histological grade, lymph node status, and tumor size) or for the clinical outcome relapse. 

> Gene expression data:
> Clincal data:
> Jupyter notebook with code: 

## Project Structure

```This project repository contains raw data (gene expression and clinical data), notebook with code and a report with key results.
.
├── data/              # Two raw data csv files
├── notebooks/         # Jupyter notebooks for exploration, training, analysis
├── results/           # Generated outputs (figures, tables, metrics, models) and interpretation in form of a report.
└── README.md
