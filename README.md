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
pandas
numpy
matplotlib
networkx
optuna
scikit_learn
lightgbm
scipy
```

### Experimental Results

[experiment_results/model_exploration.csv](./experiment_results/model_exploration.csv) is the result of "Model Exploration" experiment.

[experiment_results/model_development.db](./experiment_results/model_development.db) is the Optuna study results of "Model Development" experiment.

## Final Probabilities Prediction

The final probabilities prediction can be found at:
* **Best Submission**: [./best_results/final_preds.csv](./best_results/final_preds.csv)
* **Second-Best Submission**: [./second_best_results/final_preds.csv](./second_best_results/final_preds.csv)

## Bibliography

Akiba, T., Sano, S., Yanase, T., Ohta, T., & Koyama, M. (2019). Optuna: A Next-generation Hyperparameter Optimization Framework. *Proceedings of the 25th {ACM} {SIGKDD} International Conference on Knowledge Discovery and Data Mining.*

Cambridge University Press & Assessment. (n.d.). *fraudulent*. Cambridge Dictionary. https://dictionary.cambridge.org/dictionary/english/fraudulent 

Guolin, K., Yu, S., Lamb, J., Morales, J., Borchert, O., & Mayer, M. (2026, March). *LightGBM*. GitHub. https://github.com/lightgbm-org/LightGBM 

Narkhede, S. (2018, June 26). *Understanding AUC - ROC Curve*. TDS Archive. https://medium.com/data-science/understanding-auc-roc-curve-68b2303cc9c5 

scikit-learn developers. (n.d.). *Classifier comparison*. https://scikit-learn.org/stable/auto_examples/classification/plot_classifier_comparison.html 

The SciPy community. (n.d.). *skew*. https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.skew.html 