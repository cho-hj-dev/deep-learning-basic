# Week 03 - MNIST 첫 신경망 실습

## 실습 주제

MNIST 손글씨 숫자 이미지 분류

## 실습 목표

- MNIST 데이터셋 불러오기
- 훈련 데이터와 테스트 데이터 구조 확인하기
- 간단한 Dense 신경망 만들기
- 모델 컴파일과 학습 과정 이해하기
- 테스트 데이터로 정확도 확인하기

## 핵심 개념

- `train_images`: 모델이 학습할 이미지 데이터
- `train_labels`: 훈련 데이터의 정답
- `test_images`: 모델 평가에 사용할 이미지 데이터
- `test_labels`: 테스트 데이터의 정답
- `Dense`: 모든 뉴런이 서로 연결된 층
- `relu`: 은닉층에서 자주 사용하는 활성화 함수
- `softmax`: 여러 클래스 중 각 클래스일 확률을 출력하는 함수

## 데이터 구조

```python
train_images.shape
# (60000, 28, 28)

test_images.shape
# (10000, 28, 28)
