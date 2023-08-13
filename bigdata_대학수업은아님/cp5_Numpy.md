## Part 1_파이썬 제어문
if, if-else
while

for n in range(시작값, 끝값)


## Part 2_Numpy 설치 및 배열처리
Numpy : Numerial Python 

라이브러리 목록 확인 방법 -> pip list  
라이브러리 설치 방법 -> pip install numpy  

행렬과 벡터를 곱하는 연산을 잘함!  

```
import numpy as np
import time

n = 1000
a = 5000

x= np.random.rand(n,a)
w= np.random.rand(n,1)
z= np.zeros((1,a))
```

x는 n*a 행렬  
w는 n*1 행렬  
z는 1*a 영행  

```
x = np.array([1,2,3,4])
```
array([1, 2, 3, 4])  
```
np.zeros((2,3))
````
array([[0., 0., 0.],  
       [0., 0., 0.]])  


```
np.arange(10)
```
array([0, 1, 2, 3, 4, 5, 6, 7, 8, 9])
0부터 9까지의 백터를 생성함.  
2,10 인경우, 2부터 9까지의 백터를 생성함    


```
np.linspace(1.0,4.,6)
```
array([1. , 1.6, 2.2, 2.8, 3.4, 4. ])  
(시작값, 끝값, 시작값과 끝값을 일정한 크기로 요소를 만들것인지.)  

```
np.ones(4*10000)
```
array([1., 1., 1., ..., 1., 1., 1.])
4만개의 1차원 배열 생성

```
a = np.array([4,2,9,3])
2**a
```
array([ 16,   4, 512,   8])
2의 4승, 2의 2승, 2의 9승, 2의 3승

그 외에도 sin, log, axis 등 의 기능을 설명함!
numpy 데이터분석에 필수적으로 사용되는  기능들.






## Part 3_Numpy 데이터 생성 및 연