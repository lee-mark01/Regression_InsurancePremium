# 보험료 예측 프로젝트
이 저장소는 보험료 데이터(Insurance Premium)를 기반으로 다양한 회귀(Regression) 모델을 적용해 보험료(Charges) 예측을 수행하는 실습 노트북을 포함합니다.

## 파일 구성
- 보험료_예측_SupervisedRegression.ipynb
보험료 예측을 위한 지도 학습(회귀) 분석을 다루는 Jupyter 노트북입니다.
데이터 전처리, 특성 엔지니어링, 여러 머신러닝 회귀 알고리즘, 성능 평가 및 모델 비교를 포함합니다.

  - 주요 내용
    1. 데이터 전처리:
       
      결측치 처리, 이상치 탐지 및 제거

      범주형 변수 인코딩(원핫 인코딩 등) 및 수치형 변수 스케일링
    
      데이터 분석 및 시각화

    2. 회귀 모델링:
       
      선형 회귀(Linear Regression)

      릿지(Lasso), 라쏘(Ridge) 등 정규화 회귀
    
      트리 기반 모델(Random Forest, Gradient Boosting)
    
      하이퍼파라미터 튜닝 및 교차검증

    3. 모델 성능 평가:
       
      RMSE, MAE, R² 등 주요 회귀 평가 지표

      예측 결과 시각화 및 실제 값 비교
    
      특성 중요도/회귀 계수 해석

## 실행 환경
Python >= 3.8
Jupyter Notebook
pandas, numpy, scikit-learn, matplotlib, seaborn, xgboost 등

# 데이터 출처
보험료 예측(Insurance Premium) 데이터셋:
Kaggle - Medical Cost Personal Datasets

# 사용 방법
노트북 실행 전 필요한 라이브러리 설치 (!pip install 사용, 또는 requirements.txt 등).

데이터셋 파일을 동일 폴더에 위치시킨 후, 노트북에서 셀 순서대로 실행.

분석 결과 및 코드 설명을 셀별로 참고.

참고 및 문의
코드, 주석 및 분석 요약은 주피터 노트북 파일에서 확인
