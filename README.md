# 제목(Header)

# 제목 1

## 제목 2

### 제목 3

<!-- h tag (1~6) -->

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

<!-- p tag -->

# 줄바꿈(Line Breaks)

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세<br/>
무궁화 삼천리 화려 강산  
대한 사람 대한으로 길이 보전하세

<!-- 띄어쓰기 2번 or br tag -->

# 강조(Emphasis)

_이텔릭_  
**두껍게**  
**_이텔릭 + 두껍게_**  
~~취소선~~  
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
   1. 순서가 필요한 목록
   1. 순서가 필요한 목록
1. 순서가 필요한 목록
<!-- li tag 대신 사용하는 느낌? -->

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
  - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Linkss)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="NAVER로 이동!">NAVER</a>

[NAVER](https://naver.com "NAVER로 이동!")

<a href="https://naver.com" title="NAVER로 이동!"
targer="_blank">NAVER</a>

<!-- 새 탭에 열기 -->
<!-- 마크다운에서는 a 태그로 작성해야 새 탭 적용 가능-->

# 이미지(Images)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

<!-- 중첩시키기 -->

> 인용문을 작성하세요!
>
> > 중첩된 인용문
> >
> > > 중중첩된 인용문 1
> > > 중중첩된 인용문 2
> > > 중중첩된 인용문 3

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

<!-- 코드 강조 -->

# 블록(block) 코드 강조

```html
<a href="https://www.google.co.kr/" target="_blank">GOOGLE</a>
```

<!-- html 코드의 언어를 명시한 것임 -->

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```javascript
function func() {
  var a = "AAA";
  return a;
}
```

```bash
$ git commit -m 'Study Markdown'
```

<!-- 터미널에 입력하는 것 -->

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

<!-- 개발코드 아닌 것 -->

# 표(Table)

position 속성

| 값        |       의미        | 기본값 |
| --------- | :---------------: | -----: |
| static    |     기준 없음     |      O |
| relative  |     요소 자신     |      X |
| absoslute | 위치 상 부모 요소 |      X |
| fixed     |      뷰포트       |      X |

<!-- 콜론 기호로 정렬 지정 -->

# 원시 HTML(Raw HTML)

마크다운이 html로 번역되기 전에 개발자가 먼저 html 언어로 작성

동해물과 <span style="text-decoration: underline;">백두산</span>이 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<!-- 속성 추가도 가능(원래 html 에서는 밑줄 u 잘 사용 안 함. 대신에 css에서 꾸며줌) -->

<a href="https://naver.com" title="NAVER로 이동!" target="_blank">NAVER</a>

<!-- target -->

---

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY">
<!-- width -->

# 수평선(Horizontal line)

---

---

---
