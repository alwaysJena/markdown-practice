<!-- 마크다운 문법이 html 문법으로 변환되어서 동작 -->
# 마크다운 문법 연습

# 제목(Header)


# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)
<!--줄바꿈 = Space 두 번 입력-->
동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산  
대한 사람 대한으로 길이 보전하세  

# 강조(Emphasis)

<!-- _(내용)_ -->
_이텔릭_  
<!-- **(내용)** -->
**두껍게**  

**_이텔릭 + 두껍게_**
  <!-- ~~(내용)~~  -->
~~취소선~~    
<!-- <u>(내용)</u> -->
<u>밑줄</u>

# 목록(List)
<!-- 1.으로 반복해도 화면에선 1,2,3으로 완성됨 
    ol태그 대신 1.만 적어도 순서가 생긴다. 
    들여쓰기로 소목록 생김-->
1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록 
1. 순서가 필요한 목록 

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)
<!-- a태그 -->
<a href="https://google.com" title="구글로 이동">Google</a>
<!-- [타이틀](링크 "title") -->
[Google](https://google.com "구글로 이동")

<!-- a태그는 target 속성이있지만 markdown엔 없다.-->

# 이미지(Image)
<!-- ![]() -->
링크 없는 이미지
![구글 무료이미지](https://postfiles.pstatic.net/MjAyMjA1MjNfMzUg/MDAxNjUzMjk2OTU3NDMw.IvqyLYEswAOkrnv9VS2FYtPvRmdCGEkpS42-0UYk6NQg.9KwvyxOQYVxbe0Fdxxn1o9wRZ_VydC5h4IJsKZZkcIsg.JPEG.rzena95/%ED%95%98%EB%8A%98.jpg?type=w773)  
<!-- 링크 삽입할땐 [] 안에 그대로 넣기 -->
링크 있는 이미지
[![구글 무료이미지](https://postfiles.pstatic.net/MjAyMjA1MjNfMzUg/MDAxNjUzMjk2OTU3NDMw.IvqyLYEswAOkrnv9VS2FYtPvRmdCGEkpS42-0UYk6NQg.9KwvyxOQYVxbe0Fdxxn1o9wRZ_VydC5h4IJsKZZkcIsg.JPEG.rzena95/%ED%95%98%EB%8A%98.jpg?type=w773)  ](http://google.com "구글로 이동")

# 인용문(BlockQuote)
<!--  > 해서 -->
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)
>> 중첩된 인용문  
>>> 중첩된 인용문2

# 인라인(Inline) 코드 강조
<!-- `(내용)` -->
CSS에서 `background` 혹은
`background-image` 속성으로 요소에 배경이미지를
삽입할 수 있습니다.

# 블록(block) 코드 강조
<!-- ```(언어)(내용)``` -->
```html
<!-- html -->
<a href="https://google.com" target="_blank">Google</a>
```

```css
/* css */
..list > li {
    position: absolute;
    top: 40px;
}
```

```javascript
// javascript
function func() {
    var a = 'AAA';
    return a;
}
```

```bash
# 터미널 명령어
$ git commit -m 'Study Markdown'
```
```plaintext
<!-- plaintext -->
순수한 텍스트만 블럭코드로 강조가능
```

# 표(Table)
<!-- --왼쪽정렬, :--: 가운데정렬 , --: 우측정렬 -->
position 속성

값  | 의미 | 기본
--|:--:|--:
static| 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X

# 원시 HTML(Raw HTML)
<!-- Markdown 에서 HTMl언어로 변환되기이전에 직접 HTML 문법을 사용하는 것 -->
동해물과 <u>백두산</u>이 마르고 닳도록<br />
<span style="text-decoration: underline;">하느님</span>이 보우하사 우리나라 만세

<!-- target, Image속성 등 Markdown에 없는 속성을 직접 사용해서 출력할 수 있다 -->

# 수평선(Horizontal Rule)

--- 
***
___