# 머신러닝의 용어와 개념 설명
 머신러닝에서 사용되는 용어들과 개념들에 대해 정리
 
##ML
 기존의 Explicit programming 방식은 모든 동작을 프로그래머가 지정하여 동작 수행
 방대한 데이터를 분석하여, 자동으로 동작을 학습하는 방식인 머신러닝 기법에 대해 연구

### 학습 방식
 학습방식은 Supervised Learning과 Unsupervised Learning 두가지 방식이 있다.
 
#### Supervised learning 
 label이 정리되어있는 dataset을 이용하여 학습을 시키는 데이타셋

 
 ML의 일반적인 문제
 * image labeling
 
 > label이 달린 이미지를 학습시켜 이미지를 인식
 * Email spam filter

 > 스팸 처리된 메일을 보고 스팸으로 처리할 메일을 학습
 * Predicting exam filter
 
 > 이전 시험친 사람의 공부 시간과 시험점수의 상관관계
 
#### Unsupervised learning
 label을 달아주기 힘든 data를 학습시키기 위해 사용
 data를 보고 스스로 학습 
 * google news
 
 > 스스로 학습하여 비슷한 기사들 끼리 grouping
 
### 용어 설명
#### regression
 Input에 대한 결과의 범위가 넓은 예측을 수행
#### binary classification
 Input에 대한 결과로 Pass / Non-Pas 와 같은 둘 중 하나의 label 선택하는 분류 방식
#### multi-label classification
 Input에 대한 결과가 학점(A,B,C,D,F)와 같은 다수의 label을 선택하는 방식
