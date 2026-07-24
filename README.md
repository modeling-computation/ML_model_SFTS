# ML_model_SFTS
This repository contains the code used in the manuscript:

"Long-term projection of SFTS cases among older adults under climate change using machine learning"

## Repository structure

```
Data/
    Input datasets and Result files

hyperparameter_2/
    Trained model files

Revision_hyperparam_LR_RF_XGB.ipynb, Revision_hyperparam_DNN.ipynb, Revision_hyperparam_LSTM.ipynb
    Training and hyperparameter estimation

Revision_bootstrap.ipynb
    Bootstrap analysis for prediction intervals

Revision_Projection.ipynb
    Future projections under SSP climate scenarios

Revision_Figure.ipynb
    Generation of manuscript figures

Revision_Figure6.ipynb
    Additional figure generation
```

## Requirements

Python 3.12

Main packages

- numpy
- pandas
- scikit-learn
- xgboost
- torch
- pygam
- matplotlib
- scipy

## Workflow

The notebooks should be executed in the following order.

1. Revision_hyperparam_LR_RF_XGB.ipynb, Revision_hyperparam_DNN.ipynb, Revision_hyperparam_LSTM.ipynb
2. Revision_bootstrap.ipynb
3. Revision_Projection.ipynb
4. Revision_Figure.ipynb
5. Revision_Figure6.ipynb

## Data

Input datasets are provided in the `Data` folder.

## Notes

Random seeds were fixed to ensure reproducibility wherever applicable.
