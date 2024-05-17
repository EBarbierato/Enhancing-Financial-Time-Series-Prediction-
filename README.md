# Enhancing-Financial-Time-Series-Prediction-
Enhancing Financial Time Series Prediction with Quantum-Enhanced Synthetic Data Generation: A Case Study on the S\P 500 Using QWGAN-GP

# Quantum Generative Adversarial Network (Quantum GAN) Procedures

## Overview
This repository contains Quantum GAN procedures for running simulations and analyses on SP500 and Brazil stock market data, as well as implementing an LSTM model.

## Table of Contents
- [Quantum GAN Procedures](#quantum-gan-procedures)
  - [Data Simulation](#data-simulation)
  - [Data Analysis](#data-analysis)
  - [LSTM Model Setup](#lstm-model-setup)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
  - [Data Simulation](#data-simulation-1)
  - [Data Analysis](#data-analysis-1)
  - [LSTM Model](#lstm-model)
- [Contributing](#contributing)
- [License](#license)

## Quantum GAN Procedures

### Data Simulation

#### SP500
1. Place `sp500.csv` and `QGAN_FINALE.ipynb` in the same directory.
2. Execute `QGAN_FINALE.ipynb` to generate `fake_original_FINALE.csv`.

#### Brazil
1. Place `^BVSP.csv` and `QGAN_BR.ipynb` in the same directory.
2. Run `QGAN_BR.ipynb` to produce `fake_original_BRAZIL.csv`.

### Data Analysis

#### SP500
- Execute scripts comparing `fake_original_FINALE.csv`, `sp500.csv`, and `original_log.csv`.

#### Brazil
- Run scripts that compare `fake_original_BRAZIL.csv`, `^BVSP.csv`, and `original_log_br.csv`.

### LSTM Model Setup

#### SP500
- Ensure `FEATURE.ipynb`, `oversampling.ipynb`, and `SOLO_ORIGINALE.ipynb` are in the same directory as `fake_original_FINALE.csv` and `original_log.csv`.

#### Brazil
- Ensure `FEATURE.ipynb`, `oversampling.ipynb`, and `SOLO_ORIGINALE.ipynb` are in the same folder as `fake_original_BRAZIL.csv` and `original_log_br.csv`.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required Python libraries as listed in `requirements.txt`

### Installation
Clone the repository and install the required Python libraries:
```bash
git clone [repository-url]
cd [repository-name]
pip install -r requirements.txt

