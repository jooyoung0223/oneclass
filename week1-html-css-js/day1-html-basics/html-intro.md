# HTML 기초 개념

## HTML이란?

**HyperText Markup Language**
- HyperText: 링크로 연결된 텍스트
- Markup: 태그로 의미 부여
- Language: 문서 작성 언어

---

## HTML 기본 구조
```html
<!DOCTYPE html>           ← HTML5 문서 선언
<html>                    ← 시작
  <head>                  ← 메타 정보 (눈에 안 보임)
    <title>제목</title>
  </head>
  <body>                  ← 실제 내용 (눈에 보임)
    <h1>안녕하세요</h1>
    <p>본문 내용</p>
  </body>
</html>                   ← 끝
```

---

## 태그 구조

### 기본 형태
```html
<태그>내용</태그>
<h1>제목입니다</h1>

<태그 속성="값">내용</태그>
<a href="https://google.com">구글</a>
```

### 닫는 태그 없는 것 (Self-closing)
```html
<img src="photo.jpg">
<br>
<hr>
<input type="text">
```

---

## 필수 태그 10개

### 1. 제목 (Heading)
```html
<h1>가장 큰 제목</h1>
<h2>중간 제목</h2>
<h3>작은 제목</h3>
<h4>, <h5>, <h6>
```

### 2. 문단 (Paragraph)
```html
<p>이것은 문단입니다.</p>
```

### 3. 링크 (Anchor)
```html
<a href="https://example.com">클릭하세요</a>
```

### 4. 이미지 (Image)
```html
<img src="image.jpg" alt="설명">
```

### 5. 리스트 (List)
```html
<!-- 순서 없는 리스트 -->
<ul>
  <li>항목 1</li>
  <li>항목 2</li>
</ul>

<!-- 순서 있는 리스트 -->
<ol>
  <li>첫째</li>
  <li>둘째</li>
</ol>
```

### 6. 구획 (Division)
```html
<div>
  <h2>섹션 제목</h2>
  <p>내용</p>
</div>
```

### 7. 인라인 컨테이너 (Span)
```html
<p>이것은 <span style="color: red;">빨간</span> 글자</p>
```

### 8. 폼 (Form)
```html
<form>
  <input type="text" placeholder="이름">
  <input type="email" placeholder="이메일">
  <button type="submit">전송</button>
</form>
```

### 9. 버튼 (Button)
```html
<button>클릭</button>
```

### 10. 테이블 (Table)
```html
<table>
  <tr>
    <th>이름</th>
    <th>나이</th>
  </tr>
  <tr>
    <td>철수</td>
    <td>15</td>
  </tr>
</table>
```

---

## OneClass에서 사용할 태그

### 로그인 페이지
```html
<form>
  <input type="email">     ← 이메일 입력
  <input type="password">  ← 비밀번호 입력
  <button>로그인</button>
</form>
```

### 학부모 대시보드
```html
<div class="student-card">
  <h3>김철수</h3>          ← 학생 이름
  <p>영어학원 A</p>        ← 학원 정보
  <ul>                     ← 숙제 리스트
    <li>단어 암기</li>
  </ul>
</div>
```

### 공지사항
```html
<article>
  <h2>공지 제목</h2>
  <p>공지 내용...</p>
  <time>2025-02-14</time>
</article>
```