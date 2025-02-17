---
video_title: 마크다운 MarkDown
channel: 북트레이싱
source: https://youtu.be/rzor1oQyY9U
date: 2025-02-11
tags:
  - 옵시디언
  - Obsidian
  - 마크다운
  - MarkDown
related_notes: "[[Obsidian 사용 예제]]"
---
## 헤더(Header)
# H1 - 노트 제목에 사용됨
## H2 - 본문에서는 이것부터 사용 권장
### H3
#### H4
##### H5
###### H6

## 볼드체(강조)
**강조** : ==\*\*== + 강조 ==\*\*==
강조

## 기울임(이탤릭)
_기울임_  : ==\_== + 기울임 + ==\_==
*기울임* : ==\*== + 기울임 + ==\*==

## 취소선
~~취소선~~ : ==\~~== + 취소선 + ==\~~==
취소선

## 하이라이트(형광펜)
==하이라이트== : ==\=\=== + 하이라이트 + ==\=\===

## 밑줄(언더라인)
<u>밑줄</u> : ==\<u>== + 밑줄 + ==\</u>==

## 리스트(List)
- 리스트 : ==-== + 리스트
+ 리스트 : ==+== + 리스트
* 리스트 : ==\*== + 리스트

위 3개의 리스트가 일직선이 아니므로 하나로 통일해서 사용하는 것을 추천

- 항목 1
	- 서브 항목 a1
		- 서서브 항목 a1
	- 서브 항목 a2
- 항목 2
	- 서브 항목 b1
- 항목 3
	1. 첫 번째
	2. 두 번째

## 구분선
---
==---== 입력 후 엔터키를 누르면 됨

## 인용(Quote)
>인용문 : ==**>**==  + 인용문
>
>이어서 인용

## 체크박스
- [ ] 체크 박스 : ==-==  +  ==\[==  +  ==공백==  +  ==\]== \+ 체크 박스
- [x] 완료

## 링크(임베딩)
[북트레이싱](https://www.booktracing.com)
https://www.booktracing.com

**==[텍스트]\(URL 주소)==**

[북트레이싱 로고](https://booktracing.com/wp-content/uploads/2023/09/%EB%B6%81%ED%8A%B8%EB%9E%98%EC%8B%B1-DARK1.png)

==[북트레이싱 로고]== + ==(https://booktracing.com/wp-content/uploads/2023/09/%EB%B6%81%ED%8A%B8%EB%9E%98%EC%8B%B1-DARK1.png)==


![북트레이싱 로고](https://booktracing.com/wp-content/uploads/2023/09/%EB%B6%81%ED%8A%B8%EB%9E%98%EC%8B%B1-DARK1.png)

==!== + ==[북트레이싱 로고]== + ==(https://booktracing.com/wp-content/uploads/2023/09/%EB%B6%81%ED%8A%B8%EB%9E%98%EC%8B%B1-DARK1.png)==

>
> ==!(느낌표)== 를 텍스트 앞에 입력하면 이미지를 바로 표시할 수 있다.
>

![북트레이싱 로고|300](https://booktracing.com/wp-content/uploads/2023/09/%EB%B6%81%ED%8A%B8%EB%9E%98%EC%8B%B1-DARK1.png)

==!== + ==[북트레이싱 로고|300]== + ==(https://booktracing.com/wp-content/uploads/2023/09/%EB%B6%81%ED%8A%B8%EB%9E%98%EC%8B%B1-DARK1.png)==

>
>==|300== 를 입력하면 이미지 크기를 조절할 수 있다.
>

노트를 링크하려면 ==`[[`== 를 입력하여 선택하면 된다.
[[PARA 노트 정리법]]

노트를 임베디드 하려면 ==느낌표(!)== 를 ==`[[`== 앞에 입력하면 된다.
![[임베디드문서]]

## 코드(Code)
- 인라인 코드: ==\`== + 코드 + ==\`==
	- 예제: \`this.file.basename\`
- 코드 블럭: ==\`\`\`==  + 언어식별자 + 코드 + ==\`\`\`==
	- 예제: 
	\`\`\`tasks
	due before <% tp.date.now("YYYY-MM-DD",1) %>
	not done
	description regex does not match /^$/
	hide due date
	sort by priority
	\`\`\`
- 백슬래시(\\)를 특수기호 앞에 붙이면 특수 기능을 제한한다.
- 복잡한 수식 입력: `$$ E = mc^2 $$`
$$ E = mc^2 $$
- `$$ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$`
$$ x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$
- HTML 사용 예제
```
<span style="color: blue;">파란색</span>
<span style="color: red;">빨간색</span>
<span style="color: #ff6d20;">주황색</span>
```
<span style="color: blue;">파란색</span>
<span style="color: red;">빨간색</span>
<span style="color: #ff6d20;">주황색</span>
