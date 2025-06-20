# 선박 AIS 데이터를 활용한 차기 도착항 예측 프로젝트

## 프로젝트 개요

본 프로젝트는 선박의 AIS 데이터를 기반으로, 머신러닝 알고리즘을 활용하여 선박의 차기 도착항을 예측하는 모델을 구축하였습니다. 
다양한 데이터 전처리 및 피처 엔지니어링을 수행하였으며, 여러 분류 모델을 비교하여 성능을 평가하고 최적의 예측 모델을 도출하는 것을 목표로 하였습니다.

## 주요 실험 내용

- AIS 데이터 전처리 및 파생 변수 생성
- 분류 모델 구축: 다양한 분류기 모델 적용 (Logistic Regression, Random Forest 등)
- 하이퍼파라미터 튜닝 및 최적화 실험 
- LSTM 딥러닝 모델 실험 (시도)
- 모델 성능 평가: 정확도, 혼동행렬 기반 평가
- PSO 알고리즘과 GEOJSON을 사용하여 항구별(부산항-도착항) 대표항로 추출 

## 폴더 및 파일 구성

- `최종 *.ipynb`: 최적화된 차기 도착항 예측 모델 결과 노트북
- `시도 파일/*.ipynb`: 실험 중 다양한 시도 및 테스트 과정 기록
- `LSTM_try*.ipynb`: LSTM 기반 딥러닝 모델 실험
- `군집 시도, 분류기 시도 ipynb`: 군집 수 조정 등 실험 흐름 기록

## 사용 라이브러리 및 사용 목적

- **pandas**: 데이터프레임 기반 데이터 전처리
- **numpy**: 수치 계산 및 배열 처리
- **scikit-learn**: 머신러닝 모델 구축, 평가, 하이퍼파라미터 튜닝
- **tensorflow / keras**: LSTM 기반 딥러닝 모델 실험
- **matplotlib, seaborn, forilum**: 데이터 시각화
