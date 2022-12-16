# openSW-TripleH

### Description
주제 : K패션 데이터 학습 및 환경 구축
- KyonggiUniv OpenSW Class 최종 프로젝트 (Team TripleH)
- mmdetection을 이용한 K패션 모델 학습
### dataset 구성
|category_id|category name|All|train/val|
|--|--|--|--|
|0|coat|600|480 / 120|
|1|jacket|600|480 / 120|
|2|jumper|482|386 / 96|
|3|cardigan|486|390 / 96|
|4|blouse|576|460 / 116|
|5|t-shirt|566| 450 / 116|
|6|sweater|371| 296 / 75|
|7|shirt|366| 290 / 76 |
|8|onepiece (dress)|1076| 860 / 216|
|9|jumpshuit|55| 44 / 11|
|10|pants|337|270 / 67 |
|11|skirt|411|328 / 83|

### 가상환경 구성
- anaconda 환경 사용
- python : 3.8.15
- torch : 1.6.0+cu101
- CUDA : 10, cudnn : 7.6.5

### usage
```
    git clone https://github.com/Jjanghyo/openSW-TripleH.git
```
### Team
#### 김정효
- 데이터셋 정리 및 train 수행
#### 박소현
- 클래스 분류
- PPT 제작 및 보고서 작성
#### 노승하
- 데이터셋 정리 및 test 수행