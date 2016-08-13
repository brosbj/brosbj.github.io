---
published: true
layout: post
title: 'Android Java & Kotlin..'
modified: null
categories: android
excerpt: null
tags:
  - Java
  - Kotlin
image:
  feature: null
date: 2016-08-13T11:01:50.000Z
---

Android가 릴리즈 되고-  
별문제가 없이 사용이 되던 Java에 대한 ~~법률회사(?)~~ 오라클의  
소송으로 인해 Java의 대안언어가 하나 둘 나타나고 있다.  

---
#### Kotlin

코틀린이야 말로 현재 대안언어 1순위로 급부상하고 있는데,  
JVM기반의 언어 그리고 Java와의 상호작용이 100%이기에 대안언어로  
확실히 자리를 잡으려고 노력하고 있다.  

뭐 특징으로는,

- 장황했던 자바와 비교하면 눈물날 정도로 간결한 문법을 제공한다. 간결한 문법을 제공하면서도 런타임 오버헤드가 거의 없다.
- 오버헤드 없는 널 안전성을 제공한다. 코틀린의 변수는 Nullable(널 값 사용 가능)과 NotNull(널 값 사용 불가)로 나뉘는데, 변수 선언 시 '?'를 붙여 Nullable로 만들 수 있다.
- 예외를 검사하지 않는다.
- 확장함수, 연산자 오버로딩을 지원한다.
  예를 들어 Int형을 확장해 'i = 3 power 4' 식으로 새 연산자를 만들 수 있다.
  API 문서에 자바의 HTML대신 Markdown을 사용한다.

- == 연산자가 생각하는 대로 작동한다.
- 자바에서는 String i와 String j가 같은 문자열을 담고 있어도 가리키는 객체가 다르므로 i == j는 false이다. 코틀린에서 ==는 equals()와 똑같이 작동한다. 따라서 i == j는 true다. 자바의 ==를 쓰려면 ===를 쓰면 된다. !=는 !== 
- Static 메서드가 없다. companion object를 사용하자. 자바 코드에서 접근하려면 '클래스명.Companion.메서드_혹은_get변수명()'을 쓰면 된다.
- 자바6에 호환된다.  

뭐 이정도가 있는데 Android Studio를 만든 JetBrains에서 개발한터라  
IDE와의 효율도 상당히 좋고, 관련 플러그인 적용도 상당히 쉬운 편-  


