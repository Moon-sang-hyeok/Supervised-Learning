# More on Supervised Learning and Beyond

## Naive Bayes: Spam Filter
- 조건부 독립이라고 하는 가정이 현실과 맞지 않을 수 있음
- 합리적으로 작동한다
- 결과가 해석이 가능하다
- 한 번도 나오지 않은 단어는 어떻게 스팸?
  - Laplace Smoothing: 한번 씩은 카운트하는 방법

<br>

## Decision Tree(의사결정 나무)
- 해석 가능한 변수들을 통해서 모델을 해석 할 수 있다
- 성능이 복잡한 과제에서는 떨어질 수 있다

## Bagging
- 트리 여러 개를 앙상블 모델
- 분산을 줄이는 효과

## Adaptive Boosting (AdaBoost)
- 여러 개의 모델을 순차적으로 학습
- 틀린 것에 대해 더 강화하는 학습
- 과적합의 문제
