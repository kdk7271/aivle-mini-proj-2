# AIVLE SCHOOL 미니프로젝트 2차 

![Image](https://github.com/user-attachments/assets/73726257-cdd8-47fa-9c5c-868d1f1f8c9a)
---

## 신규 아파트 주차장 수요예측

> KT AIVLE SCHOOL 미니 프로젝트 2차
> 
> 기간 : 2025-10-14 ~ 2025-10-17


## 프로젝트 소개

신규 아파트 단지에서 필요한 주차 공간의 수요를 예측하는 머신러닝 모델을 개발하는 프로젝트입니다.
데이터 전처리, 탐색적 데이터 분석(EDA), 다양한 머신러닝 모델을 활용한 예측을 통해 최적의 주차 공간 계획을 수립하는 프로젝트입니다.

## 주요 과정

1. 데이터 전처리 및 탐색적 분석(EDA)
2. 머신러닝 모델 구축(4개 이상 알고리즘 활용) 및 성능 비교
3. 최적 모델 선정 및 하이퍼파라미터 튜닝
4. 데이터 파이프라인 구성 및 자동화

## 프로젝트 결과

![Image](https://github.com/user-attachments/assets/87b7af68-96a2-46ed-aeb6-879d3b278ee5)
----
![Image](https://github.com/user-attachments/assets/8e7881bb-1775-4dc1-ad02-5eb222d96872)
----
![Image](https://github.com/user-attachments/assets/0ae091d0-201f-42af-b467-d0c3c9147520)
---
![Image](https://github.com/user-attachments/assets/1d4d68c8-a2af-4a03-a3c8-2f8e423c8f7e)

![Image](https://github.com/user-attachments/assets/b6c92067-5ce6-4d73-9a46-c6ea906ff8fa)


이번 프로젝트에서는 Linear Regression, LightGBM, XGBoost 등의 머신러닝 모델을 활용하여 신규 아파트 단지의 주차 수요를 예측하였다. 각 모델의 예측 결과를 비교한 결과, LightGBM과 XGBoost가 상대적으로 우수한 성능을 보이는 것으로 나타났다.

모델별 예측값을 비교한 그래프를 분석한 결과, 단순 선형 회귀(Linear Regression)는 일부 데이터에서 과소 또는 과대 예측하는 경향이 있었다. 반면, LightGBM과 XGBoost는 비선형적인 관계를 보다 효과적으로 학습하여 실제 데이터에 가까운 예측값을 생성하는 경향을 보였다.

이를 통해 머신러닝 모델을 활용하여 신규 아파트 단지의 주차 수요를 효과적으로 예측할 수 있음을 확인하였으며, 다양한 모델을 비교함으로써 최적의 예측 모델을 선정할 수 있었다. 이후 추가적인 변수 탐색과 하이퍼파라미터 튜닝을 통해 모델 성능을 더욱 향상시킬수 있을 것으로 예상된다.


## 느낀점

이번 프로젝트 결과는 신규 아파트 단지의 주차 공간 계획을 수립하는 과정에서 데이터 기반의 의사결정을 지원할 수 있으며, 이를 통해 주차 공간 부족이나 과잉 공급과 같은 문제를 해결하는 데 기여할 수 있을 것으로 기대된다.
