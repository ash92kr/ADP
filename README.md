## ADP 핵심 정리(목차)



- 본 핵심 정리는 ADP에서 자주 출제되는 내용 중 데이터 분석 전문가 가이드(개정판)에 없거나 부족한 부분 위주로 정리했습니다.

* 가이드의 1장,  3장,  5장 전부와  2장의 하둡과 맵리듀스를 제외한 내용은 가이드를 읽기 바랍니다.





#### 2장 데이터 처리 기술 중 하둡과 맵리듀스

​     

1. 개요
2. HDFS - 분산 데이터 저장 시스템
3. 맵리듀스 - 분산 데이터 처리 시스템
4. 하둡 에코 시스템 - Hive와 SQL on 하둡

​    

#### 4장 - 데이터 분석

  

1. R

> ① R의 데이터 타입과 데이터 구조
>
> ② R의 기본 명령어/함수
>
> ③ 데이터 전처리 - 데이터 구조 변경, 결측값 처리, 이상치 처리

​     

2. 통계

> ① 통계 기본 개념 - 척도/변수, 모집단과 표본, 표본추출법, 확률, 조건부 확률, 독립사건, 확률변수, 확률분포
>
> ② 기술통계 개요 - 평균, 분산, 표준편차, 상자그림
>
> ③ 추론통계 개요 - 점추정, 구간추정, 통계량과 p값, 가설검정, 귀무가설과 대립가설, 제1종/2종 오류
>
>
>
> ④ 카이제곱 검정
>
> ⑤ T-검정
>
> ⑥ 분산분석(ANOVA)
>
> ⑦ 상관분석 - 공분산, 상관관계와 인과관계의 차이, 상관행렬표 해석
>
> ⑧ 회귀분석 - 독립변수와 종속변수, 오차, 최소제곱추정법, 가정(선형성, 독립성, 등분산성, 비상관성, 정상성), 단회귀분석, 중회귀분석, 독립변수 선택방법, 비선형회귀, lasso 및 ridge 회귀법 + 과적합
>
> ⑨ 다차원척도법
>
> ⑩ 주성분 분석 - 스크리 그래프, 각 주성분의 상관관계 여부, 그림 해석
>
> ⑪ 시계열 예측 - 시계열 모형-AR, MA, ARIMA, 분해 시계열, 적합한 모형 선택

​     

→ ④ ~ ⑪의 경우 언제 분석법을 사용하는지? 실행 절차는?  결과표의 어떤 부분을 해석하는지 등이 포함됩니다.

​     

3. 데이터 마이닝

> ① 개요 - 분류예측, 군집의 개념, 절차(훈련 데이터와 검증 데이터), 과적합
>
> ​     
>
> ② 로지스틱 회귀분석 - 언제 사용해야 하는가?, 오즈와 오즈비, 해석법
>
> ③ 인공신경망 - 단층신경망=퍼셉트론, 다층신경망=오차의 역전파 알고리즘, 은닉층, 가중치(편의), 활성함수 등 개념 위주로 정리
>
> ④ 의사결정나무 - 그래프 해석, 모형평가(카이제곱 통계량, 지니지수, 엔트로피 지수)
>
> ⑤ 앙상블 모형 - 배깅, 부스팅, 랜덤포레스트, 교차검정 등
>
> ⑥ 모형 평가 - 홀드아웃, 교차검증(k-fold), 붓스트랩 등 방법론 위주로 정리
>
> ​     
>
> ⑦ 군집분석
>
> ⑧ 연관분석

​     

4. 비정형 데이터 마이닝

> ① 텍스트 마이닝 - 개념 및 절차(수집, 전처리, Term-Document matrix, 단어 사전, 분석 및 시각화)
>
> ② 사회연결망 분석 - 가이드와 다른 내용이 없으면 제외할 예정

​    

#### 5장 데이터 시각화 중 ggplot2

​     

1. ggplot2 : 함수 및 인자에 대한 설명







-- 2018.09.26 작성