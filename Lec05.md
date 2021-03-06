#Lec05 삼각함수


## 1. 삼각함수 (Trigonometric function)
 - 직각삼각형(Right-Angled Triangle)의 삼요소

![image](https://user-images.githubusercontent.com/22423285/131535180-35c9f247-2b39-4438-bba6-f2cc715ae5fe.png)

### 삼각비(Trigonometric Ratio)
 - 직각 삼각형을 구성하는 세 요소 중 두 요소에 대한 비의 값

![image](https://user-images.githubusercontent.com/22423285/131535341-a7f92fd7-cdbf-40d7-8214-f4516f46612b.png)

### 삼각함수(Trigonometric Function)
 - 삼각비를 집합의 관점에서 대응 관계로 나타낸 것
 - 정의역 : 실수 집합 R
 - 공역 : [-1,1]

![image](https://user-images.githubusercontent.com/22423285/131535735-6e78adab-6e5c-411a-a13c-820844241780.png)

### 삼각함수와 단위 원

![image](https://user-images.githubusercontent.com/22423285/131536106-b38bfd2a-1aa0-41ff-aa22-492ee6fb7c20.png)

 - 빗변 벡터를 계속 돌렸을 때 아래와 같은 sin, cos값이 얻어진다
![image](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/9c350aab-36e9-46dd-a7a1-d9fec2fa1653/Circle_cos_sin.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210831%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210831T154836Z&X-Amz-Expires=86400&X-Amz-Signature=2315afbb8326262af640c7f14d0cb09ad102e07121efcdef46d67c7ca4bfdf7d&X-Amz-SignedHeaders=host)

 - sin 및 cos 함수 그래프
![image](https://user-images.githubusercontent.com/22423285/131536599-ca4e5f5b-f1a3-42ab-9cf5-3a07a9482a4b.png)

### 코사인과 사인 함수의 성질
 1. 사인 함수와 코사인 함수는 항상 [-1,1] 범위를 일정하게 반복되는 패턴을 가진다.
 2. 사인과 코사인 함수는 2π단위로 반복된다.
 3. 축을 기준으로 좌우를 포갰을 때 **코사인 함수**는 데칼코마니처럼 **좌우 대칭**인 반면, **사인 함수**는 **상하가 반전**된 형태를 가진다.

![image](https://user-images.githubusercontent.com/22423285/131536958-959d37b3-ea69-4c1c-919a-67705c120996.png)

### 탄젠트 함수는 cos90도, cos270도에서 존재하지 않는다.
 - 분모가 0인 경우는 존재 할 수 없기 때문

![image](https://user-images.githubusercontent.com/22423285/131537448-3edacb3b-8aa0-4511-93ec-d4b7da933acf.png)

### 삼각함수의 유용한 공식
 - 직각 삼각형 = 피타고라스의 정리
 - 밑변 값은 cos, 윗변값은 sin이기 때문에 피타고라스의 정리에 의하여 cos^2, sin^2의 합은 항상 1이 된다

![image](https://user-images.githubusercontent.com/22423285/131537638-077fd4a4-29f0-49dd-801b-e1d96ed0c52a.png)

 - 원의 반지름 값이 r인 경우, 원호의 좌표는 (cosθ, sinθ) 벡터에 r배 한 결과가 나온다. 

![image](https://user-images.githubusercontent.com/22423285/131538205-8a2ed566-bc4b-4db1-aeec-e83d09de98f8.png)

 - 단위원(r=1)이 아니더라도 삼각비를 이루기 때문에 위의 공식은 유효하다.

![image](https://user-images.githubusercontent.com/22423285/131538313-0e89f7ba-dad9-4471-b1e6-1324e4c2d991.png)

 - 반지름 r인 원호에 위치한 좌표의 분해
 - x = r · (cosθ)
 - y = r · (sinθ)

![image](https://user-images.githubusercontent.com/22423285/131538353-23369418-e36b-4240-9021-4444dca6b1db.png)

 - ![image](https://user-images.githubusercontent.com/22423285/131538984-3ed1a72b-44d7-4680-a9a9-2546bc18008b.png)
 
![image](https://user-images.githubusercontent.com/22423285/131539002-4c77acdf-7799-4c2e-bc5e-4fe55b6c12e0.png)

#### ※ 표준 기저벡터: 크기가 1인 벡터(1,0), (0, 1)

## 2. 각의 측정

### 각도법(Degree)
 - 원을 360개로 균일하게 나누고 ˚를 사용해 각을 표현.
 - 360도로 나눈 이유: 약수가 많이 나오는 수이기 때문에 원을 쪼개서 계산할 때 유용

### 호도법(Radian)
 -  1˚를 단위로 삼아 원에 관련된 수학을 전개했을 때 불편한 점이 많다
 -   별도의 단위를 정하고 이를 기준으로 원에 대한 수학을 전개

#### 호도법의 원리
 1. 반지름이 1인 반원의 왼쪽 좌표를

![image](https://user-images.githubusercontent.com/22423285/131539773-12fb182f-4c0b-4312-bb65-8a7400cd9bcc.png)

 2. 원점으로 옮기고

![image](https://user-images.githubusercontent.com/22423285/131539841-7ccf5872-a177-46ad-9c56-8ea2f4176651.png)

 3. 원호를 오른쪽으로 쫘악 펼치면?  ⇒ 무리수가 나온다. 이것이 바로 π

![image](https://user-images.githubusercontent.com/22423285/131539925-2fe00cfc-1e42-4f7a-9e34-f54d86255a74.png)

 4. π중에서 길이가 1인 만큼만 거꾸로 되감는다.  ⇒ 이 때 나오는 각 역시 무리수가 된다.  이것이 호도법의 단위인 래디안(rad)이다. 
 - 원호의 길이를 1만큼 되감는다
 - 이때 나오는 각이 1rad이다

![image](https://user-images.githubusercontent.com/22423285/131539995-43e1dc3b-3906-4b80-ac0f-59b3fa656fff.png)

 5. π만큼 되감으면 180˚에 해당하는 반원이 채워진다
  + 이로부터 유도되는 호도법과 각도법의 관계는 다음과 같다.
 
![image](https://user-images.githubusercontent.com/22423285/131540694-883b52ae-b107-4173-9a5d-09d6b76665e2.png)

  + 자주 사용하는 각도에 대응하는 호도값

![image](https://user-images.githubusercontent.com/22423285/131540744-de655c04-b1b9-4527-959c-4f9a0fcd5ae3.png)


## 3. 벡터의 회전(Rotation of Vector)
 - 표준 기저벡터를 사용한 실벡터공간 R²의 원소 (x,y)의 생성 방법

![image](https://user-images.githubusercontent.com/22423285/131541502-775b83bd-3ff7-42ff-81ad-4d82fa396997.png)

 -  표준기저벡터로 이루어진 벡터 공간 R²에서 공간 자체가 변할 경우(회전) 
    모든 벡터는 표준 기저벡터의 x와 y의 곱으로 나타낼 수 있으므로, 
    표준기저벡터를 변경시킴으로써 표현 할 수 있다
  - 직교상태 유지
  - 방향을 유지

![image](https://user-images.githubusercontent.com/22423285/131542308-92df338d-3177-4a17-a132-e7f0dd913d9e.png)

![image](https://user-images.githubusercontent.com/22423285/131542338-b5eb429b-53fd-41b2-86e3-9a28f6189c1d.png)

## 삼각함수의 역함수(Inverse trigonometric functions)
 - 삼각함수의 그래프

![image](https://user-images.githubusercontent.com/22423285/131542443-2ba3f5a1-f07b-4a7d-8583-2b092b5795d3.png)

 - 역함수가 존재하기 위해서는 해당함수는 전단사함수여야 한다. 
 - 하지만 sin, cos, tan는 전단사함수가 아니다. 왜냐하면 단사가 아니기 때문이다. 
 - 따라서 sin, cos, tan함수를 단사함수로 만들기 위해 의도적으로 정의역의 값을 제한시키자.
 - 그렇다면 전단사함수가 되어 역함수가 존재할 수 있다.
 - sin함수의 경우 -90˚ ~ 90˚
 - cos함수의 경우 양의 방향으로 0˚ ~ 180˚
 - tan함수의 경우 -90˚ < 범위 < 90˚
![image](https://user-images.githubusercontent.com/22423285/131543120-843c8e28-6318-4c3c-808e-b10f32be01f2.png)

 - 위의 범위에서 정의한 역함수를 아크사인,아크코사인,아크탄젠트 함수라고도 부른다. 

![image](https://user-images.githubusercontent.com/22423285/131543345-491e69ef-4205-40bf-877d-34531bba00ba.png)

### 삼각함수의 역함수

![image](https://user-images.githubusercontent.com/22423285/131543425-14b1ef0a-255f-4027-871f-f513c30ee702.png)

###  역함수가 다루는 각의 범위

![image](https://user-images.githubusercontent.com/22423285/131543481-52c8d76b-b7ca-4ca8-9b1b-f621df845f88.png)

- x축을 0으로 본다

![image](https://user-images.githubusercontent.com/22423285/131543506-87299c2d-c649-4697-bd3e-b00e6c847219.png)

### 아크탄젠트 함수의 활용
 - 두 삼각형은 다른 삼각형이고 다른 각을 가지지만 탄젠트 값은 동일하다. 

![image](https://user-images.githubusercontent.com/22423285/131543778-fdf9dfe7-4807-464c-b198-c4f343724abc.png)

![image](https://user-images.githubusercontent.com/22423285/131543880-66525fb5-991d-4517-bdb5-f0594a63e471.png)

## 극 좌표계(Polar Coordinate)
 - 모든 평면을 원으로 구성을 하고
 - 그 값을 (r, θ)로 표시, 반지름, 각도)

![image](https://user-images.githubusercontent.com/22423285/131544683-12477b93-6eae-4569-96de-f84cc84c3ad9.png)

### 데카르트 좌표계에서 극 좌표계로 변환하기

![image](https://user-images.githubusercontent.com/22423285/131544849-9aff27fa-6adb-496a-be48-047518163fd5.png)

### 극 좌표계에서 데카르트 좌표계로 변환하기

![image](https://user-images.githubusercontent.com/22423285/131544881-e771de99-664b-4f0e-9ab4-935e13e08422.png)

### 극 좌표계의 활용 예시
 - 반지름 r의 크기에 비례해서 중심에서 멀어질 수록 회전을 더 많이 주고 싶은 경우

![image](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/aabf7f9b-f737-4602-a81a-55597e3c48d5/polarcoordinate.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAT73L2G45O3KS52Y5%2F20210831%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20210831T165849Z&X-Amz-Expires=86400&X-Amz-Signature=3a44466b26e4576e082b7e5c3ac9b4b44e58c26c2cc0a1f92fe1f3aa5b62fda2&X-Amz-SignedHeaders=host)


과제
1. 삼각비와 삼각함수의 차이를 정리하시오.
 - Trigonometric Ratio는 직각 삼각형을 이루는 세 요소 중 두 요소에 대한 비를 나타낸 것이고,
 - Trigonometric Function은 삼각비를 집합의 관점에서 대응관계로 나타낸 것이다.
 - Trigonometric Function의 정의역은 실수집합 R이고, 공역은 [-1,1]이다

2. 단위원을 기반으로 삼각함수의 응용 방법과 공식을 아는만큼 정리하시오.
 - cos^2, sin^2의 합은 항상 1
 - tanθ = sinθ / cosθ
 - x = cosθ
 - y = sinθ

3. 각도법과 호도법의 차이를 설명하고, 둘의 변환식을 정리하시오.
 - Degree: 원을 360으로 나누고 ˚를 사용하여 각을 표현
 - 반지름이 1이고, 원호의 길이가 1일 경우 그 각을 1rad라고 한다.
 - 180˚ = π(rad)

