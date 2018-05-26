
# House Prices: Advanced Regression Techniques

Predict sales prices and practice feature engineering, RFs, and gradient boosting

## Overview

### Description

아이오와 주 Ames에 있는 주거용 주택을 설명하는 79 가지 변수로 각 주택의 최종 가격을 예측합니다.



### Evaluation

Root-Mean-Squared-Error (RMSE)
- [RMSE](https://en.wikipedia.org/wiki/Root-mean-square_deviation)


예측된 값과 실제 판매 가격의 잔차제곱합

## Data

### Data set

- train data size  : (1460, 81) 

- test data size : (1459, 80) 

### Data fields
- https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

## Modeling

회귀모델링

### 1. EDA

- 변수 시각화 
- numeric Data EDA
- category Data EDA


### 2. Data Engineering

- 종속변수 로그변환
- missing data 확인
- LabelEncoder
- 변수 중요도 확인 (상관계수, F-test)
- 다중공선성 확인 (variance_inflation_factor)
- 아웃라이어 제거 (레버리지, cooks_distance)


### 3. Modeling

- sklearn
  - Lasso
  - ElasticNet
  - KernelRidge
  - GradientBoostingRegressor
  - XGBRegressor
  - LGBMRegressor

- statsmodel
  - OLS
  - 다항회귀

- best model 
  - GradientBoostingRegressor
  
### 4. Submission
- Final Score : 0.11946
- Leaderboard : 784 / 5414 (15%)
