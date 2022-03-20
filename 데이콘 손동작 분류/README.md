## Result

<img width="950" alt="스크린샷 2022-03-20 14 07 19" src="https://user-images.githubusercontent.com/49870977/159149068-04492a97-7b2a-42a6-bec1-7611439d5ebd.png">

#### Public : 33th / Private : 16th(Top 4.3%)

### How To :
- Tabular -> CNN(CV) 접근법 사용 -> 굉장히 유효했다. 대부분 ML 계열 접근은 PB 기준 0.84 ~ 0.85 정도였음.
- activation function, loss 등에서 다양한 실험을 해봄.
- train 데이터가 적었기 때문에 K-Fold 그리고 그 중에서 분류 문제였기에 StratifiedKFold를 사용함.

### Feedback
- 아이디어 측면에서 가장 훌륭한 대회였음.
- validation 활용이 정말 중요하다고 생각함 -> validation 점수오 LB 점수가 비슷하게 상승 하락함.
