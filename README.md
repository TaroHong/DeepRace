# AWS DeepRacer

AWS DeepRacer는 강화 학습을 사용하여 자율 주행 자동차를 훈련하는 AWS의 기계 학습 서비스입니다.    
2024년 6월에 실시한 [AWS DeepRacer를 활용한 AI 융합 교육]으로 만들었습니다.

## 목차
- [프로젝트 소개](#프로젝트-소개)
- [학습 내용](#학습-내용)
- [기술 스택](#기술-스택)
- [사용 방법](#사용-방법)

## 프로젝트 소개
이 프로젝트에서는 AWS DeepRacer를 사용하여 강화 학습 기반의 자율 주행 자동차 모델을 훈련하고 평가했습니다.    
DeepRacer는 실제 물리적 자동차 모델을 사용하거나 가상 환경에서 시뮬레이션을 수행할 수 있습니다.

## 참고 링크
* [원회전탐색](https://falktan.medium.com/aws-deepracer-how-to-train-a-model-in-15-minutes-a07ab77fb793)
* [경로최적화](https://github.com/TwoDigits/deepracer/blob/master/reward_function.py)
* [파라미터 및 기타자료들](https://deepracer-school-ko.ai-castle.com/intro.html)
* [최단루트 및 속도계산기](https://colab.research.google.com/drive/1USh9C3sG1cP_A9PWy3Ywy5JWX5x9ZsVt#scrollTo=eroSE4c6nExR)

## 학습 내용
1. 자율주행
2. 인공지능
3. 딥러닝
4. 강화 학습
5. 파이썬 프로그래밍
6. 클라우드 컴퓨팅
7. AWS 서비스 활용
8. DeepRacer 운영
9. 리그 참가

## 기술 스택
하이퍼 파라미터에 대해서는 트랙에 맞게 변동하는걸 권장합니다.    
강화학습은 과적합에 주의해서 해야 하고 학습률과 완주율의 적당한 타협을 해야합니다.

AWS를 활용하여 강화학습중    

![GIFMaker_me](https://github.com/user-attachments/assets/1b8922f5-a94d-4f53-938d-9fb40b338f46)
    
실제 필드에서 주행시 시뮬레이션과 똑같이 나오지 않으며 일반화가 잘 된 모델이 랩타임이 빠르다.
![GIFMaker_me](https://github.com/user-attachments/assets/0394d1d9-06a4-4e5a-b071-57dc9e0bcd18)

## 사용 방법
AWS DeepRacer를 사용하려면 AWS 계정이 필요합니다.

1. AWS 콘솔에서 DeepRacer 서비스를 찾아 이용할 수 있습니다.
2. 가상 트랙에서 강화 학습 모델을 훈련하고 평가할 수 있습니다.
3. 훈련된 모델을 실제 DeepRacer 자동차에 배포하여 주행할 수 있습니다.


