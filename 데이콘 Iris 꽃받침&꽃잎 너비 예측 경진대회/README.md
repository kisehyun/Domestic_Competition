<img width="1198" alt="스크린샷 2021-10-31 13 18 26" src="https://user-images.githubusercontent.com/49870977/139567417-ee7e3fdf-0014-46ed-8f0d-0a05ea06b8b1.png">

### Evaluation : MAE(Mean Absolute Error)

### Model Selection
- KFold(15Fold)
- LeaveOneOut

#### < Leader Board >

- 2021/10/19 = 0.21161
- 2021/10/20 = 0.17558
- 2021/10/21 = 0.17551
- 2021/10/26 = 0.17498
- 2021/10/27 = 0.17382
- 2021/10/29 = 0.17208

#### How To
- species에 대해 target encoding(mean) 적용
- sepal length, petal length에 대해 각각 cos, sin 적용 변수 추가 
- 파생변수 없이 species에 대해 원-핫 인코딩만 추가
- 15FOLD Ensemble(4models + one-hot encoding)
- DNN + 4models Ensemble -> 0.17208(best)


#### Result

- Private Score : 0.17286(13th)

#### Review
- 데이터가 75개로 매우 적어 이를 적절히 활용한 파생변수 생성이 어려웠다.
- 혹여 파생변수를 만든다 하더라도 과적합 발생 리스크가 있어 일반화된 모델 구성이 핵심이었던 것 같다.
- 일반적인 ML에서 좋은 성능을 보이는 Boosting 계열이 해당 대회에서는 좋은 성능을 보장해주지는 못했다.
- 하지만 재미있었다.
