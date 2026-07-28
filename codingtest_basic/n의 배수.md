# n의 배수 - 프로그래머스

```python
def solution(num, n):
    if(num % n == 0):
        answer = 1
    else:
        answer = 0
    return answer
```

기본적인 문제
입력받은 값을 n으로 나눈 나머지가 0이면 그 입력받은 수가 n의 배수라는 의미이니 1을 출력
나머지가 0이 아니라면 n의 배수가 아니니 0을 출력하도록하였다
