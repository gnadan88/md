## **Markdown 기초**
## **1. Markdown이란?**
> 텍스트 기반의 마크업언어로 웹에서 텍스트를 게시하는 데 있어서 표준 문법으로 통용되고 있다. 특수기호와 문자를 이용한 매우 간단한 구조의 문법을 사용하여 코딩하듯이 문서를 작성한다. Notebook, Blog, Github, Notion 등에서 활용된다.  
파일 확장자 : .md

## **2. 기본 문법**
### 2.1. 타이틀
```
#H1
##H2
###H3
####H4
#####H5
######H6
```
> 출력결과

#H1  
##H2  
###H3  
####H4  
#####H5  
######H6

---
### 2.2. 강조
```
**진하게**  
<u>밑줄</u>  
~~취소~~  
_기울임_
```
> 출력결과  

**진하게**  
<u>밑줄</u>  
~~취소~~  
_기울임_  

---
### 2.3. 줄바꿈
```
문장
줄바꿈
안함

문장 (space 2개)
줄바꿈 (space 2개)
함
```
> 출력결과  

문장
줄바꿈
안함  

문장  
줄바꿈  
함  

---
### 2.4. 블럭(인용) 들여쓰기
```
> 블럭 1단계
>> 블럭 2단계
```
> 출력결과  

> 블럭 1단계  
>> 블럭 2단계  
---
### 2.5. Code Block
<pre>
<code>
```python
import something
a = 10
print(a)
if a>10:
  print(a) 
```
</code>
</pre>

> 출력결과  

```python
import something
a = 10
print(a)
if a>10:
  print(a)
```
---
### 2.6. 목록
```
- 사과
- 오렌지
  - 딸기 (tab)
  - 자두 (tab)
- 포도
- 바나나
1. 참외
2. 수박
```
> 출력결과

- 사과
- 오렌지
  - 딸기
  - 자두
- 포도
- 바나나
1. 참외
2. 수박
---
### 2.7. 하이퍼링크
```
[바로가기](http://google.com)  
<http://google.com>
```
> 출력결과

[바로가기](http://google.com)  
<http://google.com>

---
### 2.8. 수평선
```
***
수평선

----
(3개 이상)
```
> 출력결과

***
수평선

----
---
### 2.9. 표
```
|1열|2열|3열|
|:---:|---:|:---:|
|왼쪽|오른쪽|가운|
|정렬하기|정렬하기|정렬하기|
|테스트|테스트|테스트|
```
> 출력결과

|1열|2열|3열|
|:---|---:|:---:|
|왼쪽|오른쪽|가운데|
|정렬하기|정렬하기|정렬하기|
|테스트|테스트|테스트|

---
### 2.10. 이미지
```
![이미지설명문구]()
```
> 출력결과

![이미지설명문구]()

---
### 2.11. 체크박스
```
- [ ] 비어있는 체크박스  
- [x] 체크된 체크박스
```
> 출력 결과

- [ ] 비어있는 체크박스  
- [x] 체크된 체크박스

---
### 2.12. 수식-단독
```
$$
\begin{aligned}
f(x)&=ax^2+bx+c\\
g(x)&=Ax^4
\end{aligned}
$$
```
> 출력결과

$$
\begin{aligned}
f(x)&=ax^2+bx+c\\
g(x)&=Ax^4
\end{aligned}
$$

### 2.12. 수식-문장내
```
문장 내 $\frac{1+s}{s(s+2)}$ 삽입  
$$\frac{1+s}{s(s+2)}$$
```
문장 내 $\frac{1+s}{s(s+2)}$ 삽입  
$$\frac{1+s}{s(s+2)}$$

### 2.12. 수식-특수식
```
$\displaystyle\lim_{s\to\infty}{s^2}$
$\displaystyle\sum_{i=0}^{\infty}{(y_i-t_i)^2}$
```
> 출력 결과

$\displaystyle\lim_{s\to\infty}{s^2}$
$\displaystyle\sum_{i=0}^{\infty}{(y_i-t_i)^2}$

---
### 2.13. 행렬
```
$\begin{matrix}1&2\\3&4\\ \end{matrix}$
$\begin{pmatrix}1&2\\3&4\\ \end{pmatrix}$
$\begin{bmatrix}1&2\\3&4\\ \end{bmatrix}$
$\begin{Bmatrix}1&2\\3&4\\ \end{Bmatrix}$
$\begin{vmatrix}1&2\\3&4\\ \end{vmatrix}$
$\begin{Vmatrix}1&2\\3&4\\ \end{Vmatrix}$
```
> 출력결과

$\begin{matrix}1&2\\3&4\\ \end{matrix}$
$\begin{pmatrix}1&2\\3&4\\ \end{pmatrix}$
$\begin{bmatrix}1&2\\3&4\\ \end{bmatrix}$
$\begin{Bmatrix}1&2\\3&4\\ \end{Bmatrix}$
$\begin{vmatrix}1&2\\3&4\\ \end{vmatrix}$
$\begin{Vmatrix}1&2\\3&4\\ \end{Vmatrix}$
