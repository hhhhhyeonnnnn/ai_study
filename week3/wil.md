배운점
- PolynomialFeatures(degree=15)를 사용하면 특성이 매우 많이 늘어난다.

- 특성이 너무 많아지면 훈련 세트에 과하게 맞춰져 과적합이 발생할 수 있다.

- 과적합이 발생하면 train score는 매우 높게 나오지만 test score는 매우 낮아질 수 있다.

- LinearRegression()으로 다항 특성이 추가된 데이터를 학습할 수 있다.

- train score와 test score를 함께 비교하면 과적합 여부를 확인할 수 있다.

- StandardScaler를 사용하면 데이터의 스케일을 표준화할 수 있다.

- Ridge 규제를 사용하면 모델의 가중치를 줄여 과적합을 완화할 수 있다.

- 규제를 적용하면 train score는 조금 낮아질 수 있지만 test score가 높아져 일반화 성능이 좋아질 수 있다.

- sklearn은 설치 이름이 scikit-learn이고, import할 때는 sklearn으로 불러온다.