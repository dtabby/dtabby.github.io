---
title: "타이틀 부분 - 글 작성 가이드"
categories:
    - jekyll
    - minimal-mistakes
    - 카테고리
tags:
    - jekyll
    - 태그
    - 글작성
data: "2023-03-07 11:00"
---
## 이 부분을 누르면 해당하는 본문의 내용으로 이동

이 부분이 내용 부분.

YFM(YAML Front Matter)에서 정의한 제목을 이중 괄호 구문으로 본문에 추가할 수 있다.

이 글의 제목은 "{{ page.title }}" 이고,
마지막으로 수정된 시간은 "{{ page.last_modified_at }}"이다.

파일 이름의 형식을 반드시 맞춰줘야 한다 - YEAR-MONTH-DAY-title.MARKUP

YEAR : 4자리의 숫자
MONTH, DAY : 2자리의 숫자
title : 포스트 제목 (파일 이름 정도로 인식하면 된다.)
MARKUP : 마크다운 포맷이 인식되는 확장자

ex) 2023-03-07-first-post.md

-------------------------------
이름	    기능

-------------------------------
title	    포스트 제목
categories	포스트 카테고리 정의
tags	    포스트 태그 정의
date	    작성일

-------------------------------

![test01](C:\Users\USER\Documents\GitHub\dtabby-github-blog\images\2023-03-07-first-post\test01.jpg)