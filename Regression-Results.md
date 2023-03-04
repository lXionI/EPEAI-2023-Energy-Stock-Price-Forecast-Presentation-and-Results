# Regression Analysis

## Overall

| ML-Model | Model | Error | Uniper | Enel | EDF |
|:-:|:-:|:-:|:-:|:-:|:-:|
| GBRT | Stock | MSE | 0.1404 | 0.0195 | 0.0768 |
| | Stock + <br>Sentiment | MSE | 0.1410 | 0.0228 | 0.0719 |
| MLP| Stock | MSE | 0.1305 | 0.0151 | 0.0564|
|| Stock + <br> Sentiment | MSE| 0.1287 | 0.0179 | 0.0570 |
| LSTM| Stock | MSE | 0.1455 | 0.0468 | 0.0825 |
|| Stock + <br> Sentiment | MSE | 0.1422 | 0.0405 | 0.0770 |

## Uniper

| ML-Model | Model | MSE | RMSE | MAE |
| :------: | :---: | :-: | :--: | :-: |
| GBRT | Stock | 0.1404 | 0.3747 | 0.2892 |
| | Stock + <br> Sentiment | 0.1410 | 0.3756 | 0.2897 |
| MLP | Stock | 0.1305 | 0.3612 | 0.2751 |
|| Stock + <br> Sentiment | 0.1287 | 0.3586 | 0.2569 |
| LSTM | Stock | 0.1455 | 0.3814 | 0.2979 |
|| Stock + <br> Sentiment | 0.1422 | 0.3771 | 0.2851 |


## Enel

| ML-Model | Model | MSE | RMSE | MAE |
| :------: | :---: | :-: | :--: | :-: |
| GBRT | Stock | 0.0195 | 0.1398 | 0.1100 |
| | Stock + <br> Sentiment | 0.0228 | 0.1509 | 0.1152 |
| MLP | Stock | 0.0151 | 0.1229 | 0.0931 |
|| Stock + <br> Sentiment | 0.0179 | 0.1337 | 0.1017 |
| LSTM | Stock | 0.0468 | 0.2164 | 0.1743 |
|| Stock + <br> Sentiment | 0.0405 | 0.2013 | 0.1615 |

## EDF

| ML-Model | Model | MSE | RMSE | MAE |
| :------: | :---: | :-: | :--: | :-: |
| GBRT | Stock | 0.0768 | 0.2772 | 0.1979 |
| | Stock + <br> Sentiment | 0.0719 | 0.2682 | 0.1971 |
| MLP | Stock | 0.0564 | 0.2374 | 0.1725 |
|| Stock + <br> Sentiment | 0.0570 | 0.2387 | 0.1719 |
| LSTM | Stock | 0.0825 | 0.2872 | 0.2148 |
|| Stock + <br> Sentiment | 0.0770 | 0.2775 | 0.2108 |