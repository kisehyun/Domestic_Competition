<img width="951" alt="스크린샷 2021-10-19 11 17 02" src="https://user-images.githubusercontent.com/49870977/137832696-d87f6832-75fc-47d9-b9ea-c7a5982ddf13.png">


### Evaluation : MAE(Mean Absolute Error)

### Model Selection
- KFold
- LeaveOneOut


#### < Leader Board >

- 2021/10/19 = 0.21161
- 2021/10/20 = 0.17558
- 2021/10/21 = 0.17551
- 2021/10/26 = 0.17498

#### 방법론
- species에 대해 target encoding(mean) 적용
- sepal length, petal length에 대해 각각 cos, sin 적용 변수 추가 
- 파생변수 없이 species에 대해 원-핫 인코딩만 추가해서 제출한게 현재 best(10/26기준)
