## Part 1_주피터를 활용한 프로그램 생성

디렉토리 이동 후 cmd에서 jupyter notebook 입력하면 바로 연결되며, 창으로 이동함.

number 데이터 연산자 정수 실수 등..


## Part 2_리스트, 복합리스트, 튜플

날짜, 수학 관련 함수를 사용하려면 라이브러리를 가져와야한다.  
from math import exp, log, sqrt  
import re  
from datetime import date, time, datetime, timedelta  

today = date.today()  

1) 리스트  

리스트의 모든 값을 가져와서 저장할때..  
sum = 0  
score = [22,34,55]  

for x in score:  #score에 있는 모든 값을 가져와라  
  sum += x  
print(sum)  

복합 리스트란? 리스트 안에 다른 리스트가...  
e = [0,1,["py","thon"]]  
print(e[2][0])  
=> py  

2차원 리스트 

2) 튜플: ()을 사용, 수정및삭제가 불가함.

## Part 3_딕셔너리, 자료유형변환 

1) 딕셔너리 : key와 value의 쌍으로 이루어진 데이터.  
   {'name':'kim', birth: '0110'}  
   키 중복 x, 리스트를 키로 사용 x  

   for i in dic.keys():  
    print(i)  

   결과.  
   name  
   birth


   keys() 딕셔너리의 keys 객체를 리턴.
   
  리스트로 변환시... list = list(dic.keys())

2) 집합. sets
   s1 =  set([1,2,3,4])
   s1 =  set([5,6,3,4])

   교집합, 합집합, 차집합 연산을 사용할 수 있다.

   