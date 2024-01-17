## 🚀 프로젝트명

### ✔️ 우울증 지수 예측 프로젝트 😞
<br>

## 📃 프로젝트 소개

#### ✔️ 이 프로젝트는 2018년부터 2022년까지의 전국 자치구 단위 데이터를 활용하여 <br> &nbsp; &nbsp; &nbsp; 우울증 지수(우울증 환자 수 대비 총 인구 수)를 예측하는 것을 목표로 합니다.
<br>

## ⚠️ 문제 정의
2022년 기준, 한국은 OECD 국가 중 우울증 유병률이 가장 높습니다.  
2003년부터 2016년, 그리고 2017년을 제외한 18년 동안 OECD 국가 중 자살률도 1위를 기록했습니다.    
통계청에 따르면 자살 원인 중 우울증이 35.4%로 가장 큰 비율을 차지합니다.  
<br>
자살 관련 기사가 많고, 주변에서도 우울증으로 인해 병원을 찾는 사람들을 자주 볼 수 있습니다.   
국민건강보험공단에 따르면, 2020년 우울증 진료를 받은 인원은 100만 461명에 달합니다.   
국민 4명 중 1명이 정신 질환을 경험하지만, 정부의 정신건강 예산은 세계보건기구(WHO) 권장치의 절반에도 미치지 못합니다.   
<br>
이러한 배경을 바탕으로, 우울증 지수에 가장 큰 영향을 미치는 요인을 파악하고 이에 대한 정책적 해결책을 모색하기 위해 본 프로젝트를 기획하였습니다.  

<br>

## 👩🏻‍💻 팀원 소개 및 역할

