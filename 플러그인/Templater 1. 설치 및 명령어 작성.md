---
created: 2025-02-15 21:46
tags:
  - 옵시디언
  - Obsidian
  - 플러그인
  - Plugin
  - 템플릿
  - Template
  - Templater
---
# 🌱 Templater 설치 

## 커뮤니티 플러그인 설치

 - Templater 설치
 - 단축키 설정
 
![](/Files/obsidian-options-hotkeys-templater-kor.png)

![](/Files/obsidian-options-hotkeys-toggle-preview-kor.png)

 - 단축키를 누르면 화면에 표시되는 것을 확인할 수 있음
 - Ctrl-Z 누르면 되돌리기로 본 화면 확인할 수 있음

# 🌱 Templater 문법 기본 

## **tp_file**
### 노트 생성 날짜

<% tp.file.creation_date("YYYY-MM-DD HH:mm") %>

<% tp.file.creation_date("YYYY년 MM월 DD일 a H시 m분") %>

### 노트 제목

<% tp.file.title %>

<% tp.file.title.slice(7) %>

<% tp.file.title.slice(0,6) %>

### 노트 저장 폴더

<% tp.file.folder() %>

### 노트의 PC 경로

<% tp.file.path() %>

## **tp_date**

<% tp.date.now("YYYY-MM-DD") %>

<% tp.date.tomorrow("YYYY-MM-DD") %>

<% tp.date.yesterday("YYYY-MM-DD") %>

일<% tp.date.weekday("YYYY-MM-DD", 0) %>

월<% tp.date.weekday("YYYY-MM-DD", 1) %>

화<% tp.date.weekday("YYYY-MM-DD", 2) %>

수<% tp.date.weekday("YYYY-MM-DD", 3) %>

목<% tp.date.weekday("YYYY-MM-DD", 4) %>

금<% tp.date.weekday("YYYY-MM-DD", 5) %>

토<% tp.date.weekday("YYYY-MM-DD", 6) %>

일[[<% tp.date.weekday("YYYY-MM-DD", 0) %>]]

\<\% 와 \%\> 를 대괄호 \[\[   \]\] 로 묶어주면 문서 링크가 만들어지고, 링크를 누르면 문서가 생성된다.


## **tp_system**

### 클립 보드

<% tp.system.clipboard() %>

### 드롭다운 메뉴

- 영화 별점 예제

```
<% tp.system.suggester(
["별5개", "별4개", "별3개", "별2개", "별1개"],
["★★★★★", "★★★★☆", "★★★☆☆", "★★☆☆☆", "★☆☆☆☆"]
) %>
```

### 텍스트 필드

- Daily Note 작성 시 사용 가능

```
<% tp.system.prompt("오늘의 기분은?","") %>
```

---
## Reference
1. https://youtu.be/17tThWhNNGw?si=gceK47deLY1oSj8G
2. https://booktracing.com/%ec%98%b5%ec%8b%9c%eb%94%94%ec%96%b8-%ed%85%9c%ed%94%8c%eb%a6%bf-templater-%ed%94%8c%eb%9f%ac%ea%b7%b8%ec%9d%b8/
 
[https://olait.tistory.com/15](https://olait.tistory.com/15) [이토록 쉬운 옵시디언:티스토리]
