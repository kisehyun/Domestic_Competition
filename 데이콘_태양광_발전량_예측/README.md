# 태양광 발전량 예측 AI 경진대회

***
### Quantile Regression 문제

Main Task

- Pinball Loss 에 대한 이해

- Quantile Regression 에 대한 이해


## < Rank 변동 >

(2020.12.15) : 8.24974(public : 65th)

(2020.12.16) : 2.02953(public : 12th) - GradientBoostingRegressor + LGBMRegressor 앙상블

(2020.12.18) : 2.11087(public : 13th) - DNN 추가 앙상블

(2020.12.21) : submit 안함. - 파생변수 생성(계절, 일조시간, 온도 상승으로 인한 효율감소 여부 등)

(2020.12.25) : 2.01987(public : 24th) - 일조시간 변수 수정(test), 단순한 mean 앙상블

(2020.12.28) : 2.01497(public : 38th) - 변수 생성 및 앙상블 비중 조정, QuantReg는 버리기로함.

(2020.12.29) : 1.95749(public : 26th) - 일조시간 feature만 추가. 하루 뒤 예측 + 이틀 뒤 예측 데이터 각각 만들어 사용

(2020.12.30) : 1.90137(public : 18th) - 일조시간 feature + GHI feature
