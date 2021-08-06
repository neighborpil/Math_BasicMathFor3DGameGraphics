#Lec01

## 함수의 정의
 - 두 집합의 정의를 의미
 - 첫번째 집합의 모든 요소가 사용되어야 함
### 함수가 아닌 대응관계
- 첫 번째 집합의 어떤 원소에 대한 대응 관계가 빠져 있을 때
- 첫 번째 집합의 한 원소가 두 번째 집합의 두 가지 이상의 원소에 대응할 때

## 함수의 용어

- 정의역(Domain)
- 공역(Codomain)
- 치역(Range)

![image](https://user-images.githubusercontent.com/22423285/128543682-80bd5731-62de-41ae-a722-38a3067eca48.png)

### 프로그래밍 관점에서 함수를 바라보기 
- 입력(Input)
- 출력(Output)

## 함수의 종류(Classes of Function)

- 전사(Surjection) : 공역과 치역이 동일
- 단사(Injection) : 정의역과 공역의 요소가 1:1로 대응
- 전단사(**Bijection**) : 전사 + 단사를 모두 만족
- 일반(General) : 이도저도 아님


## 곱집합(Cartesian Product)
 - 곱집합이란 두 집합의 원소를 순서쌍으로 묶어 구성한 집합
 - (a,b)와 같이 괄호와 콤마를 사용해 원소를 나열하는 방식을 튜플(Tuple)이라고 함
 - 곱집합은 × 기호를 사용해 표현한다.  예) A × B
![image](https://user-images.githubusercontent.com/22423285/128544775-f240cc4e-c753-401a-bd61-868dcbb5ec5e.png)

## 이항 연산을 함수로 해석하기
 - 입력이 두개
 - 정의역 2개를 함수에 넣어 공역을 뽑아내는 것

### 합성함수(Composition)
 - 2개의 함수를 합친 것
![image](https://user-images.githubusercontent.com/22423285/128547456-ec2e5480-579f-4aeb-8b7a-e7ba36114f35.png)
![image](https://user-images.githubusercontent.com/22423285/128547474-d8140331-0015-40b9-9d12-c64063c5fccf.png)
 - g, f 중 f를 먼저 실행
### 항등함수(Identity Function)
![image](https://user-images.githubusercontent.com/22423285/128547947-8930fca4-2020-4e57-9caf-c9cf8c8bae68.png)

### 역함수(Inverse Function)
 - 전단사 함수일 때만 역함수를 보장
![image](https://user-images.githubusercontent.com/22423285/128547958-64221b94-373a-4a48-9bde-214fe542f0a2.png)
 - 어떤 전단사 함수와 그 역함수와의 합성 함수는 항등함수가 된다. 
![image](https://user-images.githubusercontent.com/22423285/128548196-4db0002f-d313-4202-bd81-f93189b04934.png)
 - f º f^{-1} = i
 - g º f = (g º ) ^-1 = f^-1 º g ^ -1




과제
1. 함수와 관련된 기본 용어를 정리하시오.
( 정의역, 공역, 치역 )
 - 정의역 : 첫번째 집합의 모든 원소
 - 공역 : 두번째 집합의 모든 원소
 - 치역 : 두번째 집합 중 첫번째 집합에 대응관계에 있는 요소
 - 
2. 함수의 종류에 관련된 용어를 정리하시오.
( 전사함수, 단사함수, 전단사함수 )
 - 전사함수: 공역과 치역이 동일
 - 단사함수: 정의역과 공역이 1:1로 대응
 - 전단사함수: 전사함수와 단사함수의 조건을 모두 만족
 - 
3. 이항 연산을 곱집합의 개념에서 설명하시오.
 - 곱집합으로 이루어진 2개의 수집합을 정의역으로 연산에 입력하여 공역을 산출해내는 것

4. 전사함수와 단사함수는 역함수를 보장할 수 없는지 그 이유를 설명하시오.
 - 모든 요소가 1:1 대응이 되는 전단사 함수일때만 역함수를 보장
 - 전단사 함수가 아니면 역함수 생성시 정의역에 대응하는 공역이 없을 수 있음

5. 어떤 합성 함수의 역함수는 각 역함수를 거꾸로 합성한 것과 동일함을 그림으로 정리하시오.
 - f º f^{-1} = i
