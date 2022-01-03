## 신용카드 사용자 연체 여부 예측
***

<img width="643" alt="스크린샷 2021-07-29 22 54 07" src="https://user-images.githubusercontent.com/49870977/127504487-01113b91-d519-4114-ba2c-5070115df15d.png">

#### Evaluation : LogLoss

#### Learder Board : 275 / 714(Top 38.5%)

### How To
- LGBM, XGBoost, Catboost 앙상블을 시도함.
- 최대한 중복 데이터를 삭제하지 않고 진행하고자 함.

#### Review
- 상위권 솔루션이 모두 CatBoost 단일 모델인 것이 약간 충격이었음
- 그나마 금융권(?)과 관련된 데이터를 다룰 수 있었던 대회
- 중복 행에 대한 처리와 고객 ID를 생성하는 아이디어가 부족했다.
