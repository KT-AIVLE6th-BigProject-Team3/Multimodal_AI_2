# Multimodal_AI_2

**1. 폴더명으로 나눔 (train(01~14)val(17~18)test(15~16))**

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



**2. 폴더자체나눔 (8:2:2)**

폴더구조
- AGV : 5개 train 1개 val 1개 test
    - train(01~18)
    - val(01~18)
    - test(01~18)
- OHT : 8개 train 2개 val 2개 test
    - train(01~18)
    - val(01~18)
    - test(01~18)
 
시계열 데이터만 사용 (SVM 모델)
- AGV 만 : 94%
- OHT 만 : 90%
- AGV, OHT : 91%

이미지 데이터만 사용 (VIT 모델)
- AGV : 50%
- OHT : 50%

  멀티모달 실험
- AGV : 91%
- OHT : 89%



**3. 폴더명으로 나눔 (train(01~11)val(12~16)test(17~18))**

폴더 구조
- AGV
    - train(01~11)
    - val(12~16)
    - test(17~18)
- OHT
    - train(01~11)
    - val(12~16)
    - test(17~18)

시계열 데이터만 사용 (SVM 모델)
- AGV만 : 93%
- OHT만 : 94%
- AGV OHT 동시에 : 95%

이미지 데이터만 사용 (VIT 모델)
- AGV : 60~70%
- OHT : 64~68%

  멀티모달 실험
- AGV : 89%
- OHT : 94%
