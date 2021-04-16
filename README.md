# KeyPoint-Simple_ResNet & XGBoost

# DACON에서 모션 키포인트 검출 AI 경진대회의 데이터로 사용했습니다.

## 1. cv2를 활용하여 이미지 Augumentation(이미지 파일, KeyPoint파일)

## 2. ResNet으로 사전학습하여 특징 검출된 csv파일로 변환

## 3. 특징 검출된 csv 파일로 DataFrame형태로 학습진행
<ul> 
  <li>이방식대로한다면 빠르게 학습이 가능합니다.</li>
  <li> Bag of Tricks for Image Classification with Convolutional Neural Networks를 참고하여<br>
    이미지 학습이 아니지만 batchsize와 learning rate를 참고하여 학습모델을 만들었습니다.</li>
</ul>

## 4. 머신러닝으로 XGBoost를 활용한 방법을 구현 계획중 
#### 현재 작성한 코드는 예측 모델 생성 부분만 작성했습니다.
##### 결과가 안나올거라 예상되어 진행을 미루고 있습니다.

<ul> 
  <li>T-test로 회귀 분석</li>
  <li>변수 선정</li>
  <li>예측 모델 생성</li>
</ul>


