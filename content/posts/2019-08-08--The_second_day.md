---
title: The day 2.
date: "2019-08-08T22:40:32.169Z"
template: "post"
draft: false
slug: "/posts/thesecond/"
category: "WeCode!"
tags:
  - "html"
  - "css"
  - "javascript"
  - "wecode!"
description: "휴"
---

아니 나라는 사람은 이 얼마나 안일한가.. 

![sad.jpg](/media/sad.jpg)


##[css] ; HYPERTEXT MARK UP LANGUAGE.

웹페이지를 만들기 위한 언어. 

웹페이지의 구조이자 구성요소, 그리고 확장자 명(.html)입니다.

브라우저는 HTML파일을 가지고 뭘 어떻게 그려주면 되는지 파악한 후에 웹 페이지를 생성..

큰 틀로, 아래처럼 구성 (꼭 머리 가슴 배st)

*html 파일의 구조는 항상 아래와 같습니다.*

```
<!DOCTYPE html>
==>HTML 파일이라면 제일 첫 줄에 위치하여 html version.이 몇인지 알려주는 역할.(tag아님!)

<html>
==>해당 tag만나면 html의 시작을 인지하고 요소를 그릴 준비를 함

 <head>
==> html태그 다음에는 항상 head태그.
가령, 한글을 사용한다던가 화면에 적절한 비율로 이쁘게 보이게 한다던가 브라우져 탭에 제목을 넣는다는 등.. 

 <body>
==> 화면에 보여져야할, 보여지고 싶은 레이아웃대로 각종 태그들을 사용하는 부분.
tag는 <태그> 본문 </태그>로 구분
tag마다 고유 기능이 있고 콘텐츠 내용과 상황에 맞게 적절하게 붙여주어야...


 </body>

 </head>

 </html>
```

tag + 속성(attribute) ==> 1tag에 여러개 붙임 가능

가령, 

```
<div class 혹은 id 혹은 href 혹은 src="OOO"></div>
```

!중요tag!
```
<a> => 클릭하면 화면이동. 링크등을 써주어서 이동 할때.
<p> => short for 'p'(aragraph). 문단. 줄바꿈 가능!
<h1~h5> => 숫자가 커질수록 크기는 작아짐
<header>
<footer> 
< div> ★★one pick★★ 수준 ¯ࡇ¯ 
=> short for 'd'(ivision). 말 그대로 디비젼별로 묶음, 레이아웃 분리가능, 그리고 각 div마다 class나 id라는 속성 부여해서 css로 꾸밀수 있!
```
