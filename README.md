# 2020 DACON CUP (데이콘 사용자 행동 예측)
`🥉 2020 DACON CUP 3위` `#Python` `#Machine Learning` `#시계열`

- 대회 : [2020 DACON CUP](https://dacon.io/competitions/official/235683/overview/description, "Dacon Link")
- 데이콘 Google Analytics 데이터를 활용한 사용자 행동 예측
	- 사용자수, 세션수, 신규방문자수, 페이지뷰수 예측
	- 453팀 중 3위 수상

## 예측 수행 과정
1. python을 활용한 데이터 정제 
2. plotly를 활용한 분석 및 시각화로 인사이트 도출
3. 결과변수에 영향을 미칠 공휴일, 대회 개최일, 대회 유형 등의 변수에 대한 가설 수립 및 검증
4. prophet 시계열 모델의 교차검증을 수행하여 최적의 하이퍼파라미터 조합 도출 및 최종 예측 수행

## 결과 확인
[01. 추가 데이터 확인 및 전처리](https://nbviewer.org/gist/ssujeong/10b893d3e32df2650b994d5a6fb88562)      
[02. EDA](https://nbviewer.org/gist/ssujeong/2e75b886f605d1a997e4a8b423dbce45)      
[03_0. 가설검증(대회개수)](https://nbviewer.org/gist/ssujeong/f134c824da2783b6a0f168295cd685c1)      
[03_1. 가설검증(주말, 공휴일)](https://nbviewer.org/gist/ssujeong/f3ed76ddb6fad802ab7812700ef838c0)       
[03_2_1. 가설검증(대회특성_상금](https://nbviewer.org/gist/ssujeong/00f03fa954072ce040d3c6022137e88c)        
[03_2_2. 가설검증(대회특성_유형,주제](https://nbviewer.org/gist/ssujeong/37c1b5378b172281f44245941be1a6e9)       
[04. 모델링(prophet](https://nbviewer.org/gist/ssujeong/13b86912ec4ab5fc86407acabf7bf83b)