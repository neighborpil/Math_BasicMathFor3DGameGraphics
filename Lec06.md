#Lec06


## 선형성(Linearity, 線型性)
 - 아래 두가지 수식을 만족하면 선형성을 가진다고 함

![image](https://user-images.githubusercontent.com/22423285/132954632-61103a5e-5b69-445e-9ebf-add1b103bbc8.png)

 - 가산성: 두가지 인자를 더하여 함수를 통과시킨 것과, 각각의 인자를 함수를 통과시켜 더한 것이 같은 것
 - 1차 동차성: 스칼라값 a에 대하여 인자 x를 함수f에 통과시킨 후 곱한 것과 ax를 함수f에 통과시킨것의 값이 같은 것

![image](https://user-images.githubusercontent.com/22423285/132954728-a5fa89f2-655d-4d93-9ee6-fdfa652e3495.png)

![image](https://user-images.githubusercontent.com/22423285/132954738-4514656c-b996-4ff8-b9db-10e0588225cf.png)

![image](https://user-images.githubusercontent.com/22423285/132954748-ec400bd7-06e1-4eb4-ac3e-1ed917224d4b.png)

![image](https://user-images.githubusercontent.com/22423285/132954754-ea28f7f0-164b-49a3-8c5a-9e59f256678b.png)

![image](https://user-images.githubusercontent.com/22423285/132955123-6c47c1dd-300d-4d60-9d6e-c4107eaebc3c.png)

 - 선형성을 가진 다는 것은 두가지를 복잡하게 계산한 것과 두가지를 따로 떼어서 계산한 것이 동일한 결과를 나타낸 것이기 때문에 간단히 분리 할 수 있다
 - 그래픽스에서는 변환?에 많이 사용된다
 
## 선형 사상 ( Linear Mapping )
 - 사상과 함수의 차이
 - 함수(Function) : 집합과 집합의 대응 관계
 - 사상(Mapping) : 집합이 가지는 수학적 체계(공리)를 보존하면서 서로 대응하는 관계

![image](https://user-images.githubusercontent.com/22423285/132955150-b42c21fe-10fc-4529-a5bc-d9c8b94b3ba7.png)

### 사상의 예

![image](https://user-images.githubusercontent.com/22423285/132955158-a2b84de4-bd33-4078-923d-b7a14bc72370.png)

### 선형성을 가지는 사상의 조건

![image](https://user-images.githubusercontent.com/22423285/132955328-ba9a9397-fc30-44ce-9d26-fb5301d41b47.png)










과제

1. 선형성을 가지는 함수는 어떤 형태가 되는지 정리하시오.
 - 가산성과 1차 동차성을 만족하는 형태를 가진다
2. y=ax+b 형태의 함수는 왜 선형성을 만족하지 못하는지 자신의 생각을 정리하시오.
 - 선형성이란 인자의 1차 배례관계로 구성된 대응관계이나, ax + b에서 b로 인하여 비례관계가 깨어져서 그렇다
3. 2차원 공간에서 2차원 공간에 대응되는 선형 변환의 형태는 f((x,y))=(ax+by, cx+dy) 임을 정리하시오.
