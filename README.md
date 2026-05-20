# ttds_assignment

## Technical Implementation & Code Details

The codebase contains a complete, robust machine learning pipeline in `ttds_assignment.ipynb` built using `scikit-learn` and `pandas`.
It is designed to dynamically handle environment dataset schemas and perform hyperparameter optimization under rigorous statistical constraints.

### Architectural Pipeline Flow
The code automatically builds a reproducible preprocessing and modeling pipeline utilizing `sklearn.pipeline.Pipeline` and `sklearn.compose.ColumnTransformer`.
This prevents data leakage during cross-validation loops.
