#Linear Regression - Diabetes Disease Progression

This project uses linear regression to predict diabetes disease progression using the sklearn diabetes dataset.

#Dataset
- Source: sklearn.datasets.load_diabetes
- Features: 10 normalized clinical variables
- Target: Quantitative measure of disease progression one year after baseline

#Model
- LinearRegression from scikit-learn
- R² score: 0.47 ~ 0.5 (varies by seed)
- MSE: (reported)

#Visualization
![scatter](./images/actual_vs_pred.png)


주요 내용 (Korean Summary)

- 선형 회귀로 당뇨병 진행 점수 예측
- 시각화 통해 예측 정확도 확인
- sklearn 기본 데이터셋 + pandas/seaborn/matplotlib 사용
