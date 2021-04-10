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

## 4. XGBoost를 활용한 방법을 구현해봤지만 학습이 너무 오래걸려 결과를 확인하지 못했습니다. 


