<img width="1195" alt="스크린샷 2021-12-15 11 48 52" src="https://user-images.githubusercontent.com/49870977/146113940-e710762b-93c4-4a12-9c8f-21c5166532ba.png">


### Evaluation
- NMAE


## Review
- 평가 지표인 NMAE에 대한 이해가 제대로 선행 됐어야 했다..
- 데이터 수가 굉장히 적었기 때문에 LeaveOneOut 방식을 cross validation으로 사용함.
- 시계열 요소가 존재하지만 이를 변수에 반영하기에 어려움.
- 가장 basic한 모델을 찾아내고자 여러 시도를 해보았다.
- 기존에 ensemble 방식을 애용했는데 단순 Hold Out을 활용하는 방법이 이번 대회에서 효과가 있었음.
- feature combination을 활용한 변수선택 후 XGBoost 사용.
