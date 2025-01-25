# Multimodal_AI_2

1. 폴더명으로 나눔 (train(01~14)val(17~18)test(15~16))
폴더 구조
- AGV
    - train(01~14)
    - val(17~18)
    - test(15~16)
- OHT
    - train(01~14)
    - val(17~18)
    - test(15~16)

시계열 데이터만 사용 (SVM 모델)
- AGV만 : 96~97%
- OHT만 : 95%
- AGV OHT 동시에 : 96%

이미지 데이터만 사용 (VIT 모델)
- AGV : 60~71%
- OHT : 75~80%

  멀티모달 실험
- AGV : 93%
- OHT : 95%
