# Intro
[Convolutional Transformer를 이용한 자연어 처리 모델 연구](https://scienceon.kisti.re.kr/srch/selectPORSrchArticle.do?cn=DIKO0016396473)논문의 구현 코드입니다.

# Abstract
최근 자연어 처리 분야에서 BERT와 같은 Transformer 기반의 언어 모델을 대규모 데이터로 사전 학습하는 방식을 통해 성능을 향상시키고 있다. 그러나 사전 학습된 자연어 처리 모델은 일반적으로 계산 비용이 많이 들기 때문에 모바일 장치와 같은 계산 성능과 에너지 자원이 제한된 환경에서 효율적으로 실행하기 어렵다. 이에 따라 본 논문에서는 정확도를 유지하면서 계산 속도를 향상시키고 모델의 크기를 줄이기 위해 Convolutional layer를 적용한 새로운 Transformer기반 자연어 처리 모델을 제안한다.

 본 논문에서 제안하는 모델인 ConvTransformer는 BERT-base와 비교하여 3.67% 크기의 작은 모델로 MNLI, MRPC, QNLI, QQP, RTE, SST-2 등 6개의 작업에서 평균적으로 BERT 성능의 85.7%를 달성한다. 이러한 결과는 본 논문에서 제안된 모델이 적은 파라미터 수로 제한된 환경에서도 충분한 성능을 낼 수 있다는 것을 보여준다.

![](https://user-images.githubusercontent.com/41243762/175933263-c5cecf1e-31b7-495a-8b73-0a5908d59548.png)

# 개요
## 모델
![](https://user-images.githubusercontent.com/41243762/175934268-ddc41e85-0f20-4681-aecd-53c6082bf41c.png)

## 성능
![](https://user-images.githubusercontent.com/41243762/175934813-79e98cd4-8d02-4a58-b74c-2bf96dcead92.png)
