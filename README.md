# World Happiness Classification

본 프로젝트는 World Happiness Report 데이터를 기반으로, 각 국가를 행복 수준에 따라 분류하는 모델을 개발하는 MLOps 과제입니다

## 파일 구성
- `happiness_classification.ipynb`: 전체 코드
- `requirements.txt`: 환경 설정을 위한 패키지 목록
- `README.md`: 프로젝트 설명 

## 사용 모델
- Random Forest (baseline)
- XGBoost (기본 + 튜닝)
- Logistic Regression (해석 기반)

## 주요 결과
- 최고 정확도: **Logistic Regression**, Accuracy = 0.92
- 가장 잘 분류되지 않은 클래스: **Class 0 (불행한 국가)**
- 중요 피처: `life_expectancy`, `gdp_per_capita`, `dystopia_residual`
