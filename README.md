# Dacon_distribution_PJ

### 데이콘 물류 유통량 예측 경진대회

- 사용모델 : light GBM
(RMSE: Public - 5.9492552829, Private - 5.6387866466)	

- 후보모델: 
1) Voting(pycaret (GBR, lightGBM, catboost) - RMSE  6.3284
2) Stacking (GBR, lightGBM, catboost, xgboost, Bagging, extratree, RandomForest) - RMSE 6.498361063421981
