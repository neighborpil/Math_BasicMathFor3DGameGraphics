#Lec04 선형독립

## 벡터의 생성(Span) 시스템
### 선형 조합(Linear Combination)
 - 벡터의 기본 연산을 사용해 새로운 벡터를 생성하는 수식

![image](https://user-images.githubusercontent.com/22423285/131179961-f7d5c87a-e835-4c6b-880a-79757b7678a9.png)

### 선형 의존과 선형 독립
 - 다음 수식을 만족하는 0이 아닌 계수가 존재하면 수식 내 벡터들은 선형 의존

![image](https://user-images.githubusercontent.com/22423285/131180175-252e2b0a-8f99-4909-873b-de181ef02ee9.png)

 - 다음 수식을 만족하기 위해 어떤 계수 값이 0이라면 수식 내 벡터들은 선형 독립

![image](https://user-images.githubusercontent.com/22423285/131180203-1f3a723d-fcf5-4430-9a95-9cca1e3f8672.png)

![image](https://user-images.githubusercontent.com/22423285/131181772-ed88e3ea-7b02-4403-9d2e-ec1898adfb11.png)

### 벡터의 조합으로 모든 벡트 생성
 - 스칼라곱이 아닌 두벡터라면 가능하다

![image](https://user-images.githubusercontent.com/22423285/131182270-e35a90d8-87bc-4e46-b5b2-7b2561e99670.png)

![image](https://user-images.githubusercontent.com/22423285/131182552-fde55be3-1ce2-4971-81ae-fbbcc44b6160.png)


 - 스칼라 곱이되는 두 벡터라면 하나의 직선만 생성 가능하다
 - 
![image](https://user-images.githubusercontent.com/22423285/131182525-5bc269e0-8c07-4d7f-8632-900717c80c78.png)

![image](https://user-images.githubusercontent.com/22423285/131182575-2802ee99-06d3-4720-b69b-5a05cda91925.png)



## 기저(Basis)와 차원(Dimension)
 - 기저(Basis) : 벡터 공간 내 모든 벡터를 생성할 수 있는 선형 독립인 벡터들의 집합
 - 기저 벡터(Basis vector) : 기저 집합에 속한 원소
 - 차원(Dimension) : 기저 집합이 가지는 원소의 수
 - 2차원 평면을 생성하기 위해서는 항상 2개의 기저벡터를 가진다

![image](https://user-images.githubusercontent.com/22423285/131183478-4b5e3e63-e4f2-41c8-b649-ac263e98b991.png)

 - 실 벡터 공간을 표기할 때 차원의 정보를 사용해 첨자를 붙여 표현

![image](https://user-images.githubusercontent.com/22423285/131183752-ae033779-3728-4d2e-b2ee-d89b681264d4.png)

### 표준 기저 벡터(Standard basis vector)
 - 기저벡터 중에서 가장 기본이 되는 벡터
 
 ![image](https://user-images.githubusercontent.com/22423285/131183820-279c2c54-2df2-41d3-8e6d-1d9202a29157.png)



과제
1. 선형 조합에 대해 정리하고 선형 조합이 가지는 의미에 대해 자신의 생각을 정리하시오.
 - 벡터의 스칼라곱과 벡터의 덧셈을 통하여 새로운 벡터를 생성하는 것

2. 선형 의존과 선형 독립의 조건을 정리하시오.
 - 선형의존: n개의 벡터의 합이 0벡터가 되고, 모든 벡터는 계수가 0이 아닐 때
 - 선형독립: n개의 벡터의 합이 0이고, 계수의 값이 0만 존재할 경우

3. 평면 상의 벡터를 생성하기 위해 선형 독립인 두 벡터가 필요함을 정리해보시오.
 - 스칼라곱이 아닌 두개의 벡터의 원점을 변경함으로써 모든 벡터를 생성 가능하다
 - 하지만 선형독립이 아닌 스칼라 곱인 두개의 벡터 조합으로는 선형의 벡터만 생성이 가능하다

4. 다음의 용어에 대해 정리하시오.
( 기저, 기저 벡터 , 차원 )
 - 기저: 벡터 공간 내 모든 벡터를 생성할 수 있는 선형 독립인 벡터들의 집합
 - 기저벡터: 기저를 이루는 집합의 원소
 - 차원: 기저 집합이 가지는 원소의 수

5. 평면을 구성하는 차원의 값은 왜 3이 될 수 없는지 그 이유를 정리하시오.
 - 세번째 벡터가 역원이 되어 선형 독립을 만족하지 못 할 수 있다.
