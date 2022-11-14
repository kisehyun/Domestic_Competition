### Public : 3 / 712 & Private : 2 / 712(score : 3.0859)


< How To >
1. 파생 변수 생성에 주력
- 공공 데이터 활용
- 위경도 좌표를 최대한 활용
- 제주도, 한라산까지의 거리 활용
- seasonality를 위해 7월, 8월만 여름으로 지정

2. optuna를 활용한 튜닝
- LGBM, XGBoost는 gpu를 활용해 튜닝
- CatBoost는 별도로 튜닝x

3. 데이터를 다르게 구성하여 모델링
- lane_count 값을 기준으로 모델링 진행 -> 1, 2, 3 차선 따로 모델링

< Lesson Learned >
- feature engineering is better than other things....!
- 튜닝도 성능 향상에 큰 영향을 줄 수 있다...
- 파이토치로 NN 짜서 해보고 싶었지만 역량 부족....
- 학습 시간 단축을 위해 GPU 활용은 필수!
