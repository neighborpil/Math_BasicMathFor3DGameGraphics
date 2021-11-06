#Lec05


## 1. 역행렬(Inverse Matrix)

### 항등 행렬(Identity Matrix)

선형 변환의 결과가 변함없는 행렬

두 표준 기저벡터 $e_1, e_2$의 값이 동일하게 유지되는 선형변환을 의미

$$I=\begin{bmatrix}1 & 0 \\ 0 & 1 \end{bmatrix}$$

$$\begin{bmatrix}a & b\\c & d \end{bmatrix}\begin{bmatrix}1 & 0\\0 & 1 \end{bmatrix}=\begin{bmatrix}a & b\\c & d \end{bmatrix}$$

### 역행렬이란?

선형 변환된 결과를 거꾸로 돌려주는 선형 변환.  이를 합성한 결과는 항등 변환이 된다. 

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/aa3194a1-dc0e-43e1-a4d1-1e8a8f9745a7/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/aa3194a1-dc0e-43e1-a4d1-1e8a8f9745a7/Untitled.png)

$$f^{-1}\circ f=i\\
A^{-1}\cdot A=I$$

## 2. 역행렬의 계산 방법

### 행렬식(Determinant)

$$A = \begin{bmatrix} a & b\\c & d \end{bmatrix}, det(A) = ad-bc$$

아래 연립방정식의 해는 존재하는가?

$$2x + y =5 \\ 
x + 0.5y = 4$$

위 연립방정식의 행렬식은 $2\cdot 0.5 - 1\cdot 1=0$이 나오고 이는 해가 없음을 의미한다. 

어째서인가? 

위 식을 행렬로 나타내면 다음과 같다.

$$\begin{bmatrix}2 & 1 \\ 1 & 0.5 \end{bmatrix}\begin{bmatrix}x \\ y \end{bmatrix}=\begin{bmatrix}5 \\ 4 \end{bmatrix}$$

위 변환을 분석하면 표준기저벡터 $e_1, e_2$는 각각 $(2,1), (1,0.5)$로 변환되었는데, 이 둘은 같은 기울기를 가지고 있음을 알 수 있다.  따라서 두 기저 벡터가 선형 독립에서 선형 의존 관계가 되었다.

이를 그림으로 나타내면 다음과 같다. 

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3b05a299-2c86-4367-aec9-63b51d7e5449/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/3b05a299-2c86-4367-aec9-63b51d7e5449/Untitled.png)

위의 경우 선형변환의 결과로 2차원 평면이 1차원 직선으로 소멸되었기에 1차원에서 2차원으로 돌아가는 역행렬은 존재하지 않는다.

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a209f0e0-420c-4c9a-b94e-5cf454db7ccc/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/a209f0e0-420c-4c9a-b94e-5cf454db7ccc/Untitled.png)

그렇다면 어째서 $ad-bc$가 0이면 차원이 소멸되는 것인가?

두 벡터가 만드는 평행사변형의 넓이를 확인해보자. 

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cfb64343-31eb-4777-80a4-94c90dd26dee/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/cfb64343-31eb-4777-80a4-94c90dd26dee/Untitled.png)

$$(a+b)(c+d)-2bc-bd-ac=ac+bd+bc+bd-2bc-bd-ac=ad-bc$$

전체 사각형에서 남은 부피를 빼면 넓이 값은 $ad-bc$임을 알 수 있다. 따라서 해당 넓이가 0이라면 두 벡터가 동일한 기울기로 겹쳐있게됨을 알 수 있다. 이는 선형 의존임을 의미한다. 

만약 역행렬이 존재한다면 어떻게 되는가? 

다음과 같은 변환을 생각하면 평면이 행렬식 값만큼 달라짐을 알 수 있다.

그렇다면 원상 복구하기 위해서는 달라진 크기의 역수만큼 변해야 한다.    

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/58e047d8-bf2e-4ac6-9980-f0409a07814f/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/58e047d8-bf2e-4ac6-9980-f0409a07814f/Untitled.png)

### 역행렬의 활용

연립방정식의 해를 구할 때 유용하게 사용된다. 

아래 식에서 선형 변환 $A$와 변환된 벡터 $v'$만 알고 있는 경우 $A$의 역행렬을 구할 수 있다면 양변에 곱해 변환하기 전의 벡터 $v$를 구할 수 있다. 

$$A\cdot v=v' \\
A^{-1}\cdot A\cdot v=A^{-1}\cdot v' \\
v=A^{-1}v'$$

임의의 정방행렬의 역행렬을 구하기 위한 방법은 여러가지가 있는데 대표적으로 다음의 방법들이 존재한다.  

- 가우스 소거법 ( Gaussian elimination )
- 크라메르 공식 ( Cramer's rule)

하지만 우리가 사용하는 대표적인 선형 변환들은 위의 방법을 사용하지 않고 직관적으로 역행렬을 구하는 것이 가능하다. 

### 크기 행렬의 역행렬

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6964b73a-4ab5-4368-b078-b786a7865bcf/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/6964b73a-4ab5-4368-b078-b786a7865bcf/Untitled.png)

$$\begin{bmatrix} 1\over a & 0\\0 & 1\over b \end{bmatrix}$$

### 밀기 행렬의 역행렬

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ae44ef80-4d76-4c0f-88a6-ef0fc42e69a1/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ae44ef80-4d76-4c0f-88a6-ef0fc42e69a1/Untitled.png)

$$\begin{bmatrix} 1 & -a\\0 & 1 \end{bmatrix}$$

### 회전 행렬의 역행렬

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7f340b82-0134-498c-a96c-93c153ffc8f4/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/7f340b82-0134-498c-a96c-93c153ffc8f4/Untitled.png)

$$R_\theta =\begin{bmatrix} cos\theta & -sin\theta\\ sin\theta & cos\theta \end{bmatrix} $$

$$R_{(-\theta)} =\begin{bmatrix} cos(-\theta) & -sin(-\theta)\\sin(-\theta) & cos(-\theta) \end{bmatrix}=\begin{bmatrix} cos(\theta) & sin(\theta)\\-sin(\theta) & cos(\theta) \end{bmatrix}$$

위 결과에서 $R_\theta$ 와 $R_{(-\theta)}$는 서로 전치 관계를 이룬다. 

따라서 회전 행렬의 역행렬은 전치 행렬이 됨을 알 수 있다.

$$R_{(-\theta)}=R_\theta^{-1}=R_\theta^T$$

과제

1. 항등행렬과 역행렬이 가지는 변환의 의미를 시각적으로 정리하시오.
2. 행렬식이 0이면 변환 과정에서 어떤 문제가 발생하는지 정리하시오.
3. 크기 행렬, 밀기 행렬, 회전 행렬의 역행렬에 대해 정리하시오.
4. 회전 행렬의 역행렬은 어째서 전치행렬이 되는지 정리하시오.
