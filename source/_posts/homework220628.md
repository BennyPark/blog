---
title: "homework220628"
output:  
    html_document:    
        toc: true
        toc_float: true
        keep_md: true
        categories: homework
date: '2022-06-28'
---
# HOMEWORK PYTHON
<!-- more -->

```python
def hello(): #hello 함수를 만듦
  print("hello, world!") 
hello()
```

    hello, world!
    


```python
def hello():
  pass #빈함수 만들기
```


```python
def add(a,b):
  """ 이 함수는 a와 b를 더한 뒤 결과를 반환하는 함수다. """
  print(a+b)
add(10,20)
```

    30
    30
     이 함수는 a와 b를 더한 뒤 결과를 반환하는 함수다. 
    


```python
def add(a,b):
  """ 이 함수는 a와 b를 더한 뒤 결과를 반환하는 함수다. """
  return a+b

x=add(5,10)
print(x)

print(add.__doc__)
```

     이 함수는 a와 b를 더한 뒤 결과를 반환하는 함수다. 
    


```python
def add(a,b):
  return a+b
x=add(4,6)
x
```




    10




```python
def one():
  return 1

x= one()
x
```




    1




```python
def not_ten(a):
  if a == 10:
    return
  print(a,"입니다.", sep='')

not_ten(5)
```

    5입니다.
    


```python
def add_sub(a,b):
  return a+b, a-b

""" add_sub는 더하기와 빼기의 값이 동시에 출력된다. """

x, y = add_sub(10,20) #결과값을 x와 y에 저장합니다. 
print(x) 
print(y)
```

    30
    -10
    


```python
def one_two():
  return(1,2)
1,2
```




    (1, 2)




```python
def one_two():
  return [1,2]

x,y= one_two()
print(x, y)
```

    1 2
    


```python
def mul(a,b):
  c= a*b
  return c


def add(a,b):
  c= a+b
  print(c)
  d=mul(a,b)
  print(d)

x=10
y=20
add(x,y)
```

    200
    


```python
def print_num(a,b,c):
  print(a)
  print(b)
  print(c)

print_num(10,20,30)

x = [10,20,30] 

print_num(*x) #리스트(튜플) 앞에 *를 붙이면 언패킹(unpacking)
```

    10
    20
    30
    10
    20
    30
    

## 참조
- 파이썬 코딩도장, 29.1 Hello, world! 출력 함수 만들기 
  + 주소 : https://dojang.io/mod/page/view.php?id=2337


```python

```
