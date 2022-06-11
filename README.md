# GTZAN-Data-analysis
* 원본 데이터(<a href="https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification">Kaggle</a>)<br>
Kaggle의 audio data와 tabular data를 이용하여 프로젝트를 진행하였습니다.<br>
audio data와 원본 tabular data는 위 링크에서 다운로드할 수 있습니다.<br>
프로젝트 진행 과정은 다음과 같습니다. 
![image](https://user-images.githubusercontent.com/86818579/173196463-f2d51a38-0baa-4c07-8052-965b170c135e.png)

* data
  * 원본 3초 데이터
  * PCA를 이용하여 30차원으로 축소한 원본 3초 데이터
  * PCA를 이용하여 30차원으로 축소한 원본 3초 1D 데이터
  * VAE를 이용하여 2차원으로 축소한 원본 3초 1D 데이터
* code
  * EDA
  * 데이터 전처리(결측치 제거 및 1D data 구축/차원 축소)
  * 분류모델 구축
  * 생성모델 구축
  * 최적 모델 4종 분류 성능 테스트

* 데이터 별 분류 성능(정확도 및 RMSE) 비교
![image](https://user-images.githubusercontent.com/86818579/173196035-783bc8dc-4036-4ac4-9d8d-9533a94db4e0.png)

