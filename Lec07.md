#Lec05

## 1. 행렬(Matrix)
 - 사각형 안에 수를 행과 열에 맞춰 배열한 것
 - 복잡한 선형 변환의 식을 계산하기 편하게 단순화시킨 계산 도구
 - 선형 변환의 표현

![image](https://user-images.githubusercontent.com/22423285/134786839-9a988ff9-1fed-42f5-a815-c51d56bfddb1.png)

### 행렬과 행렬의 덧셈 연산

![image](https://user-images.githubusercontent.com/22423285/134786853-06aa2536-2d15-46d4-8440-00db82f59864.png)


### 행렬과 스칼라의 곱셈 연산

![image](https://user-images.githubusercontent.com/22423285/134786854-efe74330-a6dc-4980-ac38-b25e79a02a28.png)


### 행렬의 전치(Transpose) 연산

![image](https://user-images.githubusercontent.com/22423285/134786858-d79490f7-a54f-42b8-b636-d6f4e8e4ec91.png)

### 행렬과 행렬의 곱셈 연산

![image](https://user-images.githubusercontent.com/22423285/134786864-187ae9bf-886a-41e2-89a6-f576402a01f7.png)

### 행렬 곱셈 연산의 특징
 1. 교환 법칙을 만족하지 않는다. 

![image](https://user-images.githubusercontent.com/22423285/134786879-4312a080-0a62-4dc2-a3b0-641ff1d6a2bc.png)

 2. 결합 법칙은 만족한다.

![image](https://user-images.githubusercontent.com/22423285/134786882-ef976923-f837-44e5-932b-4e03c2986b4f.png)

 3. 행렬 곱의 전치 연산

![image](https://user-images.githubusercontent.com/22423285/134786887-650a4d2f-6234-47aa-804f-f5e7a383ba50.png)

 4. 복잡하지만 분배법칙도 만족함

#### 정방행렬 : 행과 열이 같은 행렬

## 2. 선형 변환과 행렬

![image](https://user-images.githubusercontent.com/22423285/134786898-e5429f1b-c16f-474c-8194-ffbf687186f7.png)

### 열기반 행렬과 행기반 행

![image](https://user-images.githubusercontent.com/22423285/134786912-13871bbc-f33f-4172-8d15-3a88bc94784d.png)

## 3. 선형 변환의 시각화

### 원 벡터 공간의 선형 변환

![image](https://user-images.githubusercontent.com/22423285/134786925-398288d2-323b-4772-94af-3ddaa0e3ffe8.png)

### 기저 벡터의 변환

![image](https://user-images.githubusercontent.com/22423285/134786936-18010b84-e9dd-47e3-a96a-ff71f9678b36.png)

### 크기 변환 행렬

![image](https://user-images.githubusercontent.com/22423285/134786943-da4ba349-29f9-4b62-b7d1-8e6e4eabe6d8.png)

### 밀기 변환

![image](https://user-images.githubusercontent.com/22423285/134786948-65f4a3f0-cdd0-49ff-844a-55cfa7cfe873.png)

### 시계 방향 90도 회전 변환

![image](https://user-images.githubusercontent.com/22423285/134786954-8bacfd38-63d6-47f3-bf93-30f5eec30116.png)

### 반시계 방향 90도 회전 변환

![image](https://user-images.githubusercontent.com/22423285/134786962-9f8a2d2e-f9c0-4ea0-bea8-247de46fb71e.png)

### 임의의 각 θ에 대한 회전 변환

![image](https://user-images.githubusercontent.com/22423285/134786978-11ca6780-520a-43da-8de5-2a07adb71bb4.png)

## 4. 행렬의 곱

### 행렬의 곱
 - 행렬은 하나의 선형 변환에 대응되며, 행렬의 곱은 선형 변환을 적용한 결과에 다시 선형 변환을 적용한 결과를 다음과 같이 진행된다.

![image](https://user-images.githubusercontent.com/22423285/134786991-c5e513d2-4e1b-4517-b4cb-3c3f6c953825.png)

![image](https://user-images.githubusercontent.com/22423285/134786999-719d37c1-9075-4085-8ed9-64a032ffe37b.png)

### 삼각함수의 합 공식

![image](https://user-images.githubusercontent.com/22423285/134787005-0414e462-059d-40f4-b699-f8358d13989f.png)

### 행렬의 장점

![image](https://user-images.githubusercontent.com/22423285/134787013-ebfeface-1067-4df5-b522-265b8a5e9101.png)


과제
1. 행렬의 기본 연산에 대해 정리하시오.
 - 덧셈, 스칼라곱셈, 전치, 행렬간 곱셈 

2. 형렬 곱셈 연산이 가지는 성질(교환법칙, 결합법칙)에 대해 정리하시오.
 - 교환법칙(X),  결합법칙(O)
3. 행렬 곱셈 연산은 선형 변환과 동일함을 정리하시오.
 - 정방행렬은 같은 차원의 공간이 서로 대응되는 선형 변환이다
 - 열 벡터는 벡터 공간의 벡터를 의미한다
 - 
4. 열기반 행렬과 행기반 행렬의 차이에 대해 정리하시오.
 - 형태가 다를지라도 전치하면 동일하다

5. 기저 벡터의 변화를 추적해 크기 변환, 밀기 변환, 회전 변환에 대해 정리하시오.
 - 열벡터의 표준 기저벡터가 변화되었다고 파악하여 정의한다
 - 세로로 x,y 일차원 벡터를 배열해 행렬을 만들고 곱셈연산하면 된다
 - 크기변환: x(a, 0), y(0, b)의 선형변환이다. 기저 벡터의 x축에 a배, y축에 b배
 - 밀기변환: 기저 자체가 변환
 - 회전변환: 90도변환 x, y의 위치를 바꾼 후 x에 -붙여줌 

6. 행렬의 곱이 가지는 성질을 활용해 삼각함수의 합 공식을 유도하시오.
 - 각 a, b만큼 두번 회전 할 경우 결합법칙을 이용하여 하나의 행렬로 만들어 적용
