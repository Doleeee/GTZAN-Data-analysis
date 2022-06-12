# GTZAN-Data-analysis
* 음악 장르 분류 및 생성
<p>Kaggle의 audio data와 tabular data를 이용하여 프로젝트를 진행하였습니다.</p>
<p>audio data와 원본 tabular data는 <a href="https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification">여기</a>에서 다운로드할 수 있습니다.</p>
<p>프로젝트 진행 과정은 다음과 같습니다.</p>
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
* model
  * origin: knn.pkl
  * origin_pca30: sgd_pca30.pkl
  * 1d_pca30: knn_1d_pca30.pkl
  * 1d_vae2: rf_vae2.pkl(zip)

* 데이터 별 분류 성능(정확도 및 RMSE) 비교
![image](https://user-images.githubusercontent.com/86818579/173196035-783bc8dc-4036-4ac4-9d8d-9533a94db4e0.png)

