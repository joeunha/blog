---
id: 15
title: 자바스크립트를 선택한 이유
date: 2015-07-17T21:10:11+00:00
author: rabby
layout: post
guid: https://rabbylab.wordpress.com/?p=15
permalink: /javascript-intro-1/
geo_public:
  - 0
categories:
  - rabbylab(wordpress)
tags:
  - javascript
---
<p style="text-align:left;">
  세상에는 수 많은 프로그래밍 언어가 존재하고 그 언어들은 제 각기 배움의 가치가 있습니다. 때문에 제 각기 배움의 이유가 존재합니다. 다수의 프로그래밍 언어 서적들은 &#8216;왜 많은 언어 중에 이 언어를 배워야하는가?&#8217; 하는 질문을 답하며 책을 시작합니다. 그렇다면 저는 왜 자바스크립트를 선택했을까요?
</p>

<h4 style="text-align:left;">
  <strong>프로그래밍 경험</strong>
</h4>

<p style="text-align:left;">
  대다수의 컴퓨터공학 전공자들이 그러하듯 저 역시 C언어로 프로그래밍에 입문했습니다. &#8216;hello world&#8217;를 출력하고 기본적인 연산 프로그램을 만들며 별거 아닌데? 라는 생각이 들때쯤 배열과 포인터의 늪을 허덕였습니다. 이후 다양한 응용 과제와 씨름하며 밤새워 한번 앉아서 8시간씩 코딩을 하면서도 문제를 해결했을 때의 그 쾌감 때문에 프로그래밍에 빠져들게 되었습니다. 이어서 자바, C++등을 배웠습니다. 이후 배운 것을 근간으로 프로젝트를 수행하기도 했습니다. 자바를 이용한 안드로이드 앱 개발이 대표적이죠. 제가 배운 언어를 사용할 일이 있을 때 그 언어는 빛을 발하고 정말 재밌다는 것을 느낄 수 있었습니다.
</p>

<p style="text-align:left;">
  아쉬운 것은 스마트 디바이스의 출현으로 실질적으로 와닿는 프로그램을 만들기 위해서는 C나 자바가 다소 어렵게 느껴지는 경우가 많다는 것이었습니다. 물론 오랜 시간을 투자해서 네이티브 앱을 만들어내려고 한다면 자바는 충분히 가치가 있습니다. 허나 학회활동이나 수업에서 사용되고 만들어야 하는 수준의 프로그램은 실제 배포판이 아닌 어느정도 구색을 갖춘 프로토 타입 수준의 어플리케이션이면 되는 것이었습니다. 조금 간편하게 만들고 운영체제에 무관하게 사용해볼 수 있는 프로그램이 필요했던 것입니다.
</p>

<p style="text-align:left;">
  웹앱(web app)이 이에 적합한 형태의 프로그램이었습니다. 방학 중 Do it! 시리즈 중 한권인 &#8216;<a href="http://www.easyspub.co.kr/20_Menu/BookView/B001/90" target="_blank">쉽게 배우는 웹앱&하이브리드앱</a>&#8216;을 잡고 공부를 했습니다. <a href="https://opentutorials.org/course/668" target="_blank">생활코딩 &#8211; 클라이언트</a> 강의와 함께 HTML, CSS, jQuery의 기초를 공부하면서 웹앱의 기초를 익혔습니다. 허나 책을 다봤는데도 실제 어플리케이션을 만들 수준이 되지 않음을 깨달았습니다. 이에 <a href="https://opentutorials.org/course/1688" target="_blank">생활코딩 &#8211; 웹 애플리케이션 만들기</a> 강의를 보며 php, mysql, javascript 에 대해 배웠습니다. 이를 배우는 과정에서 간단하게 만들어 본 1차 결과물이 <a href="https://github.com/joeunha/taleline" target="_blank">taleline</a> 입니다. 지금은 정말 아무것도 아닌 상태로 남아있는 이 웹앱을 제대로 만들어보고 싶은 마음이 생긴 것이 발단이었습니다.
</p>

<p style="text-align:left;">
  어떻게하면 이 앱을 제대로 만들어 볼 수 있을까 하는 고민을 하기 시작했습니다. 현재 제가 처한 여러가지 상황을 놓고 고민했을때 저에게는 두가지 선택지가 있음을 깨달았습니다. 첫째, 지금처럼 얇고 넓게 조금씩 배우며 혼자 개발한다. 둘째, 한가지 언어를 깊게 파서 내공을 쌓은 뒤 누군가와 협력해서 개발한다. 주위의 선배들과 커뮤니티의 선배님들의 조언을 살펴 저는 한가지 언어를 깊게 파는 것을 선택했습니다.
</p>

<h4 style="text-align:left;">
  <strong>왜 자바스크립트를 선택했나? </strong>
</h4>

<p style="text-align:left;">
  사실 딱히 어떤 이유로 자바스크립트를 배워야겠다고 생각한 것은 아닙니다. 매력에 이끌렸다고 할까요? 특히 자바스크립트가 가지는 자유로움에 끌렸습니다. 운영체제를 가리지 않는 자유로움, 변수 타입에 제한을 두지 않는 자유로움, 또 웹이 확장되어가고 탈웹의 흐름에 따라 더 많은 곳에서 사용될 가능성이 저를 매료시켰습니다. 생활코딩 강의를 들으면서도 jQuery 같은 강력한 라이브러리가 자바스크립트에 기반을 두고 있다는 사실이 이 언어를 매력적으로 보이게 만들었습니다.
</p>

<p style="text-align:left;">
  앞선 자바스크립트의 매력 요소가 분명 이 언어를 선택함에 어느정도 영향을 준 것이 분명합니다. 하지만 자바스크립트가 저에게 필요하지 않았더라면 아무리 매력적이라고 해도 이 언어를 선택하지 않았을 것입니다. 그 필요는 연습삼아 만들어본 taleline 이라는 앱을 완성시키고 싶은 마음에서 출발합니다. 이 앱을 완성하기 위해 C나 자바를 배우는 것은 무의미합니다. 필요한 서비스를 구현하기 위해 필요한 언어를 배우기로 한 것이죠. 또한 지대한 영향을 끼쳤던 것은 제가 사용하는 스마트워치 &#8216;Pebble Time&#8217;의 개발 언어가 자바스크립트를 기반으로 한 <a href="http://developer.getpebble.com/getting-started/pebble-js-tutorial/part1/" target="_blank">pepple.js</a>(originally <a href="http://simplyjs.io/" target="_blank">simply.js</a>)였기 때문입니다. 가까이 두고 사용하고 있는 기기인만큼 새로운 앱에 대한 아이디어가 종종 떠올랐는데 이를 직접 만들어보고 싶었기 때문입니다.
</p>

<h4 style="text-align:left;">
  <strong>필요해서 배운다!<br /> </strong>
</h4>

<p style="text-align:left;">
  결국 필요에 의해 자바스크립트를 선택했다라고 말할 수 있겠습니다. 결론은 너무 당연한 것을 이야기하는 것 같습니다. 결국 모든 언어를 배우는 이유는 해당 언어가 자신이 만들고자 하는 서비스에 꼭 필요한 기능을 가졌거나 그 언어로 작업했을 때 발생하는 효용이 있기 때문이라는 겁니다.
</p>