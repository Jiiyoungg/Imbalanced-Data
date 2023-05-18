# Imbalanced-Data
Sampling+StackingEnsemble


라벨링 불균형 데이터 처리
===========
이진분류 문제에서 target에서 1의 비율이 4%로 불균형이 매우 심한 경우


다양한 샘플링 시도
----------
1. Random Samping
2. Tomek Links
3. Resampling
4. SMOTE
5. Borderline SMOTE
6. ADASYN
7. MICE


스태킹 앙상블
----------
> LGBM 3개, XGBoost 1개 총 4개의 모델 사용
> 4개의 모델 각각의 결과를 LogisticRegression을 Final 모델로 사용하여 최종 예측
