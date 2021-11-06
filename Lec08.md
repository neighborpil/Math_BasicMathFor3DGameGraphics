#Lec05


## 1. 역행렬(Inverse Matrix)

### 항등 행렬(Identity Matrix)

선형 변환의 결과가 변함없는 행렬

두 표준 기저벡터 $e_1, e_2$의 값이 동일하게 유지되는 선형변환을 의미

![image](https://user-images.githubusercontent.com/22423285/140609856-e7641db3-bb7a-48a6-8bd3-dbe8f87856b2.png)

### 역행렬이란?

선형 변환된 결과를 거꾸로 돌려주는 선형 변환.  이를 합성한 결과는 항등 변환이 된다. 

![image](https://user-images.githubusercontent.com/22423285/140609864-cca053e9-5a76-4462-abf1-a45d9757d17f.png)

## 2. 역행렬의 계산 방법

### 행렬식(Determinant)

![image](https://user-images.githubusercontent.com/22423285/140609874-0231d49d-2b46-46dd-81f6-83da4992c4b9.png)

아래 연립방정식의 해는 존재하는가?
![image](https://user-images.githubusercontent.com/22423285/140609901-c5e4e618-7d13-43b9-bac0-f555be0759d4.png)

위 변환을 분석하면 표준기저벡터 e1, e2는 각각 (2,1), (1,0.5)로 변환되었는데, 이 둘은 같은 기울기를 가지고 있음을 알 수 있다.  따라서 두 기저 벡터가 선형 독립에서 선형 의존 관계가 되었다.

이를 그림으로 나타내면 다음과 같다. 

![image](https://user-images.githubusercontent.com/22423285/140610007-8030265d-d554-4fb3-af9b-9bba53c5c3f5.png)

위의 경우 선형변환의 결과로 2차원 평면이 1차원 직선으로 소멸되었기에 1차원에서 2차원으로 돌아가는 역행렬은 존재하지 않는다.

![image](https://user-images.githubusercontent.com/22423285/140609926-c1860f60-aec7-4cd2-aafd-da473547ba67.png)

그렇다면 어째서 ad-bc가 0이면 차원이 소멸되는 것인가?

두 벡터가 만드는 평행사변형의 넓이를 확인해보자. 
![image](https://user-images.githubusercontent.com/22423285/140609941-5503d811-2342-47fc-ace6-97f1814d7dd5.png)

전체 사각형에서 남은 부피를 빼면 넓이 값은 ad-bc임을 알 수 있다. 따라서 해당 넓이가 0이라면 두 벡터가 동일한 기울기로 겹쳐있게됨을 알 수 있다. 이는 선형 의존임을 의미한다. 

만약 역행렬이 존재한다면 어떻게 되는가? 

다음과 같은 변환을 생각하면 평면이 행렬식 값만큼 달라짐을 알 수 있다.

그렇다면 원상 복구하기 위해서는 달라진 크기의 역수만큼 변해야 한다.    

![image](https://user-images.githubusercontent.com/22423285/140609953-e8c96dba-2a6e-4c4b-b77f-eb2067f0aeb5.png)

### 역행렬의 활용

연립방정식의 해를 구할 때 유용하게 사용된다. 

![image](https://user-images.githubusercontent.com/22423285/140609972-cf735008-6daa-4dce-ba90-6ac335d8e540.png)

임의의 정방행렬의 역행렬을 구하기 위한 방법은 여러가지가 있는데 대표적으로 다음의 방법들이 존재한다.  

- 가우스 소거법 ( Gaussian elimination )
- 크라메르 공식 ( Cramer's rule)

하지만 우리가 사용하는 대표적인 선형 변환들은 위의 방법을 사용하지 않고 직관적으로 역행렬을 구하는 것이 가능하다. 

### 크기 행렬의 역행렬

![image](https://user-images.githubusercontent.com/22423285/140609980-e2576df7-97a0-4e44-8504-8243a4e4b9b2.png)

### 밀기 행렬의 역행렬

![image](https://user-images.githubusercontent.com/22423285/140609988-b2dec9ce-89e7-42ac-8943-113d7a17cadb.png)

### 회전 행렬의 역행렬
![image](https://user-images.githubusercontent.com/22423285/140609995-369ed498-6917-4f99-a0e0-a7fcd6f328d2.png)

과제

1. 항등행렬과 역행렬이 가지는 변환의 의미를 시각적으로 정리하시오.
2. 행렬식이 0이면 변환 과정에서 어떤 문제가 발생하는지 정리하시오.
3. 크기 행렬, 밀기 행렬, 회전 행렬의 역행렬에 대해 정리하시오.
4. 회전 행렬의 역행렬은 어째서 전치행렬이 되는지 정리하시오.
