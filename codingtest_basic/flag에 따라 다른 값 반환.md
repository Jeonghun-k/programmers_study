# 플레그에 따라 다른 값 반환 - 프로그래머스

*문제*
```
두 정수 a, b와 boolean 변수 flag가 매개변수로 주어질 때,
flag가 true면 a + b를 false면 a - b를 return 하는 solution 함수를 작성해 주세요.
```
---
*코드*
```python
def solution(a, b, flag):
    if(flag == True):
        answer = a + b
    else:
        answer = a-b
    
    return answer
```
---
*설명*  
flag는 불리언 변수로 `True` or `False`를 담는다.  

조건문으로 flag가 True일 경우 a + b를 하고
아닐 경우 a - b를 하도록 잣겅하였다
