# Game Math
1. 공간에 대한 수학
2. 물체에 대한 수학
3. 회전에 대한 수

### 공리(Axiom)
- 증명할 필요가 없는 자명한 명제


## 공간에 대한 수학
### 벡터공간(Vector Space)
- 게임이 사용하는 가상 공간의 본질 Game Math
1. 공간에 대한 수학
2. 물체에 대한 수학
3. 회전에 대한 수

### 공리(Axiom)
- 증명할 필요가 없는 자명한 명제


## 공간에 대한 수학
### 벡터공간(Vector Space)
- 게임이 사용하는 가상 공간의 본질
- 수의 체계를 기반으로 한 다차원의 데이터
### 물리학에서의 벡터와 스칼라
- 벡터: 크기와 방향을 가진 대상
- 스칼라: 크기만 있는 물리량
### 수학에서의 벡터와 스칼라
- 벡터: 벡터 공간의 원소
- 스칼라: 체 집합의 원소
### 선형 변환(Linear Transformation)
- 선형성을 사진 변환
### 렌더링 파이프라인(Rendering Pipeline)
- 3차원 상의 물체를 2차원의 컴퓨터 화에 실제적으로 표현하기 위한 과정
- 3차원으로 만들어진 모델을 2차원에 투영하는 렌더링 과정의 프로세스를 자세하게 표현한 것
  
