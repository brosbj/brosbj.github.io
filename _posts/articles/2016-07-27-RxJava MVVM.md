---
published: true
layout: post
title: 'RxJava, MVP, MVVP &'
modified: null
categories: article
excerpt: null
tags:
  - RxJava
  - MVVM
  - MVP
image:
  feature: null
date: 2016-07-28T11:01:50.000Z
---
Android 개발을 2010년부터 시작했으니, 
6년여를 넘게 해오고 있는데-

그 사이 관련 개발 패러다임도 많은 변화가 있었고, 
더 좋아지려는(?) 변화도 이제 어느정도 자리를 잡은 듯 하다.

따라서 초기에 Google에서 제시한 개발 방법론도 이제는 오픈소스로 유명한 Square나 
Netflix등등 어마어마한 개발 진영들에 의해 변화가 많이 이루어지고 있으며, 
지금은 딱 과도기가 아닐까 하는 생각이 든다.

### RxJava
Netflix에서 닷넷에서 사용되던 리액티브 관련 기술을 Java에 적용시켜 만들어버렸고,
SoundCloud쪽에서 Android에도 적용가능한 RxAndroid로 확장까지 시켜버렸는데-

이게 나와버리니 기존 Android에서 제시한 모든 개발 방법론을 사용하지 않고,
반응형 프로그래밍으로 모든 것으로 만들어 버릴 수 있게끔 되어 버렸는데-

관련 책을 사보고, 공부해 보았는데.
(책은 얇디 얇은 RxJava Essentials 라는 책밖에 없고, 조악한 종이질이 경악스럽다.)

아직 생각보다 진입장벽, 즉 러닝커브가 너무 커서 쉽사리 자리 잡긴 어렵지 않나- 
라는 정도.

또한 혼자 사용한다면 어느정도 관련 효율을 낼 수 있을리라 보이는데,
요걸 협업해서 만든다면-

아직 시기상조가 아닐지 싶다.

그래도 자리가 잡힌다면(?) 콜백 더하기 콜백에 빠진 안드로이드를 구출해 낼 수 있어보이는 
유용한 도구임에는 틀림 없어 보인다.

### MVVM, MVP
디자인 패턴 관련해서는 예로부터 끊임없이 공부해도 쉽지 않은-
익숙해지지 않는 부분 중에 하나인데,
요 근래들어 MVP/MVVM에 관심이 가서 많이 보고 있는 중이다.

컨퍼런스에서 발표하는 국내/국외 Android 개발진영에서는 MVP패턴으로 어느정도 자리잡혀
개발이 이루어지는 것으로 보이는데,

난 되려 DataBinding + MVVM 이 더 효율적이지 않나 라는 생각이 들어서 그쪽으로 
많이 보고 있다.

---

결과적으론 MVP, MVVM이던 MVW(Whatever) 든지 간에 
이것 만이 현재 정답이라는 부분은 없는 것으로 보이고,
상황에 맞게 적용하는 것-
개발자의 센스와 합쳐진다면 효율적으로 코딩할 수 있는 방법이라는 생각.

뭐 이러한 패턴들이 이루고자 하는 방향은 결국 loose coupling에 테스트 가능한 모듈 쪼개기로
방향성은 같기에 선택하는 것은 해당 설계/개발자의 몫으로...

확실히 정답이 없는 문제는 공감대도 형성하기 어렵고, 설득도 쉽지가 않다.








#### 참고자료 : 
---
##### [Google Doc DataBinding](https://developer.android.com/topic/libraries/data-binding/index.html)
##### [최범균님 MVP소개 SlideShare](http://www.slideshare.net/madvirus/mvp-63161829)


