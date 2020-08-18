# 위잉위잉

### 척척고졸 유튜브 채널

https://www.youtube.com/channel/UC0XPgTuvDU4gQIw48YLGhcw/

### 시현영상 링크

척척고졸-위잉위잉 시현영상 구현 : https://youtu.be/d-wYPHqA2jY

[TODO : model 생성]

- [x] 음성 데이터 수집 (기능1,2,3)
- [x] 데이터 전처리 및 이상치 제거
- [x] 피처 추출 및 데이터 가공
- [x] 입력데이터 처리 위한 모듈 생성
- [x] 모델 선정 및 학습 진행
- [x] 하이퍼 파라미터 조정
- [x] 정확도 향상을 위한 모델 재사용
- [x] 모델 저장


### 척척고졸 Organization

<https://github.com/chuckchuck-gojol>



### 프로젝트 레포지토리 정리

https://github.com/chuckchuck-gojol/model : 모델 생성

https://github.com/chuckchuck-gojol/wiing-wiing : 척척고졸 Dev repository

### 프로젝트의 목적

청각은 외부 위험을 가장 직관적으로 인식하는 중요한 감각중 하나이다.

그러나 최근 이어폰 사용자의 증가에 따라 평상시에 이어폰 밖 '주변소리'를 인지하지 못해 안전사고가 나는 경우도 증가하고 있다.

따라서 이번 위잉위잉 프로젝트를 통해 이어폰을 낀 상황에서 사용자들이 이어폰 밖 '주변소리'를 인지할 수 있도록, 주변 환경에서의 주요한 정보를 즉각적으로 전달받아 사고를 방지할 수 있는 방법을 제시한다.



### 시나리오 설계

1.  외부 마이크에서 주변 소리 녹음
2. 주변 소리 중 불필요 소음 제거 / 필요 소리 분류
3. 필요소리 분류 : 사용자를 향한 경적소리, 초인종 소리, 지하철 내 안내방송, 가전제품 알림음
4. 필요소리를 사용자에게 실시간으로 전달 (음성 / 화면)



### 프로젝트 예상 아키텍처

![wiingwiing](https://user-images.githubusercontent.com/26458200/69914444-d4b51880-1487-11ea-9a18-64b50f04b573.png)



### 구현 참고자료

- 휴대전화 이어폰 연결 checker 

  https://github.com/chuckchuck-gojol/Jihyun22-SaranshVatsa-Earphones-PluggedIn-Checker

- 안드로이드 안에 모델파일 넣어서 같이 빌드

  https://github.com/chuckchuck-gojol/mlkit-android

- 지정한 단어를 부를시 detection 하는 프로젝트

  <https://github.com/chuckchuck-gojol/snowboy>

  <https://github.com/chuckchuck-gojol/porcupine>

  https://github.com/chuckchuck-gojol/voice-speaker-tensorflow

- 음성 추출

  https://github.com/chuckchuck-gojol/voice-speaker-tensorflow

  https://github.com/chuckchuck-gojol/RNN_LSTM_TensorFlow

  https://github.com/chuckchuck-gojol/voice-speaker-tensorflow

- 소리분류

  https://github.com/chuckchuck-gojol/Soundclassifier_backend

  https://github.com/chuckchuck-gojol/KeywordSpotting
