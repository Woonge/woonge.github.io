---
layout: post
title:  "지킬 프로젝트의 구조"
date:   2018-06-03 18:37:00 +0900
categories: jekyll update
---
[웅이의 블로그](https://blog.naver.com/woong17)

지킬 프로젝트의 구조에 대해서 설명합니다.

# Default setting
### _posts
포스팅한 글을 저장합니다.
### _config.yml
블로그의 기본 설정 정보를 담은 파일입니다.
프로젝트를 새로 생성하면 기본적으로 이 파일부터 수정해줘야 합니다.

# Custom setting
지킬의 테마를 오버라이드 하기 위해서는
아래 폴더들을 만들어서 파일을 추가해야합니다.

### _includes
disqus 댓글 플러그인, 구글 분석기 등 각종 플러그인에 대한 정보를 가지고 있습니다. 여기에 사용하고 싶은 플러그인을 include 해놓아야 합니다.
### _layouts
레이아웃의 구조(html)를 수정할 수 있습니다.
### _sass
css 정보가 담겨있습니다.
scss 파일 형식이기 때문에, 일반적인 css 외에
scss를 따로 공부해야 합니다.
### assets
css 파일을 import 할 수 있는 곳입니다.

- - -
이 태그는 뭐지

* * *

?ㅇㅇ

* * *
이제 본격적으로 수정을 해보겠습니다.

_ _ _
수정수정수정수정