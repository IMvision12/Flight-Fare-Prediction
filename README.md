# Flight-Fare-Prediction


|                 |     MAE    |      MSE      |    RMSE     |
|                 | ---------- | ------------- | ----------- |
|  Random Forest  |  1189.875  |  4101391.662  |   2025.189  |
|  TFDF           |   -        |  4263760.00   |   2064.89   |
|  Catboost       |  1159.825  |  3126290.854  |   1768.132  |


|              | Accuracy      |
| ------------- | ------------- |
| baseline(Naive Bayes)  | 79.265092  |
| simple_dense  | 78.740157  |
| lstm  | 77.821522	  |
| gru  | 77.690289	  |
| bidirectional  | 77.034121  |
| TF-HUB  | 80.839895  |
| TFDF + neural network | 74.015748  |
| TFDF + pre-trained embeddings  | 81.49606  |