### ✔️ 팀원
- [❤️ 공예림 ❤️](https://github.com/yelimkong)
- [💛 김란 💛](https://github.com/raneeKim)
- [💙 한수빈 💙](https://github.com/bonasoobin)

### ✔️ 역할 분담
프로젝트를 진행하며 모든 팀원이 머신러닝 프로세스에 대한 경험을 쌓기 위해 데이터 수집 및 전처리, 탐색적 데이터 분석(EDA), 모델링, 파라미터 튜닝, 그리고 인사이트 도출과 같은 다양한 단계들을 각자 맡아 수행했습니다. 
작업의 관리를 용이하게 하기 위해, 각 팀원의 이름을 사용하여 별도의 브랜치(yelim, ranee, soobin)를 만들어 기록했습니다. 
<br>

### ✔️ 담당 모델
- GradientBoost : 공예림   
- Polynomial Regression / Ridge: 김란  
- SVR / RandomForest: 한수빈  
<br>


## 📅프로젝트 진행 기록

### ✔️ 수행 기간
2023.12.29 ~ 2024.01.18

### ✔️ 세부 진행 기록
- 23-12-29 : 주제 정하기 및 가설 설정
- 24-01-02 : 데이터 수집 및 전처리  
- 24-01-04 : 데이터 전처리
- 24-01-07 : 데이터 전처리
- 24-01-11 : EDA
- 24-01-15 : 모델링
- 24-01-16 : 최종 모델 선정 및 결론 정리
- 24-01-18 : 깃허브 readme 작성 및 노션 정리
<br>

## 📊 데이터 소개
### ✔️ 원본 데이터
- 우울증 환자 수 &nbsp; [출처](https://www.data.go.kr/data/15118810/fileData.do)
- 평균연령 &nbsp; [출처](https://jumin.mois.go.kr/etcStatAvgAge.do)
- 총인구수 &nbsp; [출처](https://jumin.mois.go.kr/)
- 스트레스 인지율 &nbsp; [출처](https://kosis.kr/statHtml/statHtml.do?orgId=101&tblId=DT_1YL0000_1&vw_cd=MT_GTITLE02&list_id=11_21&obj_var_id=A&itm_id=11110&seqNo=&conn_path=MT_GTITLE02&path=%252FstatisticsList%252FstatisticsListIndex.do)
- 고용률 &nbsp; [출처](https://kosis.kr/statHtml/statHtml.do?orgId=101&tblId=DT_1DA7004S&vw_cd=MT_ZTITLE&list_id=B11&seqNo=&lang_mode=ko&language=kor&obj_var_id=&itm_id=&conn_path=MT_ZTITLE)
- 코로나 확진자 수 &nbsp; [출처](https://www.data.go.kr/data/15124288/fileData.do)
- 인구 1인당 지역사회 정신건강 예산 &nbsp; [출처](https://kosis.kr/statHtml/statHtml.do?orgId=117&tblId=DT_920023_A010)
- 전국 도시 공원 정보 표준 데이터 &nbsp; [출처](https://www.data.go.kr/data/15012890/standard.do)
- 공공시설 운영 현황 &nbsp; [출처](https://www.lofin365.go.kr/portal/LF5110000.do?pdtaId=9YJWO8ESQV63PIUNS62Q1211398&rdIncrYn=Y&frstParamYn=Y)


### ✔️ 데이터 세부 사항
+ 기준 : 자치구 단위<br>
+ 데이터 기간 : 2018년 ~ 2022년
+ 데이터 갯수 : 1250개<br>
1. 시도 <br>
2. 시군구 <br>
3. 행정번호 <br>
4. 년도 <br>
5. 우울증 환자 수<br>
6. 평균연령 <br>
7. 총인구수 <br>
8. 스트레스 인지율 <br>
9. 고용률 <br>
10. 코로나 확진자 수<br>
11. 1인당 정신건강 예산(원) <br>
12. 공공시설 개수 <br>
13. 우울증 지수 (우울증 환자 수 대비 총 인구 수)   ----> 파생변수 / 종속변수 <br>
<br>

## 💡 가설 설정
#### ✔️ 가설 1

+ 귀무가설 : 나이가 들 수록 우울증의 비율이 높지 않을 것이다.
+ 대립가설  : 나이가 들 수록 우울증 비율이 높을 것이다

#### ✔️ 가설 2

- H1 : 코로나 확진자 수와 우울증 지수는 양의 상관관계가 있다.
- H2 : 고용률과 우울증 지수는 음의 상관관계가 있다.
- H3 : 평균 연령와 우울증 지수는 양의 상관관계가 있다.
- H4 : 공공시설 개수는 우울증 지수와 양의 상관관계가 있다.
<br>




## 💡 데이터 전처리
+ int형이었던 행정번호 컬럼은 object형으로 형변환
+ 2018년, 2019년의 코로나 확진자 수 0명으로 대체 
+ 공공시설 데이터와 공원 데이터 자치구 단위로 합침
+ 공공시설 데이터는 2018년, 2019년, 2020년, 2022년만 존재하기에 2021년 데이터는 2020년과 2022년의 평균값으로 대체
+ 공원 데이터 내의 대구광역시 군위군 -> 경상북도 군위군으로 변경(군위군의 대구광역시 편입은 2023년)
<br>

## 💡 탐색적 데이터 분석(EDA)
+ 변수 간 상관관계 행렬과 산점도 확인 -> 선형관계가 없다는 것을 확인
+ 시도, 시군구, 행정번호 컬럼은 식별자 컬럼이기 때문에 삭제
+ 박스플롯을 통해 이상치 확인 후, 이상치에 민감하지 않은 Robust 스케일링을 진행
+ ACF 그래프를 통해 년도 변수가 독립적임을 확인 -> 년도 변수 삭제
+ VIF 분석을 통한 다중공선성 확인 -> 다중공선성 없는 것으로 확인
<br>


## 💡 모델링
#### ✔️ 변수 간 비선형 관계임을 확인한 후 비선형 모델을 선택한 후 모델링















### ✔️ 사전 학습

주제 선정 배경
1. 국내 자동차 시장 중 신차 시장 대비 2배 이상의 규모에 해당하는 중고차 시장
2. 수입차(외제차)의 보편화로 인한 국내 수입차 점유율 증가 추이

도메인 학습
1. 국내/해외별 중고차 시장 가격 영향 요인이 다를 것이라 예상
2. 국내 중고 자동차 시장 가격 영향 요인 : 연식, 주행거리(km), 배기량(CC), 마력 순
3. 해외(튀르키예) 중고 자동차 시장 가격 영향 요인 : 브랜드, 주행거리(km), 연식, 변속기 순

### ✔️ 개요

1. 차량 번호를 조회하여 중고차 시세를 예측하는 서비스의 머신러닝 모델 기획
2. 소셜 데이터에 기반한 중고차 매매 관련 외부요인 탐색<br>
   (1) 크롤링/워드 클라우드 활용 네이버 블로그 '중고차,'중고차 하락' 검색 시 '수출','시세','사고','폐차','업체','국내' 등 키워드 도출
   (2) 해외 기준 국내 중고차 품질의 우수함을 인정받고 있지만 시스템의 부재로 걸맞는 가격을 받지 못하는 상황



### ✔️ 머신 러닝

1. 데이터 전처리<br>
   (1) 신차 / 중고차 분리 : 주행거리 < 200km 의 신차 데이터 drop<br>
   (2) 이상치 데이터 제거 : 주행거리 >= 250만km (최댓값) 데이터 1개 관측/제거<br>
   (3) 중복 Feature 통합 : get_dummies화된 연료 유형 통합<br>
   (4) 불필요한 컬럼 제거 : 'ID'(데이터 고유 키값) , 'City','Area' : 모두 폴란드 지역/도시<br>
   (5) 문자형 데이터 변환 : '브랜드','차량모델명','판매도시','판매구역' Label Encoding<br>
   (6) (선택사항) MinMaxScaling : '연도','차량모델출시년도' MinMaxScaler 적용<br>
2. 학습 결과 (MAE) <br>
   (1) LightGBM : 6.8398<br>
   (2) RandomForest : 6.3714 (K-fold,cv=5,avg값 기준)<br>
   (3) XGBoost : 6.4092<br>
   (4) LinearRegression : 11.95<br>
   (5) Lasso/LassoCV : 13.44 (alpha=1)<br>

    💡MAE 기준 가장 낮은 RandomForest 의 Feature_importances : '생상년도','CC','주행거리','차량출시년도'

3. AutoML <br>

   (1) 앞서 구현한 모델들의 MAE값을 줄이기 위해 Optuna, Auto Gluon, Pycaret 총 3가지의 AutoML을 사용<br>
   (2) Optuna : xgb의 경우 best Trial의 값이 5.885, lgbm의 경우 best trial의 값이 5.9726으로 기존의 MAE값 보다 더 나은 결과를 도출<br>
   (3) Auto Gluon :  L2 모델이 6.051919, xgb는 6.245744, lgbm은 6.165254로 기존의 MAE값 보다 더 나은 결과를 도출<br>
   (4) Pycaret : Blending을 통해 여러 모델들을 혼합하여 새로운 모델 생성 -> MAE가 가장 낮게 나온 모델인 CatBoost, XGBoost 모델 Blending : 5.8961, 렌덤으로 Blending
       한 모델 :  5.9002, 기존의 MAE 값 보다 더 나은 결과 도출<br>
   (5) 결론적으로 AutoML을 사용한 결과 모든 프레임 워크들이 기존의 K-Fold된된 모델의 MAE값보다 확연히 낮아진것을 확인하였으며, 그 중에서도 Optuna를 통해 생성한              XGBoost 모델의 MAE값이 가장 좋게 나온 것을 확인<br>

4. Auto ML 학습 결과 (MAE) <br>
   (1) Optuna (XGBoost) : 5.885<br>
   (2) Auto Gluon (L2) : 6.051919<br>
   (3) Pycaret (CatBoost, XGBoost Blend 모델) : 5.8961<br>
   

### ✔️ 결과

1. 이번 수입 중고차 가격 예측 프로젝트에서 MAE 기준 가장 최적화된 모델은 Optuna(AutoML)의 XGBoost 모델이고 '생산년도','주행거리','배기량','차량모델' 순으로 가격에 영향을 미쳤습니다.
2. 금리,나라별 가격,업체(딜러) 등을 독립변수로 추가할 수 있다면 더욱 정확한 예측 가능합니다.
3. 해당 모델/서비스를 통해 중고차 구매차 및 판매자들에게 여 중고치 시장의 활성화를 도모할 수 있습니다.

## 🛠 기술 스택

### ▪ 언어
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">

### ▪ 주요 라이브러리
<img src="https://img.shields.io/badge/scikit learn-F7931E?style=for-the-badge&logo=scikit learn&logoColor=white"> <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white"> <img src="https://img.shields.io/badge/seaborn-99CC00?style=for-the-badge&logo=seaborn&logoColor=white"> <img src="https://img.shields.io/badge/matplotlib-0058CC?style=for-the-badge&logo=matplotlib&logoColor=white"> <img src="https://img.shields.io/badge/wordcloud-FF4F8B?style=for-the-badge&logo=wordcloud&logoColor=white">
<img src="https://img.shields.io/badge/konlpy-FF0000?style=for-the-badge&logo=konlpy&logoColor=white"> <img src="https://img.shields.io/badge/collections-7FADF2?style=for-the-badge&logo=collections&logoColor=white">

### ▪ 개발 툴
<img src="https://img.shields.io/badge/VS code-2F80ED?style=for-the-badge&logo=VS code&logoColor=white"> <img src="https://img.shields.io/badge/Google Colab-F9AB00?style=for-the-badge&logo=Google Colab&logoColor=white">

### ▪ 협업 툴
<img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white"> <img src="https://img.shields.io/badge/Google Slides-FFBB00?style=for-the-badge&logo=Google Slides&logoColor=white">

## 🔍 참고 자료
### ✔️ 데이터
  
[데이콘 Basic 자동차 가격 예측 AI 경진대회](https://dacon.io/competitions/official/236114/overview/description)

### ✔️ 논문
1) 고찬영, 2021, 다중선형회귀분석을 이용한 중고차 가격 예측 연구 : A사의 사례를 중심으로』, 인하대학교 물류전문대학원 석사학위 논문
2) Sümeyra MUTİ1, Kazım YILDIZ2, 2023, Using Linear Regression For Used Car Price Prediction
,International Journal of Computational and
Experimental Science and ENgineering
,Vol. 9-No.1 (2023) pp. 11-16
