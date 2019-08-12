---
title: The day 3.
date: "2019-08-09T22:40:32.169Z"
template: "post"
draft: false
slug: "/posts/thethird/"
category: "WeCode!"
tags:
  - "html"
  - "css"
  - "javascript"
  - "wecode!"
description: "어머 금요일이라면서요..?"
---

이게 오늘이 어제 같고 어제가 그제같고 내일이 아마 월요일 같은 기분이랄까요.

세상 시간이 이렇게 금방 지날 수가 없는 데 이상하게 체감은 한달이 지난 것 같은..

빨리빨리 익숙해졌으면 좋겠는 데....:(



##[CSS] ; Cascading Style Sheets 
CSS란 HTML 태그들에 디자인을 입혀주는 것. 언어라고 볼 수 없고 HTML을 이쁘게 이쁘게 꾸며주는 것.

가령, 폰트 사이즈를 바꿀 수 있고 배경색을 입힐 수도 있고 box를 만들 수도 레이아웃을 짤 수도 있는..


css를 작성한 후 HTML에 적용되도록 반영 하는 방법은 3가지가 있습니다.

- 인라인 스타일
태그 style 속성에 직접 작성.

따옴표 안의 "color:red;"부분
편한 대신에 너무 길어지면 가독성이 떨어짐.


```
<h1 style="color: red;">FRONTEND 101</h1>

```

- style 태그 
html 파일 내에 css를 작성할 수 있는 방법. style태그 사이에 css문법을 사용해서 꾸미는 법.
HTML 파일에 작성하면서 css도 작성할 수 있어서 편하고 빠르지만, 이 역시도 유지 보수가 힘둘.



```
<style>
 h2 {
  color: #408090;
 }
</style>
```

- css 파일에 작성:
앞의 두 번은 html 파일에 직접 디자인을 했다면, 3번의 방법은 html 파일과 분리하여 css파일에 따로 작성하는 방법.
가독성 및 유지보수에 좋지만 css파일이 쓰였는지 브라우저에 알려야 하는 링크를 해주는 태그 추가해야함.

```
<link href="index.css" rel="stylesheet" type="text/css" />
```

![css.png](/media/css.png)


*선택자(selector)
rule set의 맨 앞에 있는 HTML 요소 이름. 이것은 꾸밀 요소(들)을 선택.

*선언
color: red와 같은 단일 규칙; 여러분이 꾸미기 원하는 요소의 특성을 명시.

*특성
주어진 HTML 요소를 꾸밀 수 있는 방법. CSS에서, rule 내에서 영향을 줄 특성을 선택.

*특성 값
특성의 오른쪽에, 콜론 뒤에, 주어진 특성을 위한 많은 가능한 결과중 하나를 선택하기 위해 특성 값.
