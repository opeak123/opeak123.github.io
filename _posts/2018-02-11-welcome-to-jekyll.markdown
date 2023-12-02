---
layout: post
title:  "C언어 콘솔게임 Episode 1!"
date:   2023-12-02
last_modified_at: 2023-12-02
categories: [Dev Paper]
tags: [Console, C언어, 콘솔게임]
---git 

언젠가 콘솔 게임을 한번 한번 만들어보고 싶었다.

하지만 막상 구현하려다 보니 감이 오지 않았다.



음... 구현할 수 있는게 뭐가 있을까...?



1.너무 어렵지 않으면서
2.내가 구현 할 수 있는 수준이여야 하고
3.다른사람의 코드를 봐도 즉시 이해가 가능한 오픈소스 코드가 있어야한다.



라는게 시발점이였다. 



일단 생각나는 게임이 크롬(Chrome)의 다이노 게임 -> https://dinorunner.com/ 과 1945 였는데

방탈출, 미로, 스토리 게임은 필자의 흥미와 맞지 않았으므로 제외됐다.

그게 내가 "Flight Front Line 1945" 를 만들게 된 이유다.



첫날은 간단한 게임 디자인 구성하고, 메인메뉴를 만들었다.
텍스트를 아스키로 변환해 주는 것도 있었지만
손수 그리고 싶었기에 (지금 생각하면 왜라는 생각이 든다),
노가다를 조금 했다.

첫날은 무난히 흘러갔다.

![메인 메뉴](Flight Front Line 1945.jpg)

```c
#include <stdio.h>

int main(int argc, char *argv[]) {
  printf("Hello World!\n");
  return 0;
}

// => prints 'Hello World!' to STDOUT.
```

Check out the [Jekyll Paper docs][jekyll-paper-docs] or [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. If you have questions or suggestions, you can create an issue to asking them on [Jekyll Paper Issues][jekyll-paper-issues] or [Jekyll Talk][jekyll-talk].

[jekyll-paper-docs]: https://github.com/ghosind/Jekyll-Paper/wiki
[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-paper-issues]: https://github.com/ghosind/Jekyll-Paper/issues
[jekyll-talk]: https://talk.jekyllrb.com/
