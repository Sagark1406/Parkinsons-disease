# Parkinson's Disease Prediction

## Overview
This project predicts the presence of Parkinson's disease using biomedical voice measurements. 
It uses the UCI Parkinson's Disease Detection dataset, which contains acoustic features extracted 
from sustained vowel phonations recorded from both healthy individuals and Parkinson's patients.

## Features
- Data preprocessing (handling class imbalance, normalization)
- Feature engineering on voice/acoustic biomarkers (jitter, shimmer, HNR, nonlinear dynamics)
- SVM-based classification model
- Achieved 88.46% accuracy on the classification task

## Dataset
The dataset consists of biomedical voice measurements including:
- **Frequency variation (Jitter)**: MDVP:Jitter(%), MDVP:RAP, MDVP:PPQ, Jitter:DDP
- **Amplitude variation (Shimmer)**: MDVP:Shimmer, Shimmer:APQ3, Shimmer:APQ5, MDVP:APQ
- **Noise measures**: NHR, HNR
- **Nonlinear dynamical complexity measures**: RPDE, D2, DFA, spread1, spread2, PPE

## Tech Stack
- Python
- Pandas, NumPy, Scikit-learn

## How to Run
1. Install dependencies
2. Run the notebook/script

## Author
Sagar Kumar
