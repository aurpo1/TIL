# Markdown

## What is Markdown?

마크다운은 텍스트 기반의 마크업언어로, 쉽게 쓰고 읽을 수 있으며 HTML로 변환이 가능하다.

### 마크다운의 장단점

- 장점
  1. 문법이 쉽고 간결하다.
  1. 관리가 쉽다.

- 단점
  1. 표준이 없다.
  1. 모든 HTML 마크업을 대신 할 수는 없다.


---

## Markdown Syntax

### 제목(Header)

Hashtag(**#**)를 사용한다. <br>
Hashtag 다음 띄어쓰기 권장. <br>

_예시_ <br><br>

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

# H1
## H2
### H3
#### H4
##### H5
######H6

### 문장 (Paragraph)

```
This is paragraph.
```

### 줄바꿈

```
띄어쓰기 2번 이상  혹은 <br>
```

### 강조

```
- 언더바(_) : 기울이기
- 별표 2개 (**) : 두껍게
- 물결 2개 (~~) : 취소선
- <u> 태그 : 밑줄
```

_예시_       

_기울이기_ <br>
**두껍게** <br>
**_두껍게 기울이기_** <br>
~~취소선~~ <br>
<u>밑줄</u> <br>

### 목록 (List)

```
- Ordered List : 1.
- Unordered List : -
```

_예시_ <br><br>

1. 1st
1. 2nd
1. 3rd
  1. 3rd - 1
  1. 3rd - 2
<br><br>

- Americano
- Latte
- Tea


### 링크

```
[링크 삽입할 문자](링크)
[링크 삽입할 문자](링크 "마우스 클릭시 뜨는 설명")

HTML에서 제공하는 target 옵션은 제공하지 않는다.
대괄호 안에 이미지 삽입 시 이미지에 링크 걸기 가능하다.
```

_예시_ <br><br>

[Google](https://www.google.co.kr "Google로 이동")


### 이미지

```
![대체 텍스트](이미지 주소)
```

_예시_ <br><br>

![Google icon](https://www.google.com/search?q=%EA%B5%AC%EA%B8%80&sxsrf=APq-WBvevqI5unAUConl225kPoRVKZvMsQ:1649854115533&tbm=isch&source=iu&ictx=1&vet=1&fir=mM5eejaz-bUIsM%252C0UCf55-GTy6fDM%252C%252Fm%252F045c7b&usg=AI4_-kQtNF6bifw2yFn_zXZJH8-lyVrTOw&sa=X&ved=2ahUKEwifyPLDiZH3AhVNCYgKHVEMBdEQ_B16BAg-EAI#imgrc=mM5eejaz-bUIsM)

### 인용문

```
꺽쇠 괄호 + 띄어쓰기
꺽쇠 괄호를 여러개 사용시 중첩 인용 가능
```

_예시_ <br><br>

> 인용1

> 인용1
>> 인용2
>>> 인용3


### 인라인 코드 강조

```
강조하고 싶은 단어에 그레이브(`) 둘러싸기
```

_예시_ <br><br>

나는 오늘 `떡볶이` 먹었다.


### 블록 코드 강조

```
그레이브(`) 세개로 둘러싸기 ``` 강조 내용 ```
사용하는 언어를 명시해주면 문법 강조가 가능하다.
```

_예시_ <br><br>

```
블록 코드 강조
```

``` java
public static void main(String[] args) {
	System.out.println("Hello, World");
    }
}
```

### 표 (Table)

```
행1  |  행2  |  행3
-- | -- | --
사과 | 바나나 | 키위

| 로 구분하고 -- | 로 머리와 구분할 수 있다.
기본은 왼쪽 정렬이나 콜론(:)으로 감싸거나 오른쪽에 위치시키면 가운데 정렬, 오른쪽 정렬이 가능하다.
```

_예시_ <br><br>

이름 | :학년: | 학점:
--|--|--
영희 | 3 | 3.4
철수 | 4 | 4.2
민수 | 4 | 3.9


### 수평선

```
---
___
***
등으로 수평선을 표시할 수 있다.
```
