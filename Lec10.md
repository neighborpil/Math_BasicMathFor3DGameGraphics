#Lec10

## 1. 벡터의 내적 ( Dot Product )

벡터의 연산

- 기본 연산
- 유용한 연산

기본 연산이란?

- 벡터 생성에 관여하는 중요한 연산
- 
![image](https://user-images.githubusercontent.com/22423285/141192724-8938f663-59b5-415f-a526-36569a718549.png)

### 벡터의 내적 ( Dot Product )

![image](https://user-images.githubusercontent.com/22423285/141192848-1f6e2562-5cb2-4be6-b3d2-3fb5e3105f52.png)

### 벡터 내적의 코사인 공식

벡터 내적에서 가장 중요한 공식

![image](https://user-images.githubusercontent.com/22423285/141193004-8713168a-c165-4c3e-a405-0f089af7bea2.png)

![image](https://user-images.githubusercontent.com/22423285/141193046-df0d4ea2-341f-4933-8dba-5b527b22eb6e.png)

### 벡터 내적의 직교성 판별

![image](https://user-images.githubusercontent.com/22423285/141193086-c50167e8-6c3c-420b-a2fd-d585cfd7ba10.png)

![image](https://user-images.githubusercontent.com/22423285/141193144-8ec56a4c-dea4-4484-931f-aabc11d35132.png)

### 리지드 트랜스포메이션 ( Rigid Transformation )

물체의 형태가 변하지 않는 변환의 조건은 무엇인가?

- 공간을 구성하는 모든 기저 벡터의 크기가 1
- 모든 기저 벡터가 서로 직교하고 있어야 함
- 선형 변환의 행렬식 값이 1

이를 만족하는 변환은 회전 변환이다. 

![image](https://user-images.githubusercontent.com/22423285/141193172-8b4c2625-bf5c-4f32-b617-bae1b5814167.png)

따라서 회전 변환은 물체의 형태를 변형시키지 않는다. 

## 2. 벡터 내적의 활용

### 앞 뒤 판별

![image](https://user-images.githubusercontent.com/22423285/141193228-5bcf7db4-e2c5-4790-92ab-1169a88a9cd7.png) 

### 시야 판별

![image](https://user-images.githubusercontent.com/22423285/141193287-addfe0cb-2040-4de8-b628-cd0b522198a7.png)

![image](https://user-images.githubusercontent.com/22423285/141193319-675ee01a-0075-42db-8c19-813021188940.png)

### 음영 계산

램버트 코사인 법칙 : 물체 표면이 반사하는 빛의 휘도(Luminance)는 표면 방향과 광원 방향의 사잇각의 코사인 값에 비례한다.

![image](https://user-images.githubusercontent.com/22423285/141193349-47272f08-4a17-4629-ac12-e4c3cac39d31.png)

![image](https://user-images.githubusercontent.com/22423285/141193370-d871e738-d836-47eb-a531-e5cb545e470a.png)

### 투영 벡터 공식
![image](https://user-images.githubusercontent.com/22423285/141193436-691ccf97-79db-4c15-b215-72cc0e16027a.png)

![image](https://user-images.githubusercontent.com/22423285/141193459-ee450708-1b4c-4abe-880b-85cfb35622bf.png)


과제

1. 벡터의 내적이 가지는 특징에 대해 정리하시오.
( 교환 법칙, 결합 법칙, 분배 법칙, 동일한 벡터의 내적의 결과 )

2. 벡터 내적의 코사인 법칙을 직접 유도해보시오.

3. 벡터 내적은 두 벡터의 사잇각의 코사인 함수에 비례하는 성질을 가지고 있다. 게임 제작 과정에서 이를 응용할 수 있는 방법을 정리하시오.

4. 어떤 변환이 강체 변환(리지드 트랜스포메이션)이 되기 위한 조건을 나열하시오.
