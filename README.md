# ICU Survival

In this project, I trained models to predict in-hospital death. [See this link](https://physionet.org/challenge/2012/) for details.
The best model was a gradient-boosted classifier with a mean cross validation score of 0.37-0.38, beating the sample (SAPS-I) and random-predictor benchmarks.

## Installation
- [Make sure `conda` is installed](https://docs.conda.io/en/latest/miniconda.html).
- Create the local environment: `conda env create -f environment.yml`.
- Run `jupyter lab` and open `icu-survival.ipynb`.

