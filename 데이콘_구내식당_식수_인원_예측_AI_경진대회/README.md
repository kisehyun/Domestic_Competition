# 구내식당 식수 인원 예측 AI 경진대회

***


<img width="1218" alt="스크린샷 2021-07-29 09 22 05" src="https://user-images.githubusercontent.com/49870977/127412762-e7571a35-b030-4f30-a582-0a8b95ed4e38.png">


### - 주제 : 구내식당의 요일별 점심, 저녁 식사 인원 예측
### - 주최 / 주관 : LH / DACON
#### - 평가지표 : MAE(mean absolute error)
#### - Leader Board : private 13 / 481(Top 2.7%)

#### 리뷰)
- 학습 데이터가 1200여개로 모델 구성 및 검증에 한계가 있었음.
- 메뉴를 처리하기가 어려웠고 doc2vec, word2vec, cosine유사도 등 다양한 변수를 생성했지만 원-핫 인코딩 형태가 가장 성능이 뛰어났음.
- 최상위권 솔루션을 보니 상당히 심플하게 피처를 구성함 -> 파생 변수 생성에 집중할 필요가 없었다고 후회가 듬...
- 팀원들끼리 소위 "천하제일 과적합 방지 대회"라고 얘기할만큼 overfitting으로 leader board 차이가 극명하게 드러남.
