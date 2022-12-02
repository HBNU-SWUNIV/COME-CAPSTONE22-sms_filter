# 한밭대학교 컴퓨터공학과 runningrate팀

**팀 구성**
- 20157092 김상민 


## <u>Teamate</u> Project Background
- ### 필요성
  - 수많은 정보가 오가는 정보화시대에 불필요한 정보를 담은 SMS, 피싱 SMS 등으로 인하여 금전적인 피해 및 개인정보 유출 등의 피해를 보는 사람들이 늘어나고 있음
  - 이러한 피해를 입는 것을 방지하기위해 이메일을 필터링하여 스팸 SMS과 정상 SMS으로 분류할 필요가 있음
- ### 기존 해결책의 문제점
  - 높은 정확도를 위해서는 많은 데이터들이 필요
  - 다양한 모델과의 비교, 좋은 파라미터가 필요
  
## System Design
  ![캡2](https://user-images.githubusercontent.com/116828394/205301386-9b6e5f2e-4452-474a-a2fc-fce7ed45542d.JPG)

  - ### System Requirements
    - 팀 프로젝트 데이터 자동 수집 → Kaggle 데이터셋 이용
  ![image](https://user-images.githubusercontent.com/116828394/205302215-2bbe9d71-08c8-403a-9cac-3f4987fdea1c.png)

## Case Study
  - ### 데이터 수집
  ![image](https://user-images.githubusercontent.com/116828394/205302893-13b6ed72-94a6-4b01-9581-1c95db3b3529.png)
  - ### 데이터 시각화
  ![image](https://user-images.githubusercontent.com/116828394/205303663-31e82901-ec4c-44cc-9b89-0dff22a28e63.png)
  - ### 모델 학습
  ![image](https://user-images.githubusercontent.com/116828394/205304269-8e41da55-1f3c-44b1-95ef-d8702c93bd08.png)
  
    - Linear kernel, Poly kernel, Sigmoid kernel로 측정 후 정확도 분석
    - 컨퓨젼 매트릭스를 이용하여 빈도 분석
## Conclusion
  - ### 문제점 
    - SVM 모델의 Poly kernel은 94%의 살짝 낮은 정확도를 보임
  - ### 분석
    - 학습시킨 모델의 스팸 SMS 분류를 통한 피해 발생을 방지
    - 이러한 모델과 같은 다른 모델을 활용하여 더 많은 데이터를 수집 후 분류할 수 있도록 정확도를 높임
  
## Project Outcome
- ### 2022 년 공학교육학술대회
![image](https://user-images.githubusercontent.com/116828394/205305219-6cd4849a-7d96-4d64-9443-d21445c2c716.png)

![image](https://user-images.githubusercontent.com/116828394/205305435-645d1ef6-d6a8-4487-b07b-a5b617ac7f70.png)

![image](https://user-images.githubusercontent.com/116828394/205305537-00779dcb-8ef7-4eea-98c4-482c34dcd55b.png)
![image](https://user-images.githubusercontent.com/116828394/205305825-f4889259-aa3f-438e-8bac-b8440ace516e.png)





