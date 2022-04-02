# Explaining Neural Models for Image Classification
## MTQ315 Seminar Course Project

Please see `presentation.pdf` and `report.pdf` for an introduction and further details.

To setup the environment use:
```
conda env create -f env.yaml
```

The code / experiments / results are available in jupyter notebooks of the form {METHOD}\_{DATASET}.ipynb, where METHOD is `shap`, `cf`, and `cfproto` for _SHAP explanations_, _simple counterfactuals_ and _prototype-guided counterfactuals_ respectively and {DATASET} is `mnist` and `fmnist` for _MNIST_ and _Fashion MNIST_ respectively.
