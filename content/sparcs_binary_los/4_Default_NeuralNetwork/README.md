# Summary of 4_Default_NeuralNetwork

[<< Go back](../README.md)


## Neural Network
- **n_jobs**: -1
- **dense_1_size**: 32
- **dense_2_size**: 16
- **learning_rate**: 0.05
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True
 - **stratify**: True

## Optimized metric
logloss

## Training time

16.0 seconds

## Metric details
|           |    score |     threshold |
|:----------|---------:|--------------:|
| logloss   | 0.453861 | nan           |
| auc       | 0.917328 | nan           |
| f1        | 0.861685 |   0.319626    |
| accuracy  | 0.842605 |   0.319626    |
| precision | 1        |   0.999434    |
| recall    | 1        |   7.34546e-53 |
| mcc       | 0.682302 |   0.486439    |


## Metric details with threshold from accuracy metric
|           |    score |   threshold |
|:----------|---------:|------------:|
| logloss   | 0.453861 |  nan        |
| auc       | 0.917328 |  nan        |
| f1        | 0.861685 |    0.319626 |
| accuracy  | 0.842605 |    0.319626 |
| precision | 0.836097 |    0.319626 |
| recall    | 0.888889 |    0.319626 |
| mcc       | 0.681215 |    0.319626 |


## Confusion matrix (at threshold=0.319626)
|                  |   Predicted as long |   Predicted as short |
|:-----------------|--------------------:|---------------------:|
| Labeled as long  |                1558 |                  425 |
| Labeled as short |                 271 |                 2168 |

## Learning curves
![Learning curves](learning_curves.png)

## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## Confusion Matrix

![Confusion Matrix](confusion_matrix.png)


## Normalized Confusion Matrix

![Normalized Confusion Matrix](confusion_matrix_normalized.png)


## ROC Curve

![ROC Curve](roc_curve.png)


## Kolmogorov-Smirnov Statistic

![Kolmogorov-Smirnov Statistic](ks_statistic.png)


## Precision-Recall Curve

![Precision-Recall Curve](precision_recall_curve.png)


## Calibration Curve

![Calibration Curve](calibration_curve_curve.png)


## Cumulative Gains Curve

![Cumulative Gains Curve](cumulative_gains_curve.png)


## Lift Curve

![Lift Curve](lift_curve.png)



[<< Go back](../README.md)
