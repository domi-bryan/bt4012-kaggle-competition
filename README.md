# BT4012 Kaggle Competition

*By: Dominic Bryan (e1136829)*

Using LightGBM and graphical features to detect illicit Bitcoin transactions.

## File Directories

### Data file directory

Since the data files are too large to upload on GitHub, please put the `train.csv`, `test.csv`, and `txs_edgelist.csv`  under the [data](./data/) folder.

### Notebook submission

[e1136829.ipynb](./e1136829.ipynb) is the notebook submission.

### Requirements File

Requirements can be found in the [requirements.txt](./requirements.txt). List of external libraries used:

```
lightgbm
matplotlib
networkx
numpy
optuna
pandas
scikit_learn
scipy
```

### Experimental Results

[experiment_results/model_exploration.csv](./experiment_results/model_exploration.csv) is the result of "Model Exploration" experiment.

[experiment_results/model_development.db](./experiment_results/model_exploration.csv) is the Optuna study results of "Model Development" experiment.