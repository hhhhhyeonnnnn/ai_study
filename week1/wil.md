새로운 데이터
new_fish = [ [30, 600], [12, 10], [25, 150] ]

그래프를 통해 눈으로 판단한 결과
new_fish[0] : 도미
new_fish[1] : 방어
new_fish[2] : 도미

KNN 모델의 예측 결과(kn.predict)
new_fish[0] : 1 (도미)
new_fish[1] : 0 (방어)
new_fish[2] : 0 (방어)

그래프를 통해 눈으로 판단한 결과와 KNN 모델의 예측 결과 비교
new_fish[0] : 일치
new_fish[1] : 일치
new_fish[2] : 불일치

배운점
- 데이터 시각화
import matplotlib.pyplot as plt
plt.scatter()
plt.xlabel()
plt.ylabel()
plt.show()

- knn 분류기(주변에 있는 데이터들을 보고 어떤 종류인지 분류하는 모델)
from sklearn.neighbors import KNeighborsClassifier
kn = KNeighborsClassifier()

- 모델 훈련
kn.fit()

- 모델 성능
kn.score()

- 데이터 예측
kn.predict()