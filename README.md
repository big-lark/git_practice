# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5
###### 제목6

# 문장(paragraph)
동해물과 백두산이 마르고 닳도록 하느님이 보우하사 우리나라 만세

# 줄바꿈(line Breaks)
동해물과 백두산이 마르고 닳도록<br/> 
하느님이 보우하사 우리나라 만세

줄바꿈: 띄어쓰기 두번 or <br/>

# 강조(Emphasis)
_이텔릭_
**두껍게**
~~취속선~~
<u>밑줄</u>

# 목록(List)
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
		1. 순서가 필요한 목록 (들여쓰기 두번)
		1. 순서가 필요한 목록
		1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록 
		- 순서가 필요하지 않은 목록 (들여쓰기 두번)
		- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Link)
<a href="https://www.google/com">GOOGLE</a>
[GOOGLE](https://www.google/com)

<a href="https://www.naver/com" title="NAVER로 이동!">NAVER</a>
[NAVER](https://www.naver/com "네이버로 이동 !")

# 이미지(image)
![]()
![대체택스트](imageurl)

[![대체택스트](imageurl)](링크주소)
= 이미지를 클릭하면 링크주소로 이동

# 인용문(BlockQuote)
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1
>>> 중중첩된 인용문 2
?>> 중중첩된 인용문 3

# 인라인(liline) 코드 강조
CSS에서 `background` 혹은
`background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다

# 블록(block) 코드 강조

```html
<a href="https://www.naver/com" target="_blank">NAVER</a>
```

```css
 .list > li {
	position: absolute;
	top: 40px;
}
```

```javascript
	function func() {
	var a = 'AAA';
	return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

```plaintext (블럭코드작성)
	동해물과 백두산이 마르고 닳도록
	하느님이 보우하사 우리나라 만세
```

# 표(table)

값 | 의미 | 기본값
--|--|--
static | 기준없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

값 | 의미 | 기본값
--|:--:|--:
static | 기준없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML) 
### 마크다운 문법안에서 실제 HTML 문법을 사용하는 것
---
	동해물과 <u>백두산이</u> 
	<span style="text-decoration: underline;">마르고<span> 닳도록 <br/> 
	하느님이 보우하사 우리나라 만세
---
# 수평선
---
***
___