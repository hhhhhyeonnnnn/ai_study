배운점
- train_test_split()을 사용하면 데이터를 훈련 세트와 테스트 세트로 쉽게 나눌 수 있다.

- test_size를 사용하면 원하는 비율로 데이터를 분리할 수 있다.
ex) test_size=0.3 -> 7:3
    test_size=0.5 -> 5:5
    test_size=0.1 -> 9:1

- len()을 사용하면 훈련 세트와 테스트 세트의 샘플 개수를 확인할 수 있다.

- random_state를 설정하면 실행할 때마다 같은 결과로 데이터를 분리할 수 있다.

- stratify를 사용하면 훈련 세트와 테스트 세트에 클래스 비율이 비슷하게 유지되도록 나눌 수 있다.

- knn 분류기
from sklearn.neighbors import KNeighborsClassifier
kn = KNeighborsClassifier()

- 모델 훈련
kn.fit()

- 모델 성능
kn.score()

- 데이터 예측
kn.predict()