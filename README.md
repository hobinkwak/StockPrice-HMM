# StockPrice-HMM

## [Paper] Stock Price Prediction with HMM

이 ipynb파일은 아래의 논문

**Stock Market Forecasting Using Hidden Markov Model: A new Approach - MR Hassan(2005)**
**Stock Price Prediction using Hidden Markov Model - Nguyet Nguyen(2016)**

에서 소개된 방법론을 기반으로 하였음

데이터 : 2007년부터 현재(2021.8.14)까지의 코스피 200지수 데이터
- BIC를 근거로 Hiden State의 갯수를 선택
- TestSet에 대해 주가의 상승/하락의 움직임 방향을 예측하는 방식으로 Accuray를 측정


## States of Stock Return

위와 동일한 데이터의 주간수익률(Log)의 히든상태 추론
- 히든상태의 Sequence 시각화
- 히든상태의 확률분포 시각화
