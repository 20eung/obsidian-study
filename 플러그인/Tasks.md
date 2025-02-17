---
created: 2025-02-15 21:34
tags:
  - 옵시디언
  - Obsidian
  - 플러그인
  - Plugin
---
# 🌱 Tasks 필터링 구문

### 완료되지 않은 일 
not done 

### 완료된 일 
- has done date 
- no done date 
- done (on|befor|after) \<date>|\<data range> 

### 정렬 
- sort by priority 
- sort by due 
- sort by start 
- sort by scheduled 
- sort by done 
- sort by description 
- sort by path 
- sort by recurring 
- sort by tag 

### 숨김 
- hide start date 
- hide due date 
- hide edit button 
- hide backlink 

### 마감 기한 
- due 2023-12-25 
- due before yesterday 
- due today 
- due after 3 days ago 
- due in this week 
- due after this month 
- due or or before next year 
- due in 2023-Www(ww에는 주, 2자리 숫자) 
- due in 2023-10 (10월) 
- due (before|after|in) \<data range> 

### priority 
- priority is (above|below|not) (lowest|low|none|medium|high|highest) 

## Custom filter 

### 비어있는 필드 

#### 비어있는 작업 찾기 
- description regex matches /^$/ 

#### 비어있는 작업 제외하기 
- description regex does not match /^$/ 

### 폴더 필터링 

#### 현재의 폴더에 들어있는 할 일 
- folder includes {{query.file.folder}} 

#### 폴더를 포함 
- filter by function task.file.folder.includes("폴더 이름")

---
## Reference
1. https://youtu.be/Qok3EljgmbA?si=5-CjpnIyBcR26BHK
2. https://booktracing.com/tasks-%ed%95%84%ed%84%b0%eb%a7%81-%ea%b5%ac%eb%ac%b8/
 
[https://olait.tistory.com/15](https://olait.tistory.com/15) [이토록 쉬운 옵시디언:티스토리]