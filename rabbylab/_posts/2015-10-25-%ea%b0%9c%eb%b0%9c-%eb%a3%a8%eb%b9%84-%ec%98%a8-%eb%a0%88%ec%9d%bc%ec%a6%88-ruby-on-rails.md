---
id: 123
title: '[개발] 루비 온 레일즈 (Ruby On Rails)'
date: 2015-10-25T14:30:00+00:00
author: rabby
layout: post
guid: https://rabbylab.wordpress.com/2015/10/25/%ea%b0%9c%eb%b0%9c-%eb%a3%a8%eb%b9%84-%ec%98%a8-%eb%a0%88%ec%9d%bc%ec%a6%88-ruby-on-rails
permalink: /%ea%b0%9c%eb%b0%9c-%eb%a3%a8%eb%b9%84-%ec%98%a8-%eb%a0%88%ec%9d%bc%ec%a6%88-ruby-on-rails/
blogger_blog:
  - rabbyintern.blogspot.com
blogger_author:
  - Joeun Ha
blogger_aa75354ca4f56bffaa1a6e3a3b165eeb_permalink:
  - 1184982430730665425
categories:
  - internship 2015-2
---
서버 개발을 위해 조금 배운 레일즈에 관한 지식과 느낀 점을 나누고자 합니다.

## <span style="font-size: large;">루비 온 레일즈 <span lang="EN-US">(Ruby On Rails)</span></span>

<img class="size-medium wp-image-137 alignleft" src="http://rabbylab.xyz/blog/wp-content/uploads/2016/01/ef255-rubyrails-300x150.png" alt="ef255-rubyrails" width="300" height="150" srcset="http://rabbylab.xyz/blog/wp-content/uploads/2016/01/ef255-rubyrails-300x150.png 300w, http://rabbylab.xyz/blog/wp-content/uploads/2016/01/ef255-rubyrails.png 640w" sizes="(max-width: 300px) 100vw, 300px" />

<div>
  소개
</div>

<div style="text-align: justify;">
</div>

<div style="text-align: justify;">
  레일즈는 웹 어플리케이션을 빠르게 개발하기 위한 좋은 도구이다<span lang="EN-US">. </span>루비를 기반으로 만든 프레임워크인 레일즈는 국내에서는 널리 알려진 언어는 아니지만 해외에서는 웹 어플리케이션 개발을 위해 많은 사람들이 레일즈를 사용하고 있다<span lang="EN-US">. </span>레일즈는 세가지 철학을 기반으로 만들어진 언어이다<span lang="EN-US">. </span>첫번째<span lang="EN-US">, ‘DRY : Don’t Repeat Yourself’ </span>일명 드라이라고 불리는 이 원칙은 코드의 반복을 피하도록 하자는 것이다<span lang="EN-US">. </span>반복된 코드는 나쁜 것이라고 보고 코드의 재활용성을 중요시한다<span lang="EN-US">. </span>둘째<span lang="EN-US">, ‘</span>설정보다는 관습<span lang="EN-US">(Convention Over Configuration)’ </span>이라는 것이다<span lang="EN-US">. </span>일명 <span lang="EN-US">CoC</span>라고 부르는데 프로그래머가 개발을 하면서 겪는 어려움인 설정의 부분에서 굳이 각자가 새로운 설정을 할 필요가 없다는 것이다<span lang="EN-US">. </span>관례적으로 정해둔 방식으로 변수명이나 파일명을 정하기만 하면 그에 상응하는 기능을 수행하도록 사전에 설정해둔 특징들을 일컫는다<span lang="EN-US">. </span>마지막으로 세번째는 <span lang="EN-US">‘REST</span>는 웹 어플리케이션의 최고의 패턴이다<span lang="EN-US">.’ </span>라는 것인데 <span lang="EN-US">RESTful </span>아키텍쳐에 대해서 잘 이해하지 못했고 실제로 사용해보지 못한 부분이다<span lang="EN-US">.</span>
</div>

<div style="text-align: justify;">
  <span lang="EN-US"> </span>
</div>

<div style="text-align: justify;">
  <span lang="EN-US"> </span>
</div>

<div style="text-align: justify;">
  <span lang="EN-US">느낀 점</span>
</div>

<div style="text-align: justify;">
</div>

<div style="text-align: justify;">
  <span lang="EN-US"><span style="font-family: 'Times New Roman'; line-height: normal;"> </span></span>레일즈를 사용하면서 가장 신기했던 것은 <span lang="EN-US">GEM(</span>젬<span lang="EN-US">)</span>이었다<span lang="EN-US">. Gemfile</span>에 사용하고 싶은 모듈을 작성하고 <span lang="EN-US">‘gem bundle install’</span>이라는 명령어만 터미널에 입력해주면 해당 모듈을 설치해주고 이를 개발에 즉시로 사용할 수 있었다<span lang="EN-US">. </span>이를 활용해서 블로그를 만들어보기도 했는데<span lang="EN-US">, 5</span>분만에 블로그 만들기를 가르쳐주는 유투브동영상이 있어서 쉽게 따라할 수 있었다<span lang="EN-US">. </span>레일즈는 <span lang="EN-US">MVC</span>모델을 기반으로 사용하는데 이때까지만 해도 <span lang="EN-US">MVC</span>모델이 정확하게 어떤 느낌으로 작동하는지를 이해하지 못했다<span lang="EN-US">. </span>성금영 교수님의 소프트웨어 공학 수업에서 배운 내용임에도 불구하고 실제 서비스를 개발하면서 사용되는 개념은 무척 낯설게만 느껴졌다<span lang="EN-US">. </span>결과적으로 레일즈로 개발하는 것은 <span lang="EN-US">2</span>주정도로 그쳤기 때문에 지금 중간보고서를 작성하는 시점에는 별로 기억에 남는 것이 없다<span lang="EN-US">. </span>허나 레일즈라는 프레임워크를 경험함으로써 프레임워크가 왜 필요하고 얼마나 개발을 쉽게 도와주는지 알 수 있었고 설령 다른 언어로 개발하더라도 할 수 있겠다는 자신감을 갖게 해주었다<span lang="EN-US">.</span>
</div>

<!--EndFragment-->