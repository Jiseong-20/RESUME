- 2020732065_정지성
# P3.1
- 상태변수 x1(t) = y(t), x2(t) = $\frac{dy}{dt}$ 라 하자
- 그림의 시스템으로 미분방정식으 세워보면 다음과 같다.
- My″+by′+ky = F(t)
- 상태변수로 1차 미분방정식으로 표현해보면 다음과 같다.
- x2(t) = x′1(t)
- x′2(t) = $\frac{1}{M}F(t)-\frac{k}{M}x1(t)-\frac{b}{M}x2(t)$
- 이를 이용해 상태미분방정식을 구해보면 다음과 같다.
- ![스크린샷 2024-10-16 202700](https://github.com/user-attachments/assets/328eeb0c-226c-46db-9f18-d12018193505)
# P3.3
- 그림의 회로에 대해 미분방정식을 세우면 다음과 같다.
- $\frac{di_L}{dt} = \frac{1}{L}V_1(t) + \frac{1}{L}V_c(t) -\frac{1}{L}V_2(t)$
- $\frac{dV_c}{dt} = -\frac{1}{C}i_c(t) = -\frac{1}{C}i_L(t) - \frac{V_c(t)-V_2(t)}{RC}$
- 이때 상태변수 $x_1(t) = i_L(t), x_2(t) = V_c(t)$ 를 적용하면 상태 미분 방정식은 다음과 같다.
- ![스크린샷 2024-10-16 203130](https://github.com/user-attachments/assets/6cd1e9f8-f8e7-4aa4-9f7c-f69699929965)
# P3.5
- 그림에 주어진 폐루프 시스템의 전달함수 T(s)는 다음과 같다.
- T(s) = $\frac{s+2}{s^3=5s^2-23s+2}$
- 그러므로 상태변수 모델은 다음과 같다.
- ![스크린샷 2024-10-16 203904](https://github.com/user-attachments/assets/c0f2ba43-433c-4fbf-8bf1-716c8f3fe464)
- 전달함수에 의해 위상변수형 블록선도는 다음과 같다.
- 
![p3 5](https://github.com/user-attachments/assets/819b603f-7a7d-435a-b2a1-57137acc0e4d)
# P3.12
- 상태공간모델을 매트랩을 이용해 구해보면 다음과 같다.
- 
![스크린샷 2024-10-16 210304](https://github.com/user-attachments/assets/395ad85b-ea55-444f-af1c-1b441b5437b6)
- 
![스크린샷 2024-10-16 210311](https://github.com/user-attachments/assets/5bf66bec-1e56-4359-9b27-1cb9a24cba3c)
- 그러나 매트랩을 통해 구하면 행렬의 배열이 반대로 나오므로 실제론 다음과 같다.
-
![스크린샷 2024-10-16 210853](https://github.com/user-attachments/assets/5cd2051a-0042-4c94-97ea-32914011a1b7)
- 상태천이 행렬도 마찬가지로 매트랩을 이용해 구해보면 다음과 같다.
- 
![스크린샷 2024-10-16 212716](https://github.com/user-attachments/assets/b8909069-bb90-42f0-a782-85a1f8834e8e)
- 
![스크린샷 2024-10-16 212728](https://github.com/user-attachments/assets/985d491a-2cc5-4e61-b0a8-c09df4c672cb)
# P3.17
- 상태변수 방정식을 x′(t) = Ax(t) + Bu(t), y(t) = Cx(t) + Du(t) 라 할 때 문제에서 행렬 A, B, C, D를 각각 알려주었다.
- 이를 이용해 매트랩으로 전달함수를 구하면 다음과 같다.
- 
![스크린샷 2024-10-16 213942](https://github.com/user-attachments/assets/b4b85740-8b5a-452b-9b19-582a2f5ce5c0)
- 
![스크린샷 2024-10-16 213957](https://github.com/user-attachments/assets/12a2bb9d-6f95-464d-a36f-3a8c4fc2cc3d)
- 그러므로 G(s) = $\frac{-4s+12}{s^3-14s^2+37s+20}$


