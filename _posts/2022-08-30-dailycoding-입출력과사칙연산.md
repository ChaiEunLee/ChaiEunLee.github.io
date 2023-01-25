---
title: "[백준] 1. 입출력과 사칙연산"
excerpt: "1단계 전체 문제"

categories:
  - python
tags:
  - [python, tag2]

permalink: /python/baekjoon1/

toc: true
toc_sticky: true

#date = new Date().toLocaleDateString();
#date: document.write(date);
date: 2022-08-31
last_modified_at: 2022-09-01
---

### 1. 2557_Hello World

```python
Hello world
```

### 2. We love kriii

```python
print("강한친구 대한육군 \n강한친구 대한육군")
```
### 3. A+B

```python
A,B = input().split()
print(int(A)+int(B))
```

```python
a,b = map(int, input().split())
print(a+b)
```
### 4. A-B

```python
A,B = input().split()
print(int(A)-int(B))
```
### 5. A*B

```python
A,B = map(int, input().split())
print(A*B)
```
### 6. A/B

```python
A,B = map(int, input().split())
print(A/B)
```
### 7. 사칙연산

```python
A,B = map(int, input().split())
print(A+B)
print(A-B)
print(A*B)
print(A//B)
print(A%B)
```
### 8. ??!

```python
id = input()
print(id+"??!")
```
### 9. 1998년생인 내가 태국에서는 2541년생?!

```python
y = input()
print(int(y)-543)
```

### 10. 킹, 퀸, 룩, 비숍, 나이트, 폰
```python
A = input().split()
print(1 - int(A[0]), 1 - int(A[1]),2 - int(A[2]),2 - int(A[3]),2 - int(A[4]),8 - int(A[5]))
```

### 11. 나머지
```python
#11번 #10430
A,B,C = input().split()
A = int(A)
B = int(B)
C = int(C)

print((A+B)%C)
print(((A%C) + (B%C))%C)
print((A*B)%C)
print(((A%C) * (B%C))%C)
```

### 12.곱셈(2588)
```python
#12번 답 최종 -> 틀림
A = input()
A = int(A)

B = input()
B = list(B)

print(A*B//100)
print(A*((B%100)//10))
print(A*(B%10))
print(A*B)
```

첫째 줄에 (1)의 위치에 들어갈 세자리 자연수가, 둘째 줄에 (2)의 위치에 들어갈 세자리 자연수가 주어진다.
-> 따로따로 input()을 받아야 함.
```python
#12번 답 수정 
A = input()
A = int(A)

B = input()
B2 = B
B = list(B)

print(A*int(B[2]))
print(A*int(B[1]))
print(A*int(B[0]))
print(A*int(B2))
```

### 13. 고양이(10171)
->두가지 방법 모두 가능. 띄어쓰기 주의해야하고 \\ 두번 필요없으면 \한번만 해야함. 
*\ <- 이게 끝에 올때만 \\두번. 앞에 오면 \ 한번만 해도됨.
```python
print("\    /\\")
print(" )  ( ')")
print("(  /  )")
print(" \(__)|")
```

```python
print("\    /\\\n )  ( ')\n(  /  )\n \(__)|")
```
### 14. 개(10172)
```python
#14번 #10172
print("|\_/|")
print("|q p|   /}")
print("( 0 )\"\"\"\\")
print("|\"^\"`    |")
print("||_/=\\\__|")
```

### 15. 새싹(25803)
```python
#15번 print("
print("         ,r'\"7")
print("r`-_   ,'  ,/")
print(" \. \". L_r'")
print("   `~\/")
print("      |")
print("      |")
```
https://gist.github.com/1ee94fe5328efd8313b3fd3d3685d723.git