![image](https://github.com/user-attachments/assets/9ce26ff3-6efa-4940-8604-ba102121eb78)
### 행렬(Matrix)
- 선형 변환을 수행하는 도구
- 컴퓨터가 하여금 가상 공간을 빠르게 변화시키도록 지시하는 명령어
  
![image](https://github.com/user-attachments/assets/c2d97f6b-6944-4e5a-99dd-bf56c5cc9e52)
### 평면의 방정식
- ax + by + cz + d = 0
### 절두체(Frustum)
- 시야에 보이는 영역을 표현한 입체
- 프로그램의 부하를 줄이기 위해 컬링을 해야한다.
  
![image](https://github.com/user-attachments/assets/a61ef411-a1ad-4d46-a490-c60b29c395e1)

## 물체에 대한 수학
- 게임에서 사용하는 가상 공간의 체계와 물체를 구성하는데 사용하는 수학
### 벡터 공간
- 어떤 대상의 성질을 표현하는데 사용되는 데이터
- 벡터 공간의 공간과 현실 세계의 공간은 다른 개념이다.

### 벡터 공간의 공간과 현실 세계의 공간은 다른 개념을 가질지라도 캐릭터를 조종해서 탐험할 수 있는 현실 세계와 유사한 가상 공간을 어떻게 만들어야 할까?
- 공간의 차원을 추가한다.
- 2차원 물체의 표현: 2차원
- 이동의 구현: 1차원
=> 총 3차원의 공간을 활용한다.

![image](https://github.com/user-attachments/assets/5ea491a3-81c7-4267-9b41-032088e4a80e)
### 3차원의 물체를 다루려면 어떻게 해야할까? 
- 3차원 물체의 표현: 3차원
- 이동의 구현: 1차원
=> 총 4차원의 공간을 활용한다.
### 수학의 벡터는 게임을 구현하기 위해 점 또는 (이동)벡터 중 하나로 사용된다.
- 게임을 제작하는 바탕에서 벡터 공간을 크게 만들어 이를 둘로 쪼개서 물체를 구성하는 부분 공간과 이동을 구성하는 부분 공간의 두 가지로 나누어 관리하는 시스템이 기반에 구축되어 있다.
### 게임은 벡터 공간을 다음과 같이 분리해 관리한다.
1. 물체를 표현하는 공간: 아핀공간
2. 이동을 위한 공간th
1. 공간에 대한 수학
2. 물체에 대한 수학
3. 회전에 대한 수

### 공리(Axiom)
- 증명할 필요가 없는 자명한 명제


## 공간에 대한 수학
### 벡터공간(Vector Space)
- 게임이 사용하는 가상 공간의 본질 Game Math
1. 공간에 대한 수학
2. 물체에 대한 수학
3. 회전에 대한 수

### 공리(Axiom)
- 증명할 필요가 없는 자명한 명제


## 공간에 대한 수학
### 벡터공간(Vector Space)
- 게임이 사용하는 가상 공간의 본질
- 수의 체계를 기반으로 한 다차원의 데이터
### 물리학에서의 벡터와 스칼라
- 벡터: 크기와 방향을 가진 대상
- 스칼라: 크기만 있는 물리량
### 수학에서의 벡터와 스칼라
- 벡터: 벡터 공간의 원소
- 스칼라: 체 집합의 원소
### 선형 변환(Linear Transformation)
- 선형성을 사진 변환
### 렌더링 파이프라인(Rendering Pipeline)
- 3차원 상의 물체를 2차원의 컴퓨터 화에 실제적으로 표현하기 위한 과정
- 3차원으로 만들어진 모델을 2차원에 투영하는 렌더링 과정의 프로세스를 자세하게 표현한 것
  
![image](https://github.com/user-attachments/assets/9ce26ff3-6efa-4940-8604-ba102121eb78)
### 행렬(Matrix)
- 선형 변환을 수행하는 도구
- 컴퓨터가 하여금 가상 공간을 빠르게 변화시키도록 지시하는 명령어
  
![image](https://github.com/user-attachments/assets/c2d97f6b-6944-4e5a-99dd-bf56c5cc9e52)
### 평면의 방정식
- ax + by + cz + d = 0
### 절두체(Frustum)
- 시야에 보이는 영역을 표현한 입체
- 프로그램의 부하를 줄이기 위해 컬링을 해야한다.
  
![image](https://github.com/user-attachments/assets/a61ef411-a1ad-4d46-a490-c60b29c395e1)

## 물체에 대한 수학
- 게임에서 사용하는 가상 공간의 체계와 물체를 구성하는데 사용하는 수학
### 벡터 공간
- 어떤 대상의 성질을 표현하는데 사용되는 데이터
- 벡터 공간의 공간과 현실 세계의 공간은 다른 개념이다.

### 벡터 공간의 공간과 현실 세계의 공간은 다른 개념을 가질지라도 캐릭터를 조종해서 탐험할 수 있는 현실 세계와 유사한 가상 공간을 어떻게 만들어야 할까?
- 공간의 차원을 추가한다.
- 2차원 물체의 표현: 2차원
- 이동의 구현: 1차원
=> 총 3차원의 공간을 활용한다.

![image](https://github.com/user-attachments/assets/5ea491a3-81c7-4267-9b41-032088e4a80e)
### 3차원의 물체를 다루려면 어떻게 해야할까? 
- 3차원 물체의 표현: 3차원
- 이동의 구현: 1차원
=> 총 4차원의 공간을 활용한다.
- 예를 들어, 현실 세계에서 3차원 공간의 물체를 바라볼 때, 가상 공간은 4차원으로 구성되어 있다.
### 수학의 벡터는 게임을 구현하기 위해 점 또는 (이동)벡터 중 하나로 사용된다.
- 게임을 제작하는 바탕에서 벡터 공간을 크게 만들어 이를 둘로 쪼개서 물체를 구성하는 부분 공간과 이동을 구성하는 부분 공간의 두 가지로 나누어 관리하는 시스템이 기반에 구축되어 있다.
### 게임은 벡터 공간을 다음과 같이 분리해 관리한다.
1. 물체를 표현하는 공간: 아핀공간
2. 이동을 위한 공간

### 아핀 공간
- 원점 없이 거리와 방향만 있는 공간
- 벡터 공간의 부분 공간인 아핀 공간에 속한 벡터
- 물체를 표현하는 데 사용되고, 부분짓기 위해 점을 사용한다.
- 따라서, 가상 공간의 물체는 점으로 구성되어 있다고 할 수 있다.
### 이동을 위한 공간
- 이동 벡터는 물리적 벡터에 해당된다.
- 아핀 공간의 점을 사용해서 물체를 만들면 임 물체는 이동 벡터가 가지고 있는 크기와 방향을 사용하여 점을 이동시키도록 구현되어 있다.
![image](https://github.com/user-attachments/assets/c9ed1dda-86bd-4d49-97ca-b13647652e20)

- P₁ + v = P₂
- 점 P₁에 이동 벡터를 더해주면 그 힘에 따라 다른 점인 P₂에 대응하게 된다.
- 따라서, 두 점 사이에는 하나의 벡터가 대응된다고 할 수 있다.
- ↗️이동 벡터를 구하는 방법: v = P₂ - P₁
- 점으로 구성된 아핀 공간과 이동 벡터로 구성된 이 부분 공간은 서로 분리된 공간이다.
- 하지만, 두 점의 뺄셈을 통해 다른 공간의 데이터가 서로 교환될 수 있다는 것을 이해해야 한다.
![image](https://github.com/user-attachments/assets/5e8df23f-bd71-4595-96da-67ba93750611)



